# Title: The Analysis of Covid-19 Clinical Trials Dataset Using Mircrosoft Datasheets for Datasets Framework

#### By: Diego Cardenas & Kiran Treacy

## Abstract: Here you type a 3-4 sentence summary of your final project.

In this final project, we analyze the COVID-19 Clinical Trials dataset using the Microsoft Datasheets for Datasets framework. This approach will provide a structured method for evaluating how the dataset was collected, processed, and documented. By using these datasheet items, we show how to properly analyze real-world data while also identifying the ethical considerations, limitations, and potential risks associated with its use. This project highlights the importance of transparency, responsible data handling, and ethical reasoning in data science.
_________________________________________________________________________________________________________________________________________________________
## Introduction and Background: Convince your audience that the rest of the project is worth learning about. What interesting problem are you exploring? Why should EVERYONE be interested in your analysis?

The COVID-19 pandemic was one of the most global scientific efforts ever. Researchers around the world conducted many clinical trials to test vaccines and treatments. These trials produced an enormous amount of data. Which most of it became publicly accessible. So, we can analyze this COVID-19 trial data such as how the data was collected? How it was processed? And whether it can be responsibly used.

We are exploring the COVID-19 Clinical Trials dataset using the items of Microsoft Datasheets for Datasets framework. We are looking for the dataset’s origins, limits, ethical concerns, and potential biases. This is important because companies will use datasheet items to analyze datasets like these especially human subjects, often containing hidden issues that can affect the accuracy and fairness of the conclusions made. 

Everyone should be interested in this analysis because COVID-19 impacted everyone in the world. So checking this dataset's reliablability, fairness, and accuracy will make sure that we can depend on the items in the datasheet so that the data in the dataset that anyone can have access to is reliable. 
_________________________________________________________________________________________________________________________________________________________
## Data Colleciton Considerations Using the Microsoft Datasheet Format: 

### Motivation for Dataset Creation? 

Why was the dataset created? (e.g., were there specific
tasks in mind, or a specific gap that needed to be filled?)

The dataset was compiled from ClinicalTrials.gov, a public registry created by U.S. law to provide transparency in clinical research. This specific collection of COVID-19 trials was likely assembled to track and analyze the global research response to the pandemic, helping identify active studies, research gaps, and trends.

What (other) tasks could the dataset be used for? Are
there obvious tasks for which it should not be used?

It could be used for meta-research (analyzing trial design trends), epidemiological studies, or network analysis of research collaborations. It should not be used to guide personal medical decisions without consulting full published results.


Has the dataset been used for any tasks already? If so,
where are the results so others can compare (e.g., links to
published papers)?

Data from ClinicalTrials.gov is widely used in systematic reviews and research papers analyzing the COVID-19 research landscape. Results are found in academic journals

Who funded the creation of the dataset? If there is an
associated grant, provide the grant number.

The registry itself is funded by the U.S. National Institutes of Health (NIH). Individual trials within it list various funders

Any other comments? 
_________________________________________________________________________________________________________________________________________________________
## Dataset's Compostition:

What are the instances? (that is, examples; e.g., documents, images, people, countries) Are there multiple types of instances? (e.g., movies, users, ratings; people, interactions between them; nodes, edges)

Each row is a registered clinical trial.

Are relationships between instances made explicit in the data (e.g., social network links, user/movie ratings, etc.)?

Not explicitly stated; must be inferred from shared sponsors or IDs.

How many instances of each type are there?

229 trial records

What data does each instance consist of? “Raw” data (e.g., unprocessed text or images)? Features/attributes?  Is there a label/target associated with instances? If the instances are related to people, are subpopulations identified (e.g., by age, gender, etc.) and what is their distribution?

Structured metadata (not raw data). Includes trial ID, title, status, conditions, interventions, sponsor, locations, dates, participant demographics (age, gender), and links to full records.


