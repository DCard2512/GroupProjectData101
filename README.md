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

The dataset was created by the government to gather information about all the clinical trials



What (other) tasks could the dataset be used for? Are
there obvious tasks for which it should not be used?

The dataset can help paint a picture for the purpose with the different trails and even with where these trials are being done and who is funding them.


Has the dataset been used for any tasks already? If so,
where are the results so others can compare (e.g., links to
published papers)?

We have not found any published papers using this datasets but on Kaggle it has given many people the opportunity to look at the datasets like us as notebooks and projects.



Who funded the creation of the dataset? If there is an
associated grant, provide the grant number.

In this dataset, we know the data was obtained by US government in ClinicalTrials.gov, but we can see there are 3 different types of fundings in the dataset and this creates a question of why some have more funding and what may be the reasoning behind it. 



Any other comments? 
_________________________________________________________________________________________________________________________________________________________
## Dataset's Compostition:

What are the instances? (that is, examples; e.g., documents, images, people, countries) Are there multiple types of instances? (e.g., movies, users, ratings; people, interactions between them; nodes, edges)

Instances would be the different trials that are on each row. The instances are all formated the same.



Are relationships between instances made explicit in the data (e.g., social network links, user/movie ratings, etc.)?

The relationships between instances are not made explicit with our data since each instance is all unique with each other as the trials are all their own.


How many instances of each type are there?
There are all unique instances and are no types of instances


What data does each instance consist of? “Raw” data (e.g., unprocessed text or images)? Features/attributes?  Is there a label/target associated with instances? If the instances are related to people, are subpopulations identified (e.g., by age, gender, etc.) and what is their distribution?

Each instance 


Is everything included or does the data rely on external resources? (e.g., websites, tweets, datasets) If external resources, a) are there guarantees that they will exist, and
remain constant, over time; b) is there an official archival version. Are there licenses, fees or rights associated with any of the data?


Are there recommended data splits or evaluation measures? (e.g., training, development, testing; accuracy/AUC)

What experiments were initially run on this dataset? Have a summary of those results and, if available, provide the link to a paper with more information here.

Is the preprocessing software available?

Does this dataset collection/processing procedure achieve the motivation for creating the dataset stated in the first section of this datasheet?

Any other comments?

_________________________________________________________________________________________________________________________________________________________
## Data Collection Process:

How was the data collected? (e.g., hardware apparatus/sensor, manual human curation, software program, software interface/API; how were these constructs/measures/methods validated?)

The data was collected by Kaggle that brought in clinical trials from  ClinicalTrials.gov which the government has many different trials from all around the world. Sponsors and Investigators are the ones to upload their data into this database.

Who was involved in the data collection process? (e.g.,students, crowdworkers) How were they compensated? (e.g., how much were crowdworkers paid?)

The data is unknown by who exactly is invovled in getting the data individually but majority of the data is coming from hospitals and some from schools around the world.

Over what time-frame was the data collected? Does the collection time-frame match the creation time-frame?

The data was obtained between 2020 and 2021


How was the data associated with each instance acquired? Was the data directly observable (e.g., raw text, movie ratings), reported by subjects (e.g., survey responses), or indirectly inferred/derived from other data (e.g., part of speech tags; model-based guesses for age or language)? If the latter two, were they validated/verified and if so how?

The two types of ways that the data was obtained was through either observational and interventional from the different trials. We can see from the graph below that the majority of how they data was obtained of the clinicals 


Does the dataset contain all possible instances? Or is it, for instance, a sample (not necessarily random) from a larger set of instances?

No, this dataset does not contain all possible instances but more of a sample as it gets a portion of data of clinical trials but does not get all the data from the world



If the dataset is a sample, then what is the population? What was the sampling strategy (e.g., deterministic, probabilistic with specific sampling probabilities)? Is the sample representative of the larger set (e.g., geographic coverage)? If not, why not (e.g., to cover a more diverse range of instances)? How does this affect possible uses?

We would think that it is more of a diverse range of instances because the data seems to randomly be picked from the ClinicalTrials.gov which data is uploaded by the sponsors and investigators.




Is there information missing from the dataset and why? (this does not include intentionally dropped instances; it might include, e.g., redacted text, withheld documents) Is this data missing because it was unavailable? 

Yes, there is some data that is missing such as the phase the trials are in, to end date as majority have not finished with their trials, and the type of interventions that the trials have went through.



Are there any known errors, sources of noise, or redundancies in the data?
I think the some of the noise that we can see is the use of different types of names for Covid as they can be Cov19,Covid-19,and SARS-COV-2. Data missing as said before is part of it which causes a redundancies. 


Any other comments?
_________________________________________________________________________________________________________________________________________________________
## Dataset Distribution 
How is the dataset distributed? (e.g., website, API, etc.; does the data have a DOI; is it archived redundantly?)

The dataset is distributed by Kaggle which they brought in all different clinical trials to just one dataset.



When will the dataset be released/first distributed? (Is there a canonical paper/reference for this dataset?)

The dataset is unknown by when it was first uploaded to kaggle but we know the last update to it was in April of 2021




What license (if any) is it distributed under? Are there any copyrights on the data?

There is no copyright on this data since in kaggle it is a public database of different datasets for the public and the US gov has another database of individual clinical trials for public use.



Are there any fees or access/export restrictions?
No there are no fees to access since its a public source ot use.
_________________________________________________________________________________________________________________________________________________________
## Data Preprocessing:

What preprocessing/cleaning was done? (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, etc.)

We had dialed down to focus on cleaning the data a bit with making sure things like the names of the conditions are all one name of covid with the different versions of the name, funded by is put into 3 categories. But thats the most we had to do.



Was the “raw” data saved in addition to the preprocessed/cleaned data? (e.g., to support unanticipated future uses)

THe data was somewhat clean and not much and seems as the data seems to be used in the future.

_________________________________________________________________________________________________________________________________________________________
## Dataset Maintenance:

Who is supporting/hosting/maintaining the dataset? How does one contact the owner/curator/manager of the dataset (e.g. email address, or other contact info)?

The dataset is maintained by users of kaggle, but the data has not been updated in 5 years after being said that the data would be updated weekly.



Will the dataset be updated? How often and by whom? How will updates/revisions be documented and communicated (e.g., mailing list, GitHub)? Is there an erratum?
As said before, it was stated by the users that the dataset would be updated weekly but the last update has been 5 years ago no.



If the dataset becomes obsolete how will this be communicated?
We are unsure how we would know when the dataset will be obsolete so communication is not much



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
We would assume that most of the subjects is ethical and since its data provided by the US government then we can assume that the data was obtaine din an ethical way since government policies can be strict for the protection of the individual


If it relates to people, were there any ethical review applications/reviews/approvals? (e.g. Institutional Review Board applications)



If it relates to people, were they told what the dataset would be used for and did they consent? What community norms exist for data collected from human communications? If consent was obtained, how? Were the people provided with any mechanism to revoke their consent in the future or for certain uses?

We are not sure if people have given permission but using Microsoft Datasheet to see and has stated



If it relates to people, could this dataset expose people to harm or legal action? (e.g., financial social or otherwise) What was done to mitigate or reduce the potential for harm? 
I believe that 


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
