# Title: Datasheets & Clinical Trials 

#### By: Diego Cardenas & Kiran Treacy

## Abstract

Here you type a 3-4 sentence summary of your final project.


_________________________________________________________________________________________________________________________________________________________
## Introduction and Background

Convince your audience that the rest of the project is worth learning about. 
What interesting problem are you exploring? Why should EVERYONE be interested in your analysis?

_________________________________________________________________________________________________________________________________________________________
## Data Colleciton Considerations

1.1 Why was the dataset created?

To provide a consolidated list of COVID-19 related clinical trials conducted globally.

The intended purpose appears to be exploratory data analysis, trend visualization, and educational use on Kaggle.

1.2 Who created the dataset?

The dataset was uploaded and curated by Kaggle user Parul Pandey.

Trial metadata originally comes from public trial registries (e.g., ClinicalTrials.gov).

1.3 What tasks is the dataset intended to support?

Summaries of global COVID-19 clinical research activity

Exploratory analysis

Visualization of trial types, phases, sponsors, enrollment

Meta-analysis of trial characteristics (NOT patient outcomes)

1.4 What tasks should NOT be done with the dataset?

Individual patient-level inference (dataset contains no patient-level sensitive data, but users should not attempt to infer it).

Medical decision-making.

Claiming causal conclusions about treatment effectiveness.

Linking to other datasets for identification.
________________________________________________________________________________________________________________________

2.1 What does the dataset contain?

Typically includes metadata such as:

Trial ID (NCT Number)

Trial title

Study type (interventional, observational)

Sponsor information

Enrollment size (aggregate)

Study phase

Intervention type

Outcome measures

Study start/end dates

Locations

Recruitment status

2.2 What does the dataset not include?

No individual patient-level data

No identifiable personal information

No detailed clinical outcome data

No consent forms or trial protocols

2.3 Is any sensitive information included?

No direct personal health information.

But: Aggregate counts (e.g., enrollment) still originate from human subject research — should be treated respectfully and ethically.

2.4 Are there missing values, inconsistencies, or noise?

Likely yes:

Missing trial phases

Undefined interventions

Outdated recruitment status

Categorical inconsistencies (common across scraped datasets)

________________________________________________________________________________________________________________________

2.1 What does the dataset contain?

Typically includes metadata such as:

Trial ID (NCT Number)

Trial title

Study type (interventional, observational)

Sponsor information

Enrollment size (aggregate)

Study phase

Intervention type

Outcome measures

Study start/end dates

Locations

Recruitment status

2.2 What does the dataset not include?

No individual patient-level data

No identifiable personal information

No detailed clinical outcome data

No consent forms or trial protocols

2.3 Is any sensitive information included?

No direct personal health information.

But: Aggregate counts (e.g., enrollment) still originate from human subject research — should be treated respectfully and ethically.

2.4 Are there missing values, inconsistencies, or noise?

Likely yes:

Missing trial phases

Undefined interventions

Outdated recruitment status

Categorical inconsistencies (common across scraped datasets)
__________________________________________________________________________________________________________________________________________________

3.1 How was the data collected?

Most likely scraped, extracted, or downloaded from ClinicalTrials.gov and other public registries.

The Kaggle author cleaned and reformatted it.

3.2 Is the original data source public?

Yes — clinical trial registries are legally required to be publicly accessible.

3.3 Was consent obtained for data sharing?

Patient-level consent is part of the original trial design, NOT required for metadata sharing

Metadata (titles, enrollment, endpoints) is legally public.

3.4 Potential risks in collection?

Web-scraping errors

Incomplete metadata

Versioning issues (trial updates not automatically synced)
__________________________________________________________________________________________________________________________________________________

4.1 What transformations were applied?

Reformatting

Consolidation from multiple registry sources

Removal of duplicate trials

Conversion to CSV

Possible renaming of columns

Standardization of categorical fields

