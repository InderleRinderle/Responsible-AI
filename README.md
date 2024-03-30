---
# For reference on dataset card metadata, see the spec: https://github.com/huggingface/hub-docs/blob/main/datasetcard.md?plain=1
# Doc / guide: https://huggingface.co/docs/hub/datasets-cards
{{ card_data }}
---

# Dataset Card for "A Collection of 120 Psychology Patients with 17 Essential Symptoms to Diagnose Mania Bipolar Disorder, Depressive Bipolar Disorder, and Normal Individuals"

<!-- Provide a quick summary of the dataset. -->

This dataset consists of information from 120 patients who were diagnosed with mania bipolar disorder, depressive bipolar disorder, major depressive disorder, or normal (none of the others). It also includes the level of severity reported by patients for 17 symptoms related to the diagnoses.

## Dataset Details

### Dataset Description

<!-- Provide a longer summary of what this dataset is. -->

This dataset comprises 120 samples of patients diagnosed with either mania bipolar disorder, depressive bipolar disorder, and major depressive disorder as well as normal. All patient information was gathered from a private psychology clinic. The dataset also contains the patient severity levels for 17 essential symptoms that psychiatrists use to diagnose the described disorders. These symptoms include: 

*Sadness, Exhaustness, Euphoric, Sleep disorder, Mood swings, Suicidal thoughts, Anorexia, Anxiety, Try-explaining, Nervous breakdown, Ignore & Move-on, Admitting mistakes, Overthinking, Aggressive response,    Optimism, Sexual activity, and Concentration* 

The Normal category refers to the individuals using therapy time for specialized counseling, personal development, and life skill enrichments. While such individuals may also have minor mental problems, they differ from those suffering from major depressive disorder or bipolar disorder. All data is organized in a Comma Separated Value (CSV) format. (2023-10-02)


- **Curated by:**
  - **Karbalaeipour, Hengameh** (PhD, Department of Psychology, Science and Research Branch, Islamic Azad University, Tehran, Iran)
  - **Damari, Siavash** (MSC, Department of Statistics, Mathematics, and Computer Science, University of Allameh Tabataba’i, Tehran, Iran)
  - **Zolfagharnasab, Mohammad Hossein** (MSC, Department of Statistics, Mathematics, and Computer Science, University of Allameh Tabataba’i, Tehran, Iran)
  - **Haghdadi, Amin** (MSC, Department of Statistics, Mathematics, and Computer Science, University of Allameh Tabataba’i, Tehran, Iran)

- **Funded by:**
  - It is unclear if this dataset was directly funded by an organization. It should be noted that all authors of the dataset were attending either the Islamic University or the University of Allameh Tabataba’i in Tehran, Iran. While it is expected that this dataset is in conjunction with the authors’ work at these universities, and could be funded in part through these organizations, further inquiry is possible by contacting the authors for more information through the “Contact Owner” button at [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0FNET5 ).

- **Language(s) (NLP):** Dataset information is written in English.

- **License:** [CCO: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)

### Dataset Sources

<!-- Provide the basic links for the dataset. -->

