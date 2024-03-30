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

The Normal category refers to the individuals using therapy time for specialized counseling, personal development, and life skill enrichments. While such individuals may also have minor mental problems, they differ from those suffering from Major Depressive Disorder and Bipolar Disorder. All data is organized in a Comma Separated Value (CSV) format. (2023-10-02)


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

### Direct Use

<!-- This section describes suitable use cases for the dataset. -->

{{ direct_use | default("[More Information Needed]", true)}}

### Out-of-Scope Use

<!-- This section addresses misuse, malicious use, and uses that the dataset will not work well for. -->

{{ out_of_scope_use | default("[More Information Needed]", true)}}

## Dataset Structure

<!-- This section provides a description of the dataset fields, and additional information about the dataset structure such as criteria used to create the splits, relationships between data points, etc. -->

{{ dataset_structure | default("[More Information Needed]", true)}}

## Dataset Creation

### Curation Rationale

<!-- Motivation for the creation of this dataset. -->

{{ curation_rationale_section | default("[More Information Needed]", true)}}

### Source Data

<!-- This section describes the source data (e.g. news text and headlines, social media posts, translated sentences, ...). -->

#### Data Collection and Processing

<!-- This section describes the data collection and processing process such as data selection criteria, filtering and normalization methods, tools and libraries used, etc. -->

{{ data_collection_and_processing_section | default("[More Information Needed]", true)}}

#### Who are the source data producers?

<!-- This section describes the people or systems who originally created the data. It should also include self-reported demographic or identity information for the source data creators if this information is available. -->

{{ source_data_producers_section | default("[More Information Needed]", true)}}

### Annotations [optional]

<!-- If the dataset contains annotations which are not part of the initial data collection, use this section to describe them. -->

#### Annotation process

<!-- This section describes the annotation process such as annotation tools used in the process, the amount of data annotated, annotation guidelines provided to the annotators, interannotator statistics, annotation validation, etc. -->

{{ annotation_process_section | default("[More Information Needed]", true)}}

#### Who are the annotators?

<!-- This section describes the people or systems who created the annotations. -->

{{ who_are_annotators_section | default("[More Information Needed]", true)}}

#### Personal and Sensitive Information

<!-- State whether the dataset contains data that might be considered personal, sensitive, or private (e.g., data that reveals addresses, uniquely identifiable names or aliases, racial or ethnic origins, sexual orientations, religious beliefs, political opinions, financial or health data, etc.). If efforts were made to anonymize the data, describe the anonymization process. -->

{{ personal_and_sensitive_information | default("[More Information Needed]", true)}}

## Bias, Risks, and Limitations

<!-- This section is meant to convey both technical and sociotechnical limitations. -->

{{ bias_risks_limitations | default("[More Information Needed]", true)}}

### Recommendations

<!-- This section is meant to convey recommendations with respect to the bias, risk, and technical limitations. -->

{{ bias_recommendations | default("Users should be made aware of the risks, biases and limitations of the dataset. More information needed for further recommendations.", true)}}

## Citation

<!-- If there is a paper or blog post introducing the dataset, the APA and Bibtex information for that should go in this section. -->

Karbalaeipour, Hengameh; Damari, Siavash; Zolfagharnasab, Mohammad Hossein; Haghdadi, Amin, 2023, "A Collection of 120 Psychology Patients with 17 Essential Symptoms to Diagnose Mania Bipolar Disorder, Depressive Bipolar Disorder, Major Depressive Disorder, and Normal Individuals", https://doi.org/10.7910/DVN/0FNET5, Harvard Dataverse, V1

## Glossary

<!-- If relevant, include terms and calculations in this section that can help readers understand the dataset or dataset card. -->

- **Mania bipolar disorder (listed as Bipolar Type-1)** is defined by [Cleveland Clinic](https://my.clevelandclinic.org/health/diseases/9294-bipolar-disorder) as an individual who has experienced one or more episodes of mania, usually alongside an episode of depression lasting at least two weeks. Manic episodes must last at least seven days or require hospitalization for diagnosis. Mixed states are also possible for individuals to experience (both manic and depressive symptoms during an episode).
- **Depressive bipolar disorder (listed as Bipolar Type-2)** is defined by [Cleveland Clinic](https://my.clevelandclinic.org/health/diseases/9294-bipolar-disorder) similarly to mania bipolar disorder with the experience of depressive and hypomanic episodes. Individuals will not experience a full manic episode as seen in mania bipolar disorder. Chronic depression is more common in depressive bipolar disorder versus mania bipolar disorder.
- **Major depressive disorder (listed as Depression)** is defined by [Cleveland Clinic](https://my.clevelandclinic.org/health/diseases/24481-clinical-depression-major-depressive-disorder) as persistently low or depressed mood and a loss of interest in activities that one used to enjoy with symptoms lasting for at least two weeks. It is normally a chronic condition.
- **Normal (listed as Normal)** is defined within this dataset as patients with minor symptoms but who did not warrant receiving a diagnosis.


## More Information [optional]

{{ more_information | default("[More Information Needed]", true)}}

## Dataset Card Authors

The original data card was created by the original dataset authors as listed through Harvard Dataverse. Further collaboration in converting the dataset and data card to kaggle.com was provided by Chirag Desai. Further edits alongside additional discussion, specifically in regards to bias, risks, limitations, and recommendations, provided by Michael Rinderle.

## Dataset Card Contact

- Original authors can be contacted through “Contact Owner” button on [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0FNET5)
- Chirag Desai can be contacted through kaggle.com as user cid007
- Michael Rinderle can be contacted through email at mjr246@case.edu
