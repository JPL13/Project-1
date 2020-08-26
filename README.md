### Table of Contents

1. [Installation](#installation)
2. [File Descriptions](#files)
3. [Project Motivation](#motivation)
4. [Overview](#overview)
5. [Methodology](#methods)
6. [Summary](#summery)
7. [Publication](#results)
8. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code was written with Python 3. There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  

## File Descriptions <a name="files"></a>

There is 1 notebook available here to showcase work related to the above questions. Markdown cells were used to assist in walking through the thought process for individual steps.  

## Project Motivation<a name="motivation"></a>

In this analysis, I looked at responses from the three most recent Stack Overflow Developer Surveys to find some insights about
Data Scientists, Data Engineers, Data Analysts and Software Developers:

1. What are the trends in the job market? Are data-related jobs rapidly increasing? 
2. Is there any difference between the four professions in terms of salary?
3. What about job satisfaction? How many respondents want to leave their current job? Which factors are most important when choosing a new job? 
4. What languages and databases are used most for each role?


## Overview <a name="overview"></a>

### Question 1: What are the trends in the job market? Are data-related jobs rapidly increasing?
How did the proportion of each developer role change in recent years?

### Question 2. Is there any difference between the four professions in terms of salary?
Do data-related roles earn more than software developers?
Are the salaries for the software developers and data-related roles increasing?

### Question 3. What about job satisfaction? How many respondents want to leave their current job? Which factors are most important when choosing a new job? 
How satisfied are they?
How many want to leave their current job?
Which factors are most important when choosing a new job?

### Question 4. What languages and databases are used most for each role?
Are there differences between data-related roles and software engineers in terms of the technical tools they use?

## Methodology <a name="methods"></a>

- For Question 1, the most recent 3 years of data about the proportion of each developer role are computed.

- For rest of the questions, Data Scientist, Data Analyst, Data Engineer and Software Developer was selected to illustrate the differences among different developer roles, although more developer roles were available in the dataset. For this analysis, Software Developer refers to the group of developers that have ‘Developer’ in the job title, which includes Back-End, Full-Stack, Front-end, Mobile, Desktop Applications, QA or Test, Embedded Devices and Game or Graphics devices Developer. 

- For Question 2, for 2019 and 2020, I used the column 'ConvertedComp' as salary, which is the Salary converted to annual USD salaries using the exchange rate on 2019-02-01, assuming 12 working months and 50 working weeks. I removed columns with NaNs in the 'ConvertedComp' column.
  For 2018, I used the column 'ConvertedSalary'  as salary, which is the Salary converted to annual USD salaries using the exchange rate on 2018-01-18, assuming 12 working months and 50 working weeks. I removed columns with NaNs in the 'ConvertedSalary' column.

- For Question 3, I compared the job satisfaction ratio among Data Scientist, Data Analyst, Data Engineer and Software Developer.
 I also compared the ratio of respondents who are actively looking for new job among Data Scientist, Data Analyst, Data Engineer and Software Developer.
 I compared the important factors when choosing new job among Data Scientist, Data Analyst, Data Engineer and Software Developer.

- For Question 4, I compared the most-used programming languages and databases among Data Scientist, Data Analyst, Data Engineer and Software Developer.


## Summary <a name="summary"></a>

### Conclusion:
In this analysis, I looked at responses from the three most recent Stack Overflow Developer Surveys to find the proportion of people who work at Data Scientist, Data Engineer, Data Analyst, and Software Developer jobs and compared their salaries, job satisfaction, job seeking status, and the technical tools they use.
My main takeaways are the following:

-“Classic” Software Developer roles outnumber data-related roles. Certain Software Developer roles have been steadily increasing over the past three years, but the numbers for Data Scientists, Data Engineers and Data Analysts didn’t have a major change.
-The salaries for Data Scientists, Data Engineers, Data Analysts, and Software Developers have been increasing over the past three years in the US. The highest paying job in the US is Data Scientist and Data Engineer, followed by Software Developer and Data Analyst. Developers in the US are paid more than their counterparts in other countries.
-Data Scientists, Data Engineers, Data Analysts, and Software Developers are all generally happy at their jobs with Data Scientists having the highest satisfaction rate. Among these professionals, around 20% are actively looking for new jobs. For Software Developers and Data Engineers, technologies they would be working with is the main factor when choosing a new job. For others, “Opportunities for professional development” is the most important factor.
-The most used language for Software Developers and Data Engineers is Java. For Data Scientists it is Python, and for Data Analysts it is SQL. C is a close second for all four groups. In terms of databases, MySQL, PostgreSQL, Microsoft SQL server, and SQLite are the top 4 among all groups.

## Publication <a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@xiaoruyue1986/how-do-you-choose-software-engineer-data-scientist-data-engineer-or-data-analyst-1cc5ec47dff2?sk=23fb99241839aa8a31f6fcfe1f3b169c).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit : Stack Overflow for the data.  You can find the data [here](https://insights.stackoverflow.com/survey). 