- **Repository:**
  - Original dataset found at [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0FNET5)
  - Version of dataset found on [Kaggle](https://www.kaggle.com/datasets/cid007/mental-disorder-classification/data)

## Uses

<!-- Address questions around how the dataset is intended to be used. -->

This dataset is intended to showcase how patterns in symptoms can influence patient diagnoses for the disorders included within this dataset. However, due to the limited scope of this dataset, it should not be used as a tool to self-diagnose or diagnose others in regards to mental disorders.

### Direct Use

<!-- This section describes suitable use cases for the dataset. -->

- This dataset could be used to find correlations between symptoms and diagnoses for the given disorders for this specific patient population. 
- This dataset could be used to help highlight discrepancies in how this psychology clinic diagnoses its patients by comparing how symptom responses vary among patients who received the same diagnosis.
- In conjunction with other more robust datasets regarding psychiatric diagnoses, this dataset could be used to try and identify larger trends between symptom severity and diagnosis outcome.

### Out-of-Scope Use

<!-- This section addresses misuse, malicious use, and uses that the dataset will not work well for. -->

- There is not enough information from this dataset alone to attempt to procure a diagnosis for an individual based on their own responses to the observed symptoms.
- Any discovered correlation between symptoms and diagnosis within this dataset alone should not be used to conclude broader patterns in psychiatry/psychology.
- This dataset should not be used as a replacement for medical advice. For matters regarding mental health medical professionals should be consulted.


## Dataset Structure

<!-- This section provides a description of the dataset fields, and additional information about the dataset structure such as criteria used to create the splits, relationships between data points, etc. -->

The dataset was created using the Comma Separated Value (CSV) format. Patient responses and diagnoses are joined to the patient. Response types for specific symptoms was broken down in the following way:
- Reported *Sadness, Euphoric, Exhausted, and Sleep Disorder* values were reported in their frequency.
  - Values were either Usually, Most-often, Sometimes, or Seldom
- Reported *Mood Swing, Suicidal Thoughts, Anorexia, Authority Respect, Try-Explanation, Aggressive Response, Ignore & Move On, Nervous Breakdown, Admit Mistakes, and Overthinking* values were reported as having occurred or not occurred recently.
  - Values were either Yes or No
- Reported *Sexual Activity, Concentration, and Optimisim* values were reported on a scale.
  - Values were reported on a scale of 1-10 out of 10

## Dataset Creation

### Curation Rationale

<!-- Motivation for the creation of this dataset. -->

There is no stated curation rationale for the creation of this dataset, and it would be good to question the dataset authors on their intent for its use. Presumably this dataset was created for purposes of mental health evaluation or to compare the prevalency of symptoms and resulting diagnoses, but this is an assumption.

### Source Data

<!-- This section describes the source data (e.g. news text and headlines, social media posts, translated sentences, ...). -->

#### Data Collection and Processing

<!-- This section describes the data collection and processing process such as data selection criteria, filtering and normalization methods, tools and libraries used, etc. -->

All of the data comes from patient information from a private psychology clinic. This data was processed into this dataset in Comma Separated Format (CSV) by the dataset curators. Patient information only included diagnoses for the four included diagnoses. It is unclear what selection processes were used to choose which patients with a specific diagnosis at the clinic would be included within this dataset. There also appear to be no further normalization/data tools used. Total frequencies of responses for symptom severity levels was simplified to percentages for each symptom. Further inquiry on the selection/processing choices could be directed to the dataset authors.

#### Who are the source data producers?

<!-- This section describes the people or systems who originally created the data. It should also include self-reported demographic or identity information for the source data creators if this information is available. -->

The source data producers are the patients at the psychology clinic. Their reported symptom severity alongside their formal diagnoses make up the entirety of the dataset. Personal data is anonymized making specific demographic information unknown. The dataset includes: 
- 30 Normal
- 28 Bipolar Type-1 (mania bipolar disorder)
- 31 Bipolar Type-2 (depressive bipolar disorder)
- 31 Depression (major depressive disorder)

### Annotations

<!-- If the dataset contains annotations which are not part of the initial data collection, use this section to describe them. -->

#### Annotation process

<!-- This section describes the annotation process such as annotation tools used in the process, the amount of data annotated, annotation guidelines provided to the annotators, interannotator statistics, annotation validation, etc. -->

While there is not any direct annotation used on this dataset it should be noted that the original dataset was transferred onto [Kaggle](https://www.kaggle.com/datasets/cid007/mental-disorder-classification/data) by Chirag Desai. It is unclear if Chirag Desai further formatted the data into the easily digestible format that it is currently presented with on Kaggle.

#### Personal and Sensitive Information

<!-- State whether the dataset contains data that might be considered personal, sensitive, or private (e.g., data that reveals addresses, uniquely identifiable names or aliases, racial or ethnic origins, sexual orientations, religious beliefs, political opinions, financial or health data, etc.). If efforts were made to anonymize the data, describe the anonymization process. -->

This dataset contains patient health data which is personal and sensitive information. All patients are anonymized, presented as "Patient-(number)" but it is unclear how these patients were randomly anonymized. The private psychology clinic likely was responsible for anonymizing the data before it was released for use within this dataest. The fact that the clinic is also never named helps further protect patient health data.

## Bias, Risks, and Limitations

<!-- This section is meant to convey both technical and sociotechnical limitations. -->

- As all the data is from a singular clinic, there is inherent bias in the demographic variety that would receive care there. Additionally, there may be bias in how medical professionals prescribe diagnoses for that specific clinic. 
- Additionally, any demographic biases that may be present among patients are unknown and cannot be interpreted through this dataset due to the protected nature of patient information.
- Furthermore, the dataset is relatively small for each diagnosis, and should not be considered comprehensive.
- While the 17 symptoms listed provide a large scope, it is by no means enough information for overall diagnosis. Psychiatrists/psychologists look at a variety of factors alongside these self-reported symptoms when determining diagnosis for patients. This dataset does not encompass all of those other factors.
  - Further information on the process to receive a diagnosis is outlined here by [Mayo Clinic](https://www.mayoclinic.org/diseases-conditions/mental-illness/diagnosis-treatment/drc-20374974).
- The use of “normal” as a category within this dataset may be misleading as those patients may exhibit traits and behaviors that could lead to a different diagnosis beyond the three mentioned within this dataset.

### Recommendations

<!-- This section is meant to convey recommendations with respect to the bias, risk, and technical limitations. -->

- The formal diagnosis of any psychiatric condition can come with both stigmatization and burden for the individual, so caution must be taken to prevent the use of datasets like this one for diagnosis.
- Further implementation of this dataset should continue to take precautions to ensure the health information of the patients within the dataset remain anonymous and non-identifiable.
- Additionally, care should be taken with the implementation of machine learning in assisting the treatment and diagnosis of mental health disorders due to the potential consequences and outcomes.


## Citation

<!-- If there is a paper or blog post introducing the dataset, the APA and Bibtex information for that should go in this section. -->

Karbalaeipour, Hengameh; Damari, Siavash; Zolfagharnasab, Mohammad Hossein; Haghdadi, Amin, 2023, "A Collection of 120 Psychology Patients with 17 Essential Symptoms to Diagnose Mania Bipolar Disorder, Depressive Bipolar Disorder, Major Depressive Disorder, and Normal Individuals", https://doi.org/10.7910/DVN/0FNET5, Harvard Dataverse, V1

## Glossary

<!-- If relevant, include terms and calculations in this section that can help readers understand the dataset or dataset card. -->

- ***Mania bipolar disorder* (listed as Bipolar Type-1)** is defined by [Cleveland Clinic](https://my.clevelandclinic.org/health/diseases/9294-bipolar-disorder) as an individual who has experienced one or more episodes of mania, usually alongside an episode of depression lasting at least two weeks. Manic episodes must last at least seven days or require hospitalization for diagnosis. Mixed states are also possible for individuals to experience (both manic and depressive symptoms during an episode).
- ***Depressive bipolar disorder* (listed as Bipolar Type-2)** is defined by [Cleveland Clinic](https://my.clevelandclinic.org/health/diseases/9294-bipolar-disorder) similarly to mania bipolar disorder with the experience of depressive and hypomanic episodes. Individuals will not experience a full manic episode as seen in mania bipolar disorder. Chronic depression is more common in depressive bipolar disorder versus mania bipolar disorder.
- ***Major depressive disorder* (listed as Depression)** is defined by [Cleveland Clinic](https://my.clevelandclinic.org/health/diseases/24481-clinical-depression-major-depressive-disorder) as persistently low or depressed mood and a loss of interest in activities that one used to enjoy with symptoms lasting for at least two weeks. It is normally a chronic condition.
- ***Normal* (listed as Normal)** is defined within this dataset as patients with minor symptoms but who did not warrant receiving a diagnosis.


## More Information

It should be noted that overall there is ongoing debate and concern in regards to the current process to diagnose mental health disorders. Most psychiatric disorders (at least in the USA) are diagnosed using the Diagnostic and Statistical Manual of Mental Illnesses (DSM) created by the American Psychiatric Association. 

Critics of the DSM claim that the lines between specific diagnoses are not clear or accurate, as highlighted by the large number of misdiagnoses in regards to mental health. Additionally, many factors may play a role in the symptoms an individual is experiencing beyond what is outlined in the DSM, which is why consultation with a medical professional is so important. As machine learning datasets continue to be used in the field of mental health disorders, it will be increasingly important to ensure careful implementation and a nuanced understanding of the nature of these disorders.


## Dataset Card Authors

The original data card was created by the original dataset authors as listed through Harvard Dataverse. Further collaboration in converting the dataset and data card to kaggle.com was provided by Chirag Desai. Further edits alongside additional discussion, specifically in regards to bias, risks, limitations, and recommendations, provided by Michael Rinderle.

## Dataset Card Contact

- Original dataset authors can be contacted through “Contact Owner” button on [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0FNET5)
- Chirag Desai can be contacted through kaggle.com as user cid007
- Michael Rinderle can be contacted through email at mjr246@case.edu