4.2 Was any anonymization needed?

No — because no patient-level data was included.

4.3 Known issues from preprocessing?

Loss of detail from original registry

Potential misclassification of phase or intervention

Dates may have been simplified or converted incorrectly

Some fields may not match ClinicalTrials.gov exactly
__________________________________________________________________________________________________________________________________________________
5.1 Appropriate uses

Educational purposes

Visualization of trends

Analysis of trial growth over time

Comparing types and phases of studies

Understanding global research focus during COVID-19

5.2 Inappropriate or harmful uses

Claiming clinical conclusions from metadata alone

Misrepresenting trial outcomes

Attempting to reconstruct patient-level data

Policy-making decisions without original trial review

Using the dataset to claim treatment efficacy

5.3 Who is the intended audience?

Students

Data scientists

Public health researchers

Journalists

Non-experts learning exploratory data analysis
__________________________________________________________________________________________________________________________________________________
6.1 Where is the dataset hosted?

On Kaggle:
COVID-19 Clinical Trials Dataset (URL in your assignment)

6.2 What is the license?

Kaggle datasets usually default to CC-BY-NC unless otherwise noted.

Users must verify the licensing on the dataset page.

6.3 Are there restrictions on sharing?

Must credit both Kaggle uploader and the original registry.

Cannot redistribute with identifiable patient data (not applicable here).

Cannot claim the dataset is official or complete
__________________________________________________________________________________________________________________________________________________
8. Maintenance
8.1 Who maintains the dataset?

The Kaggle uploader (Parul Pandey)

Kaggle platform itself does not guarantee updates

8.2 Update frequency

Likely not regularly updated

COVID-19 trials changed rapidly, so the dataset may be outdated

8.3 How can issues be reported?

Through Kaggle’s comment/discussion section

By cross-checking with ClinicalTrials.gov entries and reporting inconsistencies
__________________________________________________________________________________________________________________________________________________

Give some background about your data. Where did you get it? How was it compiled? How many observations? What are the variables? 

Show a data frame with the most important columns.

Do some descriptive statistics and talk about the results.

__________________________________________________________________________________________________________________________________________________

## Exploratory Data Analysis

Show a few plots or some data tables that help your reader understand your data better. What are some initial questions that you were able to quickly answer? How do those questions lead you to a deeper analysis?

_________________________________________________________________________________________________________________________________________________________

## Proposed Questions - Legal and Ethical Considerations 

What specific questions are you going to explore and present in the rest of the paper? Give a very brief overview of what you are going to do to answer those questions. Imagine this as a road map so your reader knows what to expect.

7.1 Human subjects

The dataset originates from clinical trials involving human subjects.

Although metadata is public, users should acknowledge that the data represents real patients and real risks.

7.2 Biases

Potential biases include:

Geographic bias: overrepresentation of U.S., Europe, and China trials

Sponsor bias: industry trials reported differently than academic ones

Population bias within original trials (e.g., adults over children, limited minority recruitment)

Publication bias (not all trials post results)

7.3 Risks of misuse

Overinterpreting metadata

Incorrect claims about treatment effectiveness

Use in misinformation about COVID-19

Comparisons of interventions without proper statistical basis

7.4 Mitigation

Always cite original registry sources

Avoid causal claims

Encourage use only for exploratory and descriptive purposes

Provide context for uncertainty or incomplete metadata
_________________________________________________________________________________________________________________________________________________________
## Analysis and Results

Here is where you show your code and results (plots, tables, predictions, etc) that help to explore and answer your questions. There should be code here that can be run to reproduce your results and conclusions. After each plot/table/final number, you should add a Markdown cell where you explain to the reader what the result means and how/why it answers the question.

_________________________________________________________________________________________________________________________________________________________

## Conclusion

Give a brief statement about what you achieved in your analysis, what issues or limitations your analysis contains, and some possible future directions (if you had more time an money to keep going).
