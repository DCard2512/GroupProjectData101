# Title: Datasheets & Clinical Trials 

#### By: Diego Cardenas & Kiran Treacy

## Abstract: Here you type a 3-4 sentence summary of your final project.

In this final project, we analyze the COVID-19 Clinical Trials dataset using the Microsoft Datasheets for Datasets framework. This approach will provide a structured method for evaluating how the dataset was collected, processed, and documented. By using these datasheet items, we show how to properly analyze real-world data while also identifying the ethical considerations, limitations, and potential risks associated with its use. This project highlights the importance of transparency, responsible data handling, and ethical reasoning in data science.
_________________________________________________________________________________________________________________________________________________________
## Introduction and Background: Convince your audience that the rest of the project is worth learning about. What interesting problem are you exploring? Why should EVERYONE be interested in your analysis?

The COVID-19 pandemic was one of the most global scientific efforts ever. Researchers around the world conducted many clinical trials to test vaccines and treatments. These trials produced an enormous amount of data. Which most of it became publicly accessible. So, we can analyze this COVID-19 trial data such as how the data was collected? How it was processed? And whether it can be responsibly used.

We are exploring the COVID-19 Clinical Trials dataset using the items of Microsoft Datasheets for Datasets framework. We are looking for the dataset’s origins, limits, ethical concerns, and potential biases. This is important because companies will use datasheet items to analyze datasets like these especially human subjects, often containing hidden issues that can affect the accuracy and fairness of the conclusions made. 

Everyone should be interested in this analysis because COVID-19 impacted everyone in the world. So checking this dataset's reliablability, fairness, and accuracy will make sure that we can depend on the items in the datasheet so that the data in the dataset that anyone can have access to is reliable. 
_________________________________________________________________________________________________________________________________________________________
## Data Colleciton Considerations Using the Microsft Datasheet Format: 

First, we need to ask what is the motivation for the dataset creation? So we ask...

Why was the dataset created? (e.g., were there specific tasks in mind, or a specific gap that needed to be filled?)

The dataset was created to provide a list of COVID-19 related clinical trials conducted globally. The intended purpose appears to be exploratory data analysis, trend visualization, and educational use on Kaggle.

What other tasks could the dataset be used for? Are there obvious tasks for which it should not be used?
Trial landscape & meta-research: descriptive statistics and visualizations of numbers of trials by phase, intervention type, sponsor type, geographic location, and time (e.g., monthly new registrations). 
Kaggle

NLP / information extraction: build models to extract structured fields from trial XML (e.g., interventions, eligibility criteria, outcomes), to standardize intervention names, or to create ontologies/term mappings. 



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