Is everything included or does the data rely on external resources? (e.g., websites, tweets, datasets) If external resources, a) are there guarantees that they will exist, and
remain constant, over time; b) is there an official archival version. Are there licenses, fees or rights associated with any of the data?

The data is mostly self-contained in the CSV file (trial metadata). However, it relies on external resources for two key elements:

Full Record & Updates: The URL field for each trial links to the live, updated record on ClinicalTrials.gov.

Study Documents: The Study Documents field (e.g., in row 20, 71) contains links to external PDFs like protocols and statistical analysis plans.

Are there recommended data splits or evaluation measures? (e.g., training, development, testing; accuracy/AUC)

No. This is not a benchmark dataset for machine learning. It is a descriptive, real-world registry dataset.


What experiments were initially run on this dataset? Have a summary of those results and, if available, provide the link to a paper with more information here.

This specific CSV file is a snapshot created for analysis or sharing. Therefore, no "initial experiments" were run on this exact file as if it were a released benchmark.

Is the preprocessing software available?

There is no specific "preprocessing software" for this snapshot.


Does this dataset collection/processing procedure achieve the motivation for creating the dataset stated in the first section of this datasheet?

Achieves the Motivation:
The dataset successfully fulfills its core purpose of providing transparency. It allows anyone to see:

What COVID-19 trials were registered.

Who is sponsoring them.

Where they are being conducted.

Their design (intervention, endpoints).

Their current status (Recruiting, Completed, etc.).

Any other comments?

_________________________________________________________________________________________________________________________________________________________
## Data Collection Process:

How was the data collected? (e.g., hardware apparatus/sensor, manual human curation, software program, software interface/API; how were these constructs/measures/methods validated?)

Data was collected via manual human entry into a structured web-based software program—the ClinicalTrials.gov Protocol Registration and Results System (PRS). The PRS includes automated validation rules (e.g., required fields, date formats, controlled vocabularies for Study Type and Phases). 

Who was involved in the data collection process? (e.g.,students, crowdworkers) How were they compensated? (e.g., how much were crowdworkers paid?)

The data was entered by authorized representatives of the clinical trial sponsors or principal investigators. These individuals were not paid for the act of data entry itself

Over what time-frame was the data collected? Does the collection time-frame match the creation time-frame?

The data for each trial was entered and updated sporadically over the lifetime of that trial, from its initial registration. This specific CSV file is a point-in-time snapshot extracted at a single moment. The collection is an ongoing process for each trial.

How was the data associated with each instance acquired? Was the data directly observable (e.g., raw text, movie ratings), reported by subjects (e.g., survey responses), or indirectly inferred/derived from other data (e.g., part of speech tags; model-based guesses for age or language)? If the latter two, were they validated/verified and if so how?

The data is reported by subjects—specifically, by the trial organizers (sponsors/investigators). As noted, validation occurs at the point of entry (formatting, required fields). NLM staff perform QC on select fields

Does the dataset contain all possible instances? Or is it, for instance, a sample (not necessarily random) from a larger set of instances?

No. This dataset is a sample from a larger universe.

If the dataset is a sample, then what is the population? What was the sampling strategy (e.g., deterministic, probabilistic with specific sampling probabilities)? Is the sample representative of the larger set (e.g., geographic coverage)? If not, why not (e.g., to cover a more diverse range of instances)? How does this affect possible uses?
All clinical trials conducted worldwide that involve human participants and are related to COVID-19/SARS-CoV-2.
Sampling Strategy: Deterministic, but incomplete.
includes all trials registered on ClinicalTrials.gov that matched the search criteria for COVID-19 at the time of export.
Representativeness: The sample is not fully representative of the global population of COVID-19 trials.
Effect on Use: Analyses of geographic distribution, sponsor networks, and intervention types will be skewed. 


Is there information missing from the dataset and why? (this does not include intentionally dropped instances; it might include, e.g., redacted text, withheld documents) Is this data missing because it was unavailable? 

Yes, significantly.

Study Results: The Study Results column is overwhelmingly "No Results Available." This is the most critical missing information.


