# ANLP-2023

## Feedback on the paper
Points were deducted mostly due to:

- failing to follow the project guidelines
- missing sections in the paper structure (as per section 6.1 in the project guidelines)
- incomplete sections (e.g. no examples in the data section, no baseline in the experiments, no error analysis in the results)
- inadequate task formalization
- low quality in writing (too many spelling mistakes, leftover comments to self, too many claims without evidence, informal tone)
- submission of clearly unfinished work
- When submission guidelines are put forward, please follow them closely. Things like number of pages, citation format, template, figure and table layout, paper structure are very important for - - the reviewers/readers (that's why we created guidelines in the first place).

Here are some further general feedback on the papers. Not everything impacted grades, this is meant as recommendations for writing better papers in general.

## General Comments
- Use scientific, formal language, with a coherent flow. Proofread your text.
- Do not submit unfinished work. Plan enough time for projects (and for writing!).
- Avoid making claims that are only based on your assumptions and perceptions. Everything should be backed up by a citation, by the data/results, or by other forms of concrete evidence or argumentation.
- Follow citation standards. In NLP literature, the default is: SurnameA and SurnameB (YEAR) if it is a part of the sentence, or (Surname, YEAR) when it is used to reference where the claim comes from. It is not necessary to mention the title of a paper or the first names of the authors in the text.
- Avoid strange passive constructions. It's totally fine to use 1st person (I or we).
- Use the right symbol for opening quotation marks in LaTeX.
- Avoid vertical lines in tables. Also avoid horizontal lines except at the top, bottom, and after the header. Exceptions to this are only when we need to split blocks for some reason. You can check the APA table layout guidelines.
- Figure size should be appropriate to the document. Figures that are too small or too large are not helpful.
- Make sure that the font sizes in figures are readable. Figures should be readable for colourblind people, and preferably in grey version too. Ideally, do not rely on colour only to make a distinction (use marker format, line style etc instead or additionally).
- Include a caption in every figure and table. It should be self-contained.
- Always refer to every figure and table at least once in the text.
## Title and abstract
- Titles should be informative, containing all relevant keywords.
- Abstracts are a full summary of the work: It must mention the motivation, the research question, the approach, and also the main takeaways.
## Introduction
- Should include the motivation/background, the research question, the approach, the contributions.
- In this project, the SemEval task should be put in evidence and cited.
- Avoid boilerplate texts that do not add much in content. For example, starting the introduction with "NLP models have been showing impressive results in the latest year".
## Related Work
- Do not just add short summaries of papers one after the other.
- This section should tell a story about how the work fits into its context.
- What are the limitations of existing works? How does the work relate to existing work and tries to overcome the known limitations?
## Task Formalisation
- This was the section with most issues. Here, you should formalise the task, in abstract form, using mathematical notation.
- We had a full session on this and the slides with plenty of examples are available on Moodle (week 7).
- Just describing what is the data, model etc. is not enough.
- This also does not relate to describing how the model is trained or evaluated.
## Data
- Always add examples and include basic descriptive statistics, as well as any important preprocessing steps.
- Even if using existing datasets, include the main information that the reader needs to understand the work without having to go to the original publication.
- Publicly available is not always public domain.
## Experiments
- It's always a good idea to add an illustration of the model architecture.
- The evaluation methods and metrics should be presented before the results section so that, when we get there, we already know what to expect.
- The implementation should be discussed in a high level overview.
- Function names, for example, are not necessary here.
- Other very specific details belong to the code documentation and, if applicable, the appendix.
## Results
- Do not use the word "significant" when referring to results, unless you have run statistical significance tests.
- Preferably, disentangle reporting results from interpreting them.
- The error analysis in NLP should discuss the evaluation taking into account the linguistic aspects of the inputs and outputs, focusing on the cases where the model fails.
- By default, one table with the main results and a few plots for additional analysis are expected in this section. Reporting numbers sparsely over the text hinders the comparison of results.
## Conclusion
This is a recap on what was done and a wrap-up, summarising the main takeaways and possible further research.
## Limitations and Ethics
- Avoid generic text that adds no value.
- Be clear about what you know that could have been done in other ways and explain why you did not do it.
- Think critically about the consequences of your work (even if only potential) in reality.
## References
- Make sure that the references are complete.
- Sometimes, the .bib entry has missing information that is important and needs to be added manually.
- Before citing arXiv papers, first check if they have been published somewhere.
- Published work must be cited as such, not as preprints.
