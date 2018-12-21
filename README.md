# Project-Write-A-Data-Science-Blog-Post

## Project Introduction
---
In this project, I will creating a jupyter notebook, blog post and Github repository to start building my data science portfolio. This data science process focus on the `Stack Overflow data - 2017 survey data`. The analysis will be completed by using CRISP-DM (Cross Industry Process for Data Mining), as presented at below.

1. Business Understanding
2. Data Understanding
3. Prepare Data
4. Data Modeling
5. Evaluate the Results
6. Deploy

## Installation
---
The following python tools/module packages is needed for this study.
- python 3.6
- anaconda
- jupyter notebook
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

## Motivation/Object of project
---
In order to answering the following business understanding question below, we will preform data science process on Stackoverflow survey data (in 2017) to get some insight into each of these questions. Below presents the column needed for analysis/modelling prediction of each questions:

1. Is Python the most used programming language in 2017?
    - HaveWorkedLanguage
2. What are the employment status and enjoyability (ProgramHobby) of those who have programming skillsets?
    - EmploymentStatus, ProgramHobby
3. How well can we predict an individual's enjoyability (ProgramHobby)? What aspects correlate well to enjoyability (ProgramHobby)?
    - All columns

## Files Uploaded in Repository
---

The following are all file/data that needed for this project.

1. Jupyter Notebook (project_04_write_ds_blog_post.ipynb) -  codings for each steps of CRISP-DM (Cross Industry Process for Data Mining)
2. Stack Overflow data - 2017 survey data (survey_results_public.csv) -  raw data for the data analysis and modelling
3. Raw Data Description (survey_results_schema.csv) - the description/questions of all features/columns of raw data

`Note:` Due to large file size, please download Stack Overflow data - 2017 survey data at https://insights.stackoverflow.com/survey

 ## Summary of the results of analysis
---

In this analysis, we found the following answers for the respective business questions:
1. Answer for Question 1 - Java is the most used programming language in 2017
2. Answer for Question 2 - The proportion of Employed full-time is higher than another employment status if the person who have programming language skillsets. Besides that, a majority of programmer enjoy their programming works, especially program as hobby, followed by program for both (hobby & contribute to open source prohjects) and program to contribute to open source projects only.
3. Answer for Question 3 - Random Forest Model with 0.84 of accurancy score and 0.91 of F1 score had been setup. In addition, Employment status appears to be one of the top indicators for an individual enjoyability. Professional Status and Formal Education are another important indicators for the enjoyability of programmer.

For more information about this project, you also refer to my Medium at [here](https://medium.com/@leehongchen/what-is-the-most-used-programming-language-in-2017-d3f5840b9f63)

 ## Acknowledgement
---
I couldn’t have finish this project without the help of a lot of people. I’d like to thank the Udacity instructors and the rest of the Udacity staff for their invaluable help. Thanks to my project mentors, for great suggestions, edits, and support.