Are there any known errors, sources of noise, or redundancies in the data?

Human Entry Errors: Typos, inconsistent terminology (e.g., "Covid19" vs. "COVID-19"), and misclassification in free-text fields.

Outdated Information: Trial Status or Completion Date may be outdated if sponsors fail to update the record.


Any other comments?
_________________________________________________________________________________________________________________________________________________________
## Dataset Distribution 
How is the dataset distributed? (e.g., website, API, etc.; does the data have a DOI; is it archived redundantly?)



When will the dataset be released/first distributed? (Is there a canonical paper/reference for this dataset?)



What license (if any) is it distributed under? Are there any copyrights on the data?


Are there any fees or access/export restrictions?

_________________________________________________________________________________________________________________________________________________________
## Data Preprocessing:

What preprocessing/cleaning was done? (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, etc.)

Was the “raw” data saved in addition to the preprocessed/cleaned data? (e.g., to support unanticipated future uses)

_________________________________________________________________________________________________________________________________________________________
## Dataset Maintenance:

Who is supporting/hosting/maintaining the dataset? How does one contact the owner/curator/manager of the dataset (e.g. email address, or other contact info)?


Will the dataset be updated? How often and by whom? How will updates/revisions be documented and communicated (e.g., mailing list, GitHub)? Is there an erratum?


If the dataset becomes obsolete how will this be communicated?

Is there a repository to link to any/all papers/systems
that use this dataset?

If others want to extend/augment/build on this dataset, is there a mechanism for them to do so? If so, is there a process for tracking/assessing the quality of those contributions. What is the process for communicating/distributing these contributions to users?


Any other comments?
_________________________________________________________________________________________________________________________________________________________
## Exploratory Data Analysis

Show a few plots or some data tables that help your reader understand your data better. What are some initial questions that you were able to quickly answer? How do those questions lead you to a deeper analysis?

_________________________________________________________________________________________________________________________________________________________
## Proposed Questions - Legal and Ethical Considerations 

What specific questions are you going to explore and present in the rest of the paper? Give a very brief overview of what you are going to do to answer those questions. Imagine this as a road map so your reader knows what to expect. If the dataset relates to people (e.g., their attributes) or
was generated by people, were they informed about the data collection? (e.g., datasets that collect writing, photos, interactions, transactions, etc.)


If it relates to other ethically protected subjects, have appropriate obligations been met? (e.g., medical data might include information collected from animals)


If it relates to people, were there any ethical review applications/reviews/approvals? (e.g. Institutional Review Board applications)


If it relates to people, were they told what the dataset would be used for and did they consent? What community norms exist for data collected from human communications? If consent was obtained, how? Were the people provided with any mechanism to revoke their consent in the future or for certain uses?


If it relates to people, could this dataset expose people to harm or legal action? (e.g., financial social or otherwise) What was done to mitigate or reduce the potential for harm? 

If it relates to people, does it unfairly advantage or disadvantage a particular social group? In what ways? How was this mitigated? 

If it relates to people, were they provided with privacy guarantees? If so, what guarantees and how are these ensured?

Does the dataset comply with the EU General Data Protection Regulation (GDPR)? Does it comply with any other standards, such as the US Equal Employment Opportunity Act?

Does the dataset contain information that might be considered sensitive or confidential? (e.g., personally identifying information)


Does the dataset contain information that might be considered inappropriate or offensive?

Any other comments?
_________________________________________________________________________________________________________________________________________________________
## Analysis and Results

Here is where you show your code and results (plots, tables, predictions, etc) that help to explore and answer your questions. There should be code here that can be run to reproduce your results and conclusions. After each plot/table/final number, you should add a Markdown cell where you explain to the reader what the result means and how/why it answers the question.

_________________________________________________________________________________________________________________________________________________________

## Conclusion

Give a brief statement about what you achieved in your analysis, what issues or limitations your analysis contains, and some possible future directions (if you had more time an money to keep going).
