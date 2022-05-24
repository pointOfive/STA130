

# STA130 (Fall 2022): An Introduction to Statistical Reasoning and Data Science

This course transitions the [W22 Online](https://q.utoronto.ca/courses/253019) version of this course to an in-person course by translating previous powerpoint slides and accompanying pre-recorded lectures into an Rmd beamer pdf presentation format (which is the format required for student project submissions). The course objectives are to develop and practice the two steps the statistical and data science workflow:

1. Extract meaning from data through coding and analysis
2. Communicate learned knowledge in writing and speaking


## Weekly Course Routine

- 2 hours of in-person lecture and interactive class practice quizzes

  > 3 hours of "completion credit" R homework (10%) designed to develop and practice the skills evaluated on the exams (40%) and the course project (25%)
  
- 1 hour of in-person tutorial activities (15%) focussing on written and verbal comminication

  > 2 hours of written and verbal communication homework (10%) designed to develop and practice the skills evaluated on the exams and the course project

- 2 hours of study time

  > For course review, office hours, piazza discussion board 

## Course Grading

| | |
|-|-|
| 10% R homework | 10% written and verbal communication homework |
| 15% tutorial communication activies | 25% Course project |
| 20% Midterm exam | 20% Final exam |


Tutorial attendance is mandatory in the sense that it involves graded in-person activies. 
Lecture attendance is mandatory in the sense that lectures will not be recorded, but there are no addendance grades for lectures.
Practice quizzes and other study materials to help prefar for the exams (40%) are available, but these are optional in the sense that they are not graded for course points.

## Misses Assessments

- Missed Exams may be rescheduled for valid excused absences
- Late Project submission will not generally be accomodated
- Let Homework and Tutorial work will not be accepted; however...
  - the highest grade will replace the lowest for each of these categories
  - For additional support contact your [College Registrar](https://www.artsci.utoronto.ca/current/academic-advising-and-support/college-registrars-offices)

## Communication

- Online Piazza Discussion Board
- Online Zoom Office Hours TBA
- In-person Office Hours TBA
- Special inquiries sta130@utorono.ca

## Course project

The course project will be done in consultation with our "project collaborator" [Dr. Heman Shakeri](https://datascience.virginia.edu/people/heman-shakeri) of the [University of Virginia's](https://www.virginia.edu/) (UVA) [Data Science Institute](https://datascience.virginia.edu/) (DSI). The DSI is a recently created [School](https://datascience.virginia.edu/pages/uva-plans-new-school-data-science) (the 12th) of this [premier](https://www.usnews.com/best-colleges/uva-6968/overall-rankings) US university originally founded by [Thomas Jefferson](https://www.virginia.edu/aboutuva) the [principal author](https://en.wikipedia.org/wiki/Thomas_Jefferson) of the US [Declaration of Independence](https://en.wikipedia.org/wiki/United_States_Declaration_of_Independence).

Dr. Shakeri's research, in conjuction with the [Department of Biomedical Engineering](https://engineering.virginia.edu/departments/biomedical-engineering) and 
[Systems Biology and Biomedical Data Sciences](https://engineering.virginia.edu/departments/biomedical-engineering/research/systems-biology-and-biomedical-data-sciences),
is motivated by the experience with cancer of a close family friend. So, Heman (Dr. Shakeri) wants to use "data-driven identification and control of high-dimensional dynamical systems" to detect deviations away from normal cellular function and intervene to interrupt the pregression of cancer before it can establish a deleterious cellular homeostasis in order to  give family's more time with their loved ones and close friends.

The data we will work with is based on advances in the fields of [Flow Cytometry](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5939936/) for single cell analysis and [Mass Spectrometry](https://www.broadinstitute.org/technology-areas/what-mass-spectrometry) for measurement of cellular proteomic processes (the [phenotypical process endpoint](https://en.wikipedia.org/wiki/Central_dogma_of_molecular_biology) of cellular function and behavior). Based on these technologies, the multivariate landscape of proteomic activity can be measured for a single cell in any experiemental condition for any cell type (e.g., cancerous and benign cellular lines) at scale. By understanding typical cellular homeostatis of healthy and deliterious cells, and observing the phenotypical transformation of cellular proteomic homeostatsis over time in response to different treatments, it is hoped that we will eventually understand how to direct deleterious cellular states to transition into non-deleterious states. I.e., "data-driven identification and control of high-dimensional dynamical systems".

The data observations simultaneously measure 17 so-called [AP-1 transcription factors](https://en.wikipedia.org/wiki/AP-1_transcription_factor) over thousands of cells in a given experiemental condition. By repeatedly observing this protein complex (as is done in this data), the correlation between the different proteins can be observed. Further, the evolution of these dependencies can be observed over time as a response to different interventions. And even further, the emergence of downstream cellular phenotypes in response to changes of the state of the AP-1 system can also be observed and can be characterized through 4 other "phenotype" proteins (whose measurements are also available in this data set). Thus, though our course project, we seek to understand the inter-dependence between the AP-1 proteins, and their driving relationship with downstream cellular phenotypes, which might eventually suggest how we can intervene along this pathway to induce transformation away from deletarious cellular states. 


## Outline

### Week 1: Jupyterhub and Rstudio and R Basics

Week 1 is concerned with introducing students to R and [Rstudio](https://www.rstudio.com/) using [UofT's Jupyterhub](https://jupyter.utoronto.ca). Our primary reference resources in this task are

- the [R for Data Science](https://r4ds.had.co.nz/) textbook by Hadley Wickham & Garret Grolemund
- the [DoSS Toolkit](https://dosstoolkit.com/) created by seasoned STA130 Profs. Alexander and Caetano among many, many others
- and Rstudio [primers](https://rstudio.cloud/learn/primers) and [cheatsheets](https://www.rstudio.com/resources/cheatsheets/)

In particular, the resources from these references which will help you getting started in week 1 are 
[https://r4ds.had.co.nz/workflow-basics.html](R4DSch4), [Programming Basics](https://rstudio.cloud/learn/primers/1.2),
and the modules on [Rstudio](https://dosstoolkit.com/#hello-world), [errors](https://dosstoolkit.com/#operating-in-an-error-prone-world),
and [packages](https://dosstoolkit.com/#holding-the-chaos-at-bay) from the [DoSS Toolkit](https://dosstoolkit.com/)
for those [https://dosstoolkit.com/#if-you-have-never-used-r-before](new to R and Rstudio).

> The [UofT Jupyterhub](https://jupyter.utoronto.ca) is a phenomenal resource; however, it is subject to service outages from time to time (which have in the past coincided with assignment due dates), and it can take a long time to load when there's a lot of simultaneous user demand (if a lot of students in our or another class log in at once). When you cannot use [UofT Jupyterhub](https://jupyter.utoronto.ca) you must use your own [local Rstudio instance](https://www.rstudio.com/).

> An extremely valuable skill in the context of coding for statistics and Data Science is troubleshooting and figuring things out.  Resources like the [R for Data Science](https://r4ds.had.co.nz/) textbook and the the [DoSS Toolkit](https://dosstoolkit.com/) are excellent recources to learn things in a systematic, structured, and organized manner; however, google, stack exchange/overflow, and coding blog posts can be an invaluable resource for finding quick solutions for coding bugs and suggestions for how to complete a desired analyses. Hopefully through this class you will take the opportunity to build your self-sufficiency and coding-resiliance.

The content for week 1 includes

- [In-class Slides](https://github.com/pointOfive/STA130_Week1_Slides) [view on Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week1_Slides&urlpath=rstudio%2F&branch=main)
- [In-class Demo 1](https://github.com/pointOfive/STA130_Week1_Demo1) [view Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week1_Demo1&urlpath=rstudio%2F&branch=main) and
- [In-class Demo 2](https://github.com/pointOfive/STA130_Week1_Demo2) [view Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week1_Demo2&urlpath=rstudio%2F&branch=main).
- [In-class questions](https://pollev.com/sta) [[Round 1](https://PollEv.com/surveys/Sn8Y5ZdhDdocnPBg5lWU3/respond), [Round 2](https://PollEv.com/surveys/ZajOSOpWDmepur3hTlXKV/respond), [Round 3](https://PollEv.com/surveys/ytOu9cYQoL6Oyon1dmUWr/respond), [Round 4](https://PollEv.com/surveys/5gpW9MIWgzTuE81nEJDaH/respond), [Round 5](https://PollEv.com/surveys/k46QXuZy1j1a9kuXy4eY0/respond)]
- [Practice quiz](https://q.utoronto.ca/courses/253019/quizzes/236277/edit)
- [Homework assignment](https://github.com/SamanthaJoCaetano/STA130-W22-ProblemSet1)



#### Module 1 material

- Everything: https://q.utoronto.ca/courses/253019/pages/m1-outcomes-and-activities?module_item_id=3320925


## Module 2: Distributions and Statistics

## Module 3: Data Wrangling with Tidy

## Module 4: Statistical Inference for a Single Sample Proportion

## Module 5: Permutation Tests for Two Groups

## Midterm Review

## Module 6: Sampling Distributions and Bootstrap Confidence Intervals

## Module 7: Linear Regression I

## Module 8: Linear Regression II

## Module 9: Classification Trees

## Module 10: Study Design, Confounding, and Ethics

## Final Review
