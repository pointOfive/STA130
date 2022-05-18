

# STA130 (Fall 2022): An Introduction to Statistical Reasoning and Data Science

This course transitions the [W22 Online](https://q.utoronto.ca/courses/253019) version of this course to an in-person course by directly translating previous powerpoint slides and accompanying pre-recorded lectures into the ".Rmd presentation" format used for student project submissions. The translation is faithful to the original material while also attempting to streamline and increase precision of scope limitations and learning targets. Adjustments are merely the natural product of the review and organizational process of transitioning the notes and do not entail critical criques of the original material on which they are based.

## The weekly routine of the course consists of
- 2 hours of in-person lecture
  - 1 hour of "completion credit" quizzes designed to reinforce course learning objectives
- 1 hour of tutorial, which a focus on written and verbal comminication

  > a key skill of the statistician and data scientist
  
  - 2 hours of written and verbal communication homework primarily associated with the tutorial 

  
- 4 hours of "completion credit" R homework

  > designed to develop and practice the skills evaluated exams and the course project

## The course grade is consists of
- 15% R homework
- 15% Communication tutorial work/homework
- 5% Practice quizzes
- 20% Midterm exam
- 20% Final exam
- 25% Course project

## Course project

The course project will be done in consultation with our "project collaborator" [Dr. Heman Shakeri](https://datascience.virginia.edu/people/heman-shakeri) of the [University of Virginia's](https://www.virginia.edu/) (UVA) [Data Science Institute](https://datascience.virginia.edu/) (DSI). The DSI is a recently created [School](https://datascience.virginia.edu/pages/uva-plans-new-school-data-science) (the 12th) of this [premier](https://www.usnews.com/best-colleges/uva-6968/overall-rankings) US university originally founded by [Thomas Jefferson](https://www.virginia.edu/aboutuva) the [principal author](https://en.wikipedia.org/wiki/Thomas_Jefferson) of the US [Declaration of Independence](https://en.wikipedia.org/wiki/United_States_Declaration_of_Independence).

Dr. Shakeri's research, in conjuction with the [Department of Biomedical Engineering](https://engineering.virginia.edu/departments/biomedical-engineering),
[Systems Biology and Biomedical Data Sciences](https://engineering.virginia.edu/departments/biomedical-engineering/research/systems-biology-and-biomedical-data-sciences),
and the [Biocomplexity Institute](https://biocomplexity.virginia.edu/systems-biology-and-bioinformatics-0) is personally motivated by his own family's experience with cancer, and his strong desire to understand biological networks in order to detect deviations away from normal cellular function and intervene to interrupt the pregression of cancer before it can establish a deleterious cellular homeostasis. Heman (Dr. Shakeri) wants to increase our understanding of complex biological dynamics so that he can give other family's more time with their loved ones than his family was able to have with his father. In his own words, the solution for Heman is "data-driven identification and control of high-dimensional dynamical systems".

The data we will work with is based on advances in the fields of [Flow Cytometry](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5939936/) for single cell analysis and [Mass Spectrometry](https://www.broadinstitute.org/technology-areas/what-mass-spectrometry) for measurement of cellular proteomic processes (the [phenotypical process endpoint](https://en.wikipedia.org/wiki/Central_dogma_of_molecular_biology) of cellular function and behavior). Based on these technologies, the multivariate landscape of proteomic activity can be measured for a single cell in any experiemental condition for any cell type (e.g., cancerous and benign cellular lines) at scale. By understanding typical cellular homeostatis of healthy and deliterious cells, and observing the phenotypical transformation of cellular proteomic homeostatsis over time in response to different treatments, it is hoped that we will eventually understand how to direct deleterious cellular states to transition into non-deleterious states. I.e., "data-driven identification and control of high-dimensional dynamical systems".

The data observations simultaneously measure 17 so-called [AP-1 transcription factors](https://en.wikipedia.org/wiki/AP-1_transcription_factor) over thousands of cells in a given experiemental condition. By repeatedly observing this protein complex as is done in this data, the correlation between the different proteins can be observed. Further, the evolution of this dependency can be observed over time as a response to different interventions. And even further, the emergence of downstream cellular phenotypes in response to changes of the state of the AP-1 system can also be observed and can be characterized through 4 other "phenotype" proteins which are also measured in this data set. Thus, though our course project, we seek to understand the inter-dependence between the AP-1 proteins, and their driving relationship with downstream cellular phenotypes, and how we might intervene along this pathway to induce transformation away from deletarious cellular states. I.e., "data-driven identification and control of high-dimensional dynamical systems".


## Further Details

### Lectures

In-person lectures will review the course slides and .Rmd files

### Tutorials

In-person tutorials will address and practice communication for statistics and data science though various written, group, and presentation exercises

### Office Hours

We will have in-person office hours as well as virtual (zoom) office hours as follows

### Piazza

We will use piazza to support student questions



## Module 1: R Basics

Module 1 is concerned with introducing students to R and [Rstudio](https://www.rstudio.com/) using [UofT's Jupyterhub](https://jupyter.utoronto.ca). Our primary reference resources in this task are

- the [DoSS Toolkit](https://dosstoolkit.com/) created by seasoned STA130 Profs. Alexander and Caetano among many, many others
- the [R for Data Science](https://r4ds.had.co.nz/) textbook by Hadley Wickham & Garret Grolemund


> The [UofT Jupyterhub](https://jupyter.utoronto.ca) is a phenomenal resource; however, it is subject to service outages from time to time (which have in the past coincided with assignment due dates); and, when a heavy user load accesses it at the same time (e.g., if all the students in our class log in at once) it can take time to "spin-up" resource instances to support the demand, so there can be long "loading" periods in such instances.

> An extremely valuable skill in the coding context of statistica and Data Science is troubleshooting and figuring things out.  Resources like the [DoSS Toolkit](https://dosstoolkit.com/) and the [R for Data Science](https://r4ds.had.co.nz/) textbook are structured places to learn things in an organized manner; however, google, stack exchange/overflow, and coding blog posts can be an invaluable resource for finding fixes for coding bugs and solutions for desired analyses. Hopefully through this class you will take the opportunity to build your coding resiliance and self-sufficiency.

### Source Material

I am currently planning to combine module 0 and 1

#### Module 0 material
- https://rstudio-with-jupyerhub-uoft.netlify.app
- https://q.utoronto.ca/courses/253019/pages/opening-editing-knitting-and-downloading-your-rstudio-jupyterhub-problem-sets?module_item_id=3315343
- and cute pictures from Allison Horst in Module 0 and the syllabus

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