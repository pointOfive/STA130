

# Fall 2022 STA130: Introduction to Statistical Reasoning and Data Science

### Welcome!

> *Welcome to your Fall 2022 semester and STA130!* **STA130 Lectures** are Monday's 9:10AM/2:10PM ET for L0101/L0201, and **STA130 Tutorials** are Friday's 9:10AM/2:10PM ET for L0101/L0201. The Fall 2022 term begins September 8, but we won't meet in person for a tutorial on the first Friday, September 9th; instead, you are expected to use your two-hour tutorial block to review the course website and get a head start on familiarizing yourself with R based on your review of the course website.  See you in Lecture on Monday, September 12th!
> 
> -- STA130 Instructor Prof. Scott Schwartz  
> Assistant Professor, Teaching Stream  
> Director, Data Science Programs for Statistical Science   
> 
> P.S. Just call me Scott
---

> *Prior to Winter 2020 this was an **In-Person** course (e.g., [F18](https://ntaback.github.io/UofT_STA130/Fall2018/fall2018_course_content.html), [F19](https://www.statistics.utoronto.ca/sites/www.statistics.utoronto.ca/files/STA130_syllabus_F19.pdf), [W20](https://www.statistics.utoronto.ca/sites/www.statistics.utoronto.ca/files/STA130H1S.pdf)). From Fall 2020 to Winter 2022 it was transitioned to an **Online** course (e.g., [W22](https://q.utoronto.ca/courses/253019)). The current course transitions these iterative course developments back into the previous **In-Person** format. Specifically, the Winter 2022 Online [.ppt and pre-recording material](https://q.utoronto.ca/courses/253019) is integrated into leveraged and reworked [Rstudio Rmd](https://ntaback.github.io/UofT_STA130/Fall2018/fall2018_course_content.html) and [beamer pdf](https://ntaback.github.io/UofT_STA130/Fall2018/fall2018_course_content.html) materials of the previous **In-Person** courses.*

<!-- STUDENTS: Instead of those below (which you will not be given access to), please see https://ntaback.github.io/UofT_STA130/Fall2018/fall2018_course_content.html for previous content -->
<!-- NOT AVAILABLE for student use: https://www.dropbox.com/home/W20_slides-shared -->
<!-- NOT AVAILABLE for student use: https://can01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.dropbox.com%2Fl%2Fscl%2FAACmrT8hzMyabinD1Ioc4_CWCLbgwhZx4lU&data=05%7C01%7Cscott.schwartz%40utoronto.ca%7C07bd03b4049f4302640108da3e67cd9b%7C78aac2262f034b4d9037b46d56c55210%7C0%7C0%7C637890913830493523%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C2000%7C%7C%7C&sdata=7uY5HYCnQ9Rqp4U5KOSh9UigGyzhCfymDSehiQSC6xA%3D&reserved=0 -->


### The philosophy and purpose of STA130

At the highest level, the course activities are meant to develop and practice the final two steps the statistical and data science workflow:


|1. *We'll not be making you struggle to get data yourself*<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br/>2. Extract meaning from data through coding and analysis<br/><br/>3. Communicate findings through writing and speaking|<img src="https://bookdown.org/gavinmasterson/dvfc/images/environmental-data-science-r4ds-general.png" width=75%>|
|-|:-:|
| | [Dr. Julia Lowndes'](https://github.com/allisonhorst/stats-illustrations/raw/master/openscapes/) version of Grolemund & Wickham's<br/>classic R4DS schematic [illustrated](https://github.com/allisonhorst/stats-illustrations#hello) by [@Allison_Horst](https://twitter.com/allison_horst?lang=en).|

<!-- image is now from https://bookdown.org/gavinmasterson/dvfc which could be a good resource? Reminds me of communicating data course UVA -->
<!-- previously https://github.com/allisonhorst/stats-illustrations/raw/master/openscapes/environmental-data-science-r4ds-general.png -->
<!-- but now see also https://www.openscapes.org/gallery/ and https://github.com/Openscapes/teaching-learning-resources-->

### The 5 Learning Objectives of STA130

Specifically, STA130 has the following **5 Learning Objectives**:

1. Implement the computational steps involved in the management and statistical analysis of data using R.
2. Carry out a variety of statistical analyses in R and interpret the results of the analyses.
3. Clearly communicate the results of statistical analyses to technical and non-technical audiences.
4. Identify appropriate uses of statistical methods to answer questions, including their strengths and weaknesses.
5. Describe how statistical methods can be used to learn from data, including methods for description, explanation, and prediction.

# Table of Contents

Please see below for information regarding the following topics:

- [Calendar](#calendar)
- [Learning R](#learning-r)
- [Course project](#course-project)
  - [Course project requirements and scope](#course-project-requirements-and-scope)
  - [Course project data](course-project-data)

- [Outline](#outline)


## Calendar

Fall 2022 semester begins Thursday, September 8th.  Friday, September 9th there is no tutorial. 
The first day of class and the first day of tutorial occur during the week of September 12th.

| Week | Week of | Topic                                     | Monday Lec     | Thursday 5PM | Friday Tut | Friday 10PM |
|------|---------|-------------------------------------------|----------------|--------------|------------|------------|
| 1    | Sep 12  | [Jupyterhub, Rstudio, R Basics](#week-1-jupyterhub-rstudiormd-and-r-basics-and-libraries)             | 9:10AM/2:10PM | HW1 Due      | 9:10AM/2:10PM    | Tut 1 Due  |
| 2    |Sep 19  | [Distributions and Statistics](#week-2-data-types-ggplot2-and-lower-case-statistics)              | 9:10AM/2:10PM | HW2 Due      | 9:10AM/2:10PM    | Tut 2 Due  |
| 3    |Sep 26  | [Data Wrangling with Tidy](#week-3-tidy-data-and-data-wrangling)                  | 9:10AM/2:10PM | HW3 Due      | 9:10AM/2:10PM    | Tut 3 Due  |
| 4    |Oct 3   | [One/Two Sample Hypothesis Testing](#week-4-one-and-two-sample-hypothesis-tests)     | 9:10AM/2:10PM | HW45Part2 Due| 9:10AM/2:10PM    | Tut 4 Due  |
| 5    |Oct 10  | *THANKSGIVING DAY: NO CLASS, RESCHEDULED  |               | HW45Part3 Due| 9:10AM/2:10PM    | **Project Introduction** |
| 6    |Oct 17  | [Bootstrap Confidence Intervals](#week-6-bootstrap-confidence-intervals)            | 9:10AM/2:10PM | HW6 Due      | 9:10AM/2:10PM    | Tut 5 Due  |
| 7    |Oct 24  | **Midterm Review**                        | 9:10AM/2:10PM |              | 9:10AM/2:10PM    | **Midterm Exam**   |
| 8    |Oct 31  | [Simple Linear Regression](#week-8-simple-linear-regression)                  | 9:10AM/2:10PM | HW7 Due      | 9:10AM/2:10PM    | Tut 6 Due  |
| 9    |Nov 7   | READING WEEK                              |                |              |                   |            |
| 10   |Nov 14  | [Multivariate Linear Regression](#week-10-multivariate-linear-regression)                      | 9:10AM/2:10PM | HW8 Due      | 9:10AM/2:10PM    | Tut 7 Due  |
| 11   |Nov 21  | [Classification Decision Trees](#week-11-classification-decision-trees)                      | 9:10AM/2:10PM | HW9 Due      | 9:10AM/2:10PM    | Tut 8 Due  |
| 12   |Nov 28  | [Ethics, Confounding, and Study Design](#week-12-ethics-confounding-and-study-design) | 9:10AM/2:10PM | HW10 Due      | 9:10AM/2:10PM    | Tut 9 Due  |
| 13   |Dec 5   | **Final Review**                          | 9:10AM/2:10PM |              |                   |            |
|  |       | *Oct 10 -> Dec 8th Reschedule             |                | **Thursday** |                   |            |
|   |      |                                           |                | **Dec 8th**  |                   |            |
|    |     |                                           |                | **9:10AM/2:10PM**        |      |            |
|     |    |                                           |                | **Project (DUE)**  |                   |            |
|      |   |                                           |                | **Presentations** |              |            |


## Learning R

Ivan and Rahul Selvakumar have put together some resources for helping you get better at R (found through the Department along with some YouTube channels and MOOCs). These specific resources are highlighted in where appropriate in the [outline](#outline) below as well.  

https://mdl.library.utoronto.ca/support/workshops-and-training

[R self-paced introduction from the Department Of Statistical Sciences](https://dosstoolkit.com/)

- Students can use the code and modules provided to gain some hands-on-experience with R. It covers most of the stuff that students do in STA130 and some more (Using github, maps and etc ) which can be helpful for Statistics competitions and Kaggle competitions.

[R for Data science (Courtesy of Cindy 😊)](https://r4ds.had.co.nz/)

- A thorough book on how R (and its countless packages) can be used to perform data analysis. Although the book delves into a lot of complicated ideas it can be a great place for those who want to venture outside of STA130.

[R Markdown Cookbook](https://bookdown.org/yihui/rmarkdown-cookbook/)

Another excellent book that focuses more on R markdown which is an excellent resource for students who want to learn how to create dynamic pdfs, html files or word documents with R. Having a good understanding of this can be a plus for resume

[Edureka YouTube video](https://www.youtube.com/watch?v=eDrhZb2onWY)

- A more handhold-y youtube guide that involves the basic codes aspects of R. I think this is great for students who are finding it difficult to execute even a single line of code in R.  (just to be clear this is just for this video and not the course that they are running which is way too expensive)

[RStudio’s own education guidelines](https://education.rstudio.com/learn/beginner/)

This covers a few basic ways students (and others) can get started with R. The main page includes a few videos, tutorials, books, and a flowchart with how to get started with R. I also recommend going through until the Intermediate stage which covers, design elements such as visualisation, cheatsheets, statistical models such as regression, and some interactive applications (although this tends to be a more advanced)

[Introduction to R workshop](https://libcal.library.utoronto.ca/event/3691450)

- This is just a workshop held by UofT. Its supposed to be a very basic introduction to R and Rstudio.

## Course project

The course project is meant to give you an example of what it can be like to be a statistician doing applied work.  To give you an authentic experience, you'll work on data from one of my own current projects, and you'll see what real research work is like (at least for an ' $n \text{ of } 1$ ', me!).

Before I moved to UofT I taught at the [University of Virginia](https://www.virginia.edu/) [School of Data Science](https://datascience.virginia.edu/). Fun fact: The [UVA School of Data Science](https://datascience.virginia.edu/pages/uva-plans-new-school-data-science) is the 12th school of the [premier](https://www.usnews.com/best-colleges/uva-6968/overall-rankings) US university originally founded by [Thomas Jefferson](https://www.virginia.edu/aboutuva), the [principal author](https://en.wikipedia.org/wiki/Thomas_Jefferson) of the US [Declaration of Independence](https://en.wikipedia.org/wiki/United_States_Declaration_of_Independence).

While I was at UVA I met [Dr. Heman Shakeri](https://datascience.virginia.edu/people/heman-shakeri) who works in conjuction with the [Department of Biomedical Engineering](https://engineering.virginia.edu/departments/biomedical-engineering) and 
[Systems Biology and Biomedical Data Sciences](https://engineering.virginia.edu/departments/biomedical-engineering/research/systems-biology-and-biomedical-data-sciences). Heman's (Dr. Shakeri's) research involves using "data-driven identification and control of high-dimensional dynamical systems" to detect deviations away from normal cellular function and intervene to interrupt the pregression of cancer before it can establish a deleterious cellular homeostasis. As with many people, Heman's interest in this area is motivated by the personal experience of a close family friend. Heman's work is movtivated by his hope that his research will help give family's more time with their loved ones and close friends.

In my career I've worked in [Integrative Biology](https://sites.cns.utexas.edu/juenger_lab/),
[Nutrition and Complex Disease](https://chapkinlab.tamu.edu), and [Next Generation Sequencing](https://www.txgen.tamu.edu) labs. I've actually been a "Bioinformatician" for about the same amount of time that I've been a "Data Scientist" (in industry) and "Statistician" (here in academia).  So, with that in mind, when Heman and I talk about our research, the conversation looks something like this:

> The data we will work with is based on advances in the fields of [Flow Cytometry](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5939936/) for single cell analysis and [Mass Spectrometry](https://www.broadinstitute.org/technology-areas/what-mass-spectrometry) for measurement of cellular proteomic processes (the [phenotypical process endpoint](https://en.wikipedia.org/wiki/Central_dogma_of_molecular_biology) of cellular function and behavior). Based on these technologies, the multivariate landscape of proteomic activity can be measured for a single cell in any experiemental condition for any cell type at scale (e.g., cellular lines with a cancerous genotype at various stages of progression). By understanding typical cellular homeostatis of healthy and deliterious cells, and observing the phenotypical transformation of cellular proteomic homeostatsis over time in response to different experimental conditions, we may eventually be able to understand how to direct deleterious cellular states to transition into non-deleterious states. And with the ability of "data-driven identification and control of high-dimensional dynamical systems" we'll be able to fight cancer!

Now, if you didn't catch all (or any) of that on your first reading, that's normal.  I'm a seasoned professional (I got my PhD in Statistical Science in 2010) and you're a first year college student... I have a 20-year head start on you. The first thing to do here to begin increasing your understanding is to read things several times, slowly and carefully;  and, sometimes stopping and pausing to make sense of a word or a concept. While it's not *always* going to make sense to do this for every part of something you're reading, try it out on the above "sciency" paragraph and see if you can decipher the information there. Once you've done that, and maybe have a better sense of the different scientific pieces of the project, then let's move on to breaking it down with a little more with more focus on the data rather than the science and technology.

> The data observations simultaneously measure 22 so-called [AP-1 transcription factors](https://en.wikipedia.org/wiki/AP-1_transcription_factor) 
> and 4 phenotype proteins. So there are 26 total variables, 22 of which are thought of as "casues" and 4 of which are thought of as "outcomes". Each measurement is taken on a single cell; but, we can actually measure lots and lots of individual cells at once; and, we can do the measurements under different experiemental conditions, which lets us repeatedly observe these 22 variables over lots of different cells under lots of different treatment conditions (such as at different treatment conditions at different stages of cancer progression).
> - How can we measure the progression over time? Actually, we can't measure the same cells over and over. To make a measurement on a cell we have to destroy it... but, if we take a batch of cells (in a specific experimental condition) then we can split the cells up into groups and make the measurements on the different groups at different times; thus, we observe "the progression of the experimental condition over time".
>
> So the experiment based on condition $x$ and time $t$ produces the following tidy data table
>
>
>| | TF<sub>1</sub> | TF<sub>2</sub> | TF<sub>3</sub> |  $\vdots$| TF<sub>20</sub> | TF<sub>21</sub> | TF<sub>22</sub> | Y<sub>1</sub> | Y<sub>2</sub> | Y<sub>3</sub> | Y<sub>4</sub> | Drug | Dosage | Time | Rep |
>|-|-----|-----|-----|----------|------|------|------|----|----|----|----|------|--------|------|-----|
>|1|     |     |     |          |      |      |      |    |    |    |    |      |        |      |     |
>|2|     |     |     |          |      |      |      |    |    |    |    |      |        |      |     |
>|$\vdots$|  |   |   |          |      |      |      |    |    |    |    |      |        |      |     |
>|$n$|  |   |   |          |      |      |      |    |    |    |    |      |        |      |     |
>
> where the total number of observations $n = \sum_x \sum_t n_{xt}$ is the sum of all the samples $n_{xt}$ in each condition $x$ and time $t$ (which will be different since different batches of cells so we don't always have the same number of cells).
>
> - Note that the "number of individual cells" is the "number of observations" on which the (26) measurements have been made for each experimental condition $x$ which is defined by two drugs and their dosage, and each condition is repeated a few times for validation purposes.

Hopefully this makes things a little more comprehensible now. And actually, you've just had your first formal experience as a consultant!  How so?  Well, in my experience as a statistical, bioinformatic, and data science consultant, the exercise you've just done is exactly how the consulting activity goes.  You meet someone, they tell you about their applied problem, and then you would work to learn what the context is and understand what their problem actually is.  So if you need, review things here a little bit more, and work to make yourself more comfortable with what this project is all about!  

- The great thing about being a consultant in a statistical, bioinformatic, or data science role is how much you get to learn about different application areas. It's an especially great context in which to learn because the people you're learning from are experts in their problem and very knowlegable in their domain of expertise.  Stastistics and data science in particular are quite unique fields in this regard, since statistical and data science expertise is applicable in so many different areas. This means the natural directionality is that methods are taken to data, and so statistical and data science roles are naturally involve more learning about new areas than is generally the case in other disciplines. 

Continuing with the theme of being a statistical consultant, let's start thinking about this problem from a statistical perspective.  What analyses would be helpful for this data?  Here is my own thought process about what we could do with this data.

1. *Do protein levels in experimental condition* $x$ *change over time* $t$? $\longrightarrow$ **Two Sample Hypothesis Testing**
2. *Are protein levels at time* $t$ *different between experimental conditions* $x_1$ *and* $x_1$? $\longrightarrow$ **Two Sample Hypothesis Testing**
3. *At time* $t$ *in experimental condition* $x$, *what is the relationship between different proteins*? $\longrightarrow$ **Correlation Estimation**
4. *Can we predict cellular phenotypical outcomes* $(Y)$ ***values/states*** *from transcription factors (TF)*? $\longrightarrow$ **Regression/Classification**
5. *At what times* $t$ *in experimental conditions* $x$ *can we do this*? $\longrightarrow$ **Regression/Classification**
6. *At time* $t$ *in experimental condition* $x$, *what TF are most predictive of cellular*  ***values/states*** $(Y)$? $\longrightarrow$ **Regression/Classification**
7. Are there patterns in the patterns? Each above analyses is a result, but what's the analysis of the results themselves? $\longrightarrow$ meta...

Of the analyses proposed above, we've so far only covered **Hypothesis Testing**.  A good place to both get started on the project as well as familiarize yourself with the data would be to start by doing some **Hypothesis Testing** on the data.  *In general, you should use the project to reinforce the topics we're learning by trying them out on the project data. Not only will this be beneficial for your learning, but it will help you avoid a last-minute rush to create your material for the* **Project Poster Presentations on Thursday, December 8th**.  For example, ***Confidence Intervals*** are the next tool we'll cover in the course. How can we use ***Confidence Intervals*** in the context of our course project data, specifically with respect to ***correlation***?

### Course project requirements and scope

Your Course Project will grade (20% of course grade) will be divided up between an initial logistics planning proposal (2% of course grade), 
a live poster presentation (8% of course grade), and an offline evaluation of your submitted poster presentation slides (10% of course grade).

#### Your poster presentation and slides will be evaluated based on your presentation of 3 of the 5 distinct categories of analyses noted above (Hypothesis Testing, Confidence Intervals, Correlation, Regression, Classification) and the use of supporting visualizations and explanation.

#### The group logistics planning proposal is due my midnight on October 28th, which is the same week as the Midterm Exam. 
- The requirement to plan project meeting and work logistics with your group during the week of the Midterm Exam is intended to emphasize scheduling during time when it's particularly relevent; and, to perhaps generate useful opportunties for group study sessions, so hopefully this is something you're doing sooner rather than later.  It should not be the case that you're rushing to finish this after the Midterm Exam.

#### The poster presentations will be on December 8th, and project slides will be due on December 8th as well.

|<img src="poster_fair.JPG" height=400px>|<img src="poster_fair_2.jpg" height=400px>|
|-|-|

#### Outstanding projects will successfully accomplish the required tasks as part of a coherent narrative addressing the bigger picture of the project: what is "good" cellular homeostasis, and how can "bad" cellular homeostasis be changed to be "good"?

For the purposes of the course project, your objective is to answer three questions like those from 1-6 above for our data from our collaborator Dr. Shakeri. Question 7 is not required for the project, but you may be interested in pursuing it anyway if you're attempting to submit an *outstanding* project. In doing so, you would likely address the following questions:
- How do the observed correlations evolve over time under the different experimental conditions?
- Is this temporal dynamic *itself* predictive of the eventual state of the downstream cellular phenotypes?
- Are the temporal dynamics different or somehow controlled by the experimental conditions?

By looking at these more advanced "meta" questions, we may be able to understand the inter-dependence of the AP-1 proteins, their driving relationship with downstream cellular phenotypes, and how we may be able intervene along this pathway to induce transformation away from deletarious cellular states. If there are certain correlation structures in the TF proteins that leads to good and bad phenotype outcome states $Y$, can we affect the correlation structure of the TF proteins with some treatment which changes the state from a bad phenotype to a good one?

> By understanding typical cellular homeostatis of healthy and deliterious cells, and observing the phenotypical transformation of cellular proteomic homeostatsis over time in response to different experimental conditions, we may eventually be able to understand how to direct deleterious cellular states to transition into non-deleterious states. And with this "data-driven identification and control of high-dimensional dynamical systems" we will be able to fight cancer!

### Course project groups

There will be 6 project teams of 4 students per TUT group (perhaps with some groups of 3 depending on course enrollments). Working groups are one of the primary communities we are a part of in life. Take advantage of the opportunity to make connections with your peers!  Collaborative work is -- and I cannot stress this enough -- **A HUGE** part of the being a Statistician or a Data Scientist. So take this opportunity to practice being a good team member. Learn from your peers, meet your peers where they're at and be charitable and generous in your interactions with them, and do your best to be supportive and helpful to your team.  You'll need to work as a team to plan your project strategy, divide and assign tasks, and collaboratively improve and refine your work. Be constructive and help synergize your teams potential!

Your first group project assignment (worth 2% of the total 20%, i.e., 2%+18%=20%) is to plan the routine and cadence of your group work and meetings. You will submit a proposal for how you plan to collaborate and work together, as well as a general roadmap of your groups strategy for accomplishing the tasks of the course project. Your proposal must detail how you will systematically explore the data and the applicability and results of applying the methods you're learning to the data. 

#### Your proposal MUST also commit your group to a weekly cadence of project work. This is mandatory and not optional for full marks on this proposal. 

Your proposal should address the following questions. When will you meet? How will you meet? How will you communicate outside of meetings? How will you determine which group members do which work? What will you do if a group member is not completing the work they agreed to? What will you do if you can't agree on what work the members of the group will do? What will you do if there are problems with group dynamics? The proposal planning your group logistics is due my midnight on October 28th, which is the same week as the Midterm Exam. Your groups proposal will be evaluated based on the expected effectiveness of the plan, and the contingencies put in place by the proposal that give your group the ability to handle adversity and challenge in a self-sufficient manner.  

Submit your group meeting and working logistics proposal (expected to be approximately 100-500 words) [here on Quercus](https://q.utoronto.ca/courses/277998/assignments/910660). Your submitted document must include the names of each member of your group, and each member of your group must have approved and signed the proposal, and each member of the group must submit this document individually in order to receive a grade for this component. If it has not been possible to contact and engage a group member for the purposes of creating the proposal, document your "reasonable and sufficient" attempt to contact the absent group member as an appendix to your proposal.

### Caution and advice

There are many things to explore in this data. But remember, the project is scored based on your presentation of 3 of the 5 distinct categories, not the exhaustiveness of your analysis. It is worth spending time on exploratory data analysis (EDA) as it will help you form your initial objectives and guide any advanced work you do beyond the basic project requirements; but, if you find your EDA requiring too much time and effort, then you need to quickly determine how you can reduce the scope of your efforts.  You will never be able to do everything you want to with a data set, and you need to be comfortable working efficiently towards clear and achieveable objectives while avoiding "analysis paralysis" -- this is a very important skill for being effective and productive as a statistician or a data scientist.
 
> When you're examining the dependency between the proteins, only examine the different proteins within one particular treatment condition at first. If you're consider comparing analyses across different treatment conditions, it's first to best to confirm that repeated batches (`Rep`) are behaving reproducibly. If you are starting to compare different treatment conditions, it's best to start by just comparing two different treatment conditions, and perhaps it makes the most sense to compare the first and last timepoints within a drug since those should show the greatest differentiation.

### Course project data

The data for the course project comes from [this article](https://www.biorxiv.org/content/10.1101/2021.12.06.471514v1.full) finding that the 
"AP-1 transcription factor network" (i.e., the relative distributions and dependency relationships of transcription factors) are predictive of "cellular plasticity in melanoma" (i.e., how easily changable the phenotypes are melanoma cell lines), and is available for download [here](https://drive.google.com/uc?id=1m-bc56NfKErzkxdlHXBLWQg14W2R2vd8&export=download)

| Phenotype Indicators      | MiTFg | Sox10 | NGFR | AXL | | | |
|--------------------------:|-------|-------|------|-----|-------------|-------------|-------------|
| AP-1 transcription factors| ATF2  |ATF3   | ATF4 | ATF5|Phospho_ATF1 | Phospho_ATF2 | Phospho_ATF4|
|                           | ATF6  | JunB  |c_Jun |JunD | Phospho_S6  |Phospho_c_Jun | Phospho_Erk1 |
|    NF_kappaB              | Fra1  | Fra2  | c_Fos|Ki_67 | Phospho_Fra1 | Phospho_c_Fos | Phospho_p38 |


The cellular phenotypes of melanoma cell can be characterized in terms of the HIGH/LOW balance of the four phenotype indicators MiTFg, NGFR, SOX10, and AXL as follows

| Cellular Phenotype \ Gene  | MiTFg| NGFR | SOX10 | AXL |
|----------------------------|------|------|-------|-----|
| Undifferentiated           | LOW  | LOW  | LOW   | HIGH|
| Neural crest-like          | LOW  | HIGH | HIGH  | HIGH| 
| Transitory                 | HIGH | HIGH | HIGH  | LOW |
| Melanocytic                | HIGH | HIGH | LOW   | LOW |

where the HIGH/LOW distinctions are determined empirically from the data.



## Outline

### Week 1: Jupyterhub, Rstudio/Rmd, and R Basics and Libraries

|<img src="https://jupyterhub.readthedocs.io/en/0.9.0/_static/logo.png" width=200px>|<img src="https://www.rstudio.com/wp-content/uploads/2018/10/RStudio-Logo-Flat.png" width=300px>|<img src="https://westcampus.yale.edu/sites/default/files/event-images/r_0.png" width=150px>|<img src="https://tidyverse.tidyverse.org/logo.png" width=125px>|
|-|-|-|-|

| [Slides](https://github.com/pointOfive/STA130_Week1_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week1_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week1_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week1_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet1) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet1&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269319) by 5 p.m. ET Thursday |
|-|-|
| [PollEV](https://pollev.com/sta) In-Class Questions Round [1](https://PollEv.com/surveys/wQpfE3KrENeWTTTNu7nwi/respond), [2](https://PollEv.com/surveys/a5mpfyaCt7s2wjpd4g1cy/respond), [3](https://PollEv.com/surveys/TTyRWyCnpBiQlDENmFG9E/respond), [4](https://PollEv.com/surveys/E3s7y55RNjSFvJ1gI44Iy/respond), [5](https://PollEv.com/surveys/iyPJyiwyHLcjmF3kbQNwo/respond) | |

Week 1 is concerned with introducing students to [R](https://www.r-project.org/) and R libraries (like [tidyverse](https://www.tidyverse.org/)), [Rstudio](https://www.rstudio.com/) and [UofT's Jupyterhub](https://jupyter.utoronto.ca). Our primary reference resources in this task are

- the [R for Data Science](https://r4ds.had.co.nz/) (R4DS) textbook by Hadley Wickham & Garret Grolemund (previously [Hands-On Programming with R](https://d1b10bmlvqabco.cloudfront.net/attach/ighbo26t3ua52t/igp9099yy4v10/igz7vp4w5su9/OReilly_HandsOn_Programming_with_R_2014.pdf))
  - specifically the [Introductory R](https://r4ds.had.co.nz/workflow-basics.html) and [R Markdown](https://r4ds.had.co.nz/r-markdown.html) material
- online Markdown [tutorials](https://www.markdownguide.org/getting-started/), [cheetsheats](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), and [resources](https://www.markdowntutorial.com/)
- the [DoSS Toolkit](https://dosstoolkit.com/) created by seasoned STA130 Profs. Alexander and Caetano et al.
  - specifically the [RStudio](https://dosstoolkit.com/#hello-world), [errors](https://dosstoolkit.com/#operating-in-an-error-prone-world),
and [packages](https://dosstoolkit.com/#holding-the-chaos-at-bay) [tutorials](https://dosstoolkit.com/#if-you-have-never-used-r-before)
- [RStudio R](https://rstudio.cloud/learn/primers/1.2) and [R Markdown](https://rmarkdown.rstudio.com/) primers 
  - and see also RStudio's [R Markdown](https://raw.githubusercontent.com/rstudio/cheatsheets/main/rmarkdown.pdf) and [RStudio](https://raw.githubusercontent.com/rstudio/cheatsheets/main/rstudio-ide.pdf) [cheatsheets](https://www.rstudio.com/resources/cheatsheets/)
- and [free online introductions to R](https://www.datacamp.com/courses/free-introduction-to-r) from learning websites like [datacamp](https://www.datacamp.com/).

> The [UofT Jupyterhub](https://jupyter.utoronto.ca) is a phenomenal resource; however, it is subject to service outages from time to time (which have in the past coincided with assignment due dates), and it can take a long time to load when there's a lot of simultaneous user demand (if a lot of students in our or another class log in at once). When you cannot use [UofT Jupyterhub](https://jupyter.utoronto.ca) you must use your own [local Rstudio instance](https://www.rstudio.com/).

> An extremely valuable skill in the context of coding for statistics and Data Science is troubleshooting and figuring things out.  Resources like the [R for Data Science](https://r4ds.had.co.nz/) textbook and the the [DoSS Toolkit](https://dosstoolkit.com/) are excellent recources to learn things in a systematic, structured, and organized manner; however, google, stack exchange/overflow, and coding blog posts can be an invaluable resource for finding quick solutions for coding bugs and suggestions for how to complete a desired analyses. Hopefully through this class you will take the opportunity to build your self-sufficiency and coding-resiliance.



### Week 2: Data Types, ggplot2, and (lower case) statistics

|<img src="https://pbs.twimg.com/media/EkoDNU6U0AISh-u.jpg" width=300px> @AllisonHorst |<img src="https://pbs.twimg.com/media/Ehh6v4kVoAIbotc.jpg:large" width=400px> @AllisonHorst |<img src="https://ggplot2.tidyverse.org/logo.png" width=150px>|
|-|-|-|

| [Slides](https://github.com/pointOfive/STA130_Week2_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week2_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week2_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week2_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet2) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet2&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269319) by 5 p.m. ET Thursday |
|-|-|
| [PollEV](https://pollev.com/sta) In-Class Questions Round [1](https://PollEv.com/surveys/fr3VWMEBXve0CAxxM1rIu/respond), [2](https://PollEv.com/surveys/Xk5h0ZwTNozrsyXHYtbbk/respond), [3](https://PollEv.com/surveys/t0wHO6X6Mb65iBBAlJ6zq/respond) | Ungraded Optional [Quercus Practice Quiz](https://q.utoronto.ca/courses/239327/quizzes/269319) | 

Week 2 differentiates ([numerical](https://www.jove.com/science-education/12573/how-data-are-classified-numerical-data) and [ordinal](https://www.jove.com/science-education/12574/ordinal-level-of-measurement) and [nominal](https://www.jove.com/science-education/12798/nominal-level-of-measurement) data types [categorical](https://www.jove.com/science-education/12797/how-data-are-classified-categorical-data)) and explores the [technical details](https://r4ds.had.co.nz/vectors.html) of [R data types](https://rstudio.cloud/learn/primers/1), which directly informs the choice of [appropriate visualizations of data](https://www.jove.com/science-education-library/160/summarizing-and-visualizing-data). Building on this foundation, the `ggplot2` ["grammer of graphics"](https://www.amazon.com/Grammar-Graphics-Statistics-Computing/dp/0387245448/ref=as_li_ss_tl) syntax is then introduced (with associated learning and refernce resources listed below) using the examples of `bar`, `histogram`, and `boxplot` `geom_`'s (but of course there are [MANY](https://datavizcatalogue.com), [MANY](https://www.data-to-viz.com) other kinds of plots, too). The `fig.size` and `fig.width` [R Markdown sizing parameters](https://r4ds.had.co.nz/graphics-for-communication.html?q=fig.width#figure-sizing) are also introduced at this stage (and again see below for additional R Markdown learning and reference materials). Standard [location](https://q.utoronto.ca/courses/277998/pages/jove-videos) ([mean](https://www.jove.com/science-education/12810/arithmetic-mean), [median](https://www.jove.com/science-education/12815/median), [mode](https://www.jove.com/science-education/12814/what-is-a-mode)) and [scale](https://q.utoronto.ca/courses/277998/pages/jove-videos) (IQR, [range, variance, standard deviation](https://www.scribbr.com/statistics/variability/)) statistics for characterizing distributions are introduced, and higher order distributional characterizations are covered ([skewness](https://www.jove.com/science-education/12816/skewness), etc.) 

| ggplot2 Resources and References | Markdown Resources and References |
|----------------------------------|-----------------------------------|
| [Official Cheatsheet](https://github.com/rstudio/cheatsheets/blob/main/data-visualization-2.1.pdf)|[RStudio Markdown Cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)|
| &nbsp;&nbsp;&nbsp; [Finding Answers](https://ggplot2.tidyverse.org/#getting-help)| &nbsp;&nbsp;&nbsp; [R4DS Introduction](https://r4ds.had.co.nz/r-markdown.html) |
| [Learning Resources](https://ggplot2.tidyverse.org/#learning-ggplot2)| &nbsp;&nbsp;&nbsp; [RStudio Introduction](https://rmarkdown.rstudio.com/) |
| &nbsp;&nbsp;&nbsp; [Official Usage](https://ggplot2.tidyverse.org/#usage)| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [knitr Documentation](https://yihui.org/knitr/) | 
| &nbsp;&nbsp;&nbsp; [R4DS Textbook](https://r4ds.had.co.nz/data-visualisation.html)| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [.Rmd Documentation](https://bookdown.org/yihui/rmarkdown/) |
| &nbsp;&nbsp;&nbsp; [DoSS Toolkit](https://dosstoolkit.com/#to-ggplot-or-not-to-ggplot)| [Markdown Tutorial](https://www.markdowntutorial.com/)|

### Week 3: Tidy Data and Data Wrangling

|<img src="https://tidyr.tidyverse.org/logo.png" width=150px>|<img src="https://dplyr.tidyverse.org/logo.png" width=150px>|<img src="https://image.jimcdn.com/app/cms/image/transf/none/path/sc907c1c4cc8c1f1e/image/i3129eb909b67b786/version/1617197006/image.jpg" width=325px>|
|-|-|-|


| [Slides](https://github.com/pointOfive/STA130_Week3_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week3_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week3_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week3_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet3) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet3&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269908) by 5 p.m. ET Thursday |
|-|-|
| [PollEV](https://pollev.com/sta) In-Class Questions Round [1](https://PollEv.com/surveys/fr3VWMEBXve0CAxxM1rIu/respond), [2](https://PollEv.com/surveys/5I8qbQ9DrPyHPivrRfOjJ/respond), [3](https://PollEv.com/surveys/t0wHO6X6Mb65iBBAlJ6zq/respond) | Ungraded Optional [Quercus Practice Quiz](https://q.utoronto.ca/courses/239327/quizzes/269908) | 

Week 3 is concerned with defining "Tidy Data" and introducing the following "Data Wrangling" functions from the `dplyr` library.

|           |             |          |            |            |
|-----------|-------------|----------|------------|------------|
|`filter()` |`mutate()`   |`mean()`  |`min()`     |`&`         |
|`select()` |`case_when()`|`median()`|`max()`     |`\|`        |
|`rename()` |`summarise()`|`var()`   |`quantile()`|`!`         |
|`arrange()`|`group_by()` |`sd()`    |`n()`       |`%in%`      |
|`desc()`   |`is.na()`    |`IQR()`   |`sum()`     |`rm.na=TRUE`|


For additional introductions to these topics see the [Tidy Data](https://r4ds.had.co.nz/tidy-data.html) and [Transformation](http://r4ds.had.co.nz/transform.html) of the [R4DS textbook](https://r4ds.had.co.nz/index.html).  For additional `dplyr` resources please see the UofT [DoSS Toolkit](https://dosstoolkit.com/#hand-me-my-plyrs) and the official [`dplyr`](https://dplyr.tidyverse.org/#cheat-sheet) cheat sheet. Additional advanced data wrangling tools are available through the [dplyr](https://dplyr.tidyverse.org/) and [tidyr](https://tidyr.tidyverse.org/) [tidyverse](https://www.tidyverse.org/) libraries.  For additional `tidyr` resources please see the official [`tidyr`](https://tidyr.tidyverse.org/#cheatsheet) cheat sheet.


### Week 4: One and Two Sample Hypothesis Tests

|<img src="https://www.dummies.com/wp-content/uploads/362521.image0.jpg" width=450px>|<img src="https://i.ytimg.com/vi/5Z9OIYA8He8/maxresdefault.jpg" width=450px>|
|-|-|

| [Slides](https://github.com/pointOfive/STA130_Week4_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week4_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week4_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week4_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet45) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet45&urlpath=rstudio%2F&branch=main)] **Part 2** and **Part 3** due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269908)  |
|-|-|
| **Strongly Recommended** Ungraded Quercus Practice Quizzes on | respectively at 5 p.m. ET on Thursday **this week and next** | 
| [One](https://q.utoronto.ca/courses/277998/quizzes/279243) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_PracticeQuiz_OneSampleHypothesisTest_ABCD&urlpath=rstudio%2F&branch=main)] and [Two](https://q.utoronto.ca/courses/277998/quizzes/279244) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_PracticeQuiz_TwoSampleHypothesisTest_gratitude&urlpath=rstudio%2F&branch=main)] Sample Hypothesis Tests | Ungraded Optional Quercus Practice Quizzes [One](https://q.utoronto.ca/courses/277998/quizzes/279237) and [Two](https://q.utoronto.ca/courses/277998/quizzes/279238) |

Week 4 is extremely packed begins an extensive coding assignment, **Part 2** of which is due at the original 5 p.m. ET time on Thursday during **Week 4**, and **Part 3** of which is due at 5 p.m. ET time on Thursday of **Week 5**. Both Part 2 and 3 each have one optional question. The remaining parts of the coding assignment are Part 1 which is optional but designed to be more guided and structed to support learning if needed and Part 4 which is optional but ***Strongly Recommended*** practice material to test and support your learning. 

- There is so much available practice material because there is no lecture during Week 5 after hypothesis testing, and it's important to stay engaged with R and the class so that your progressing and retention provides good support leading into the Week 7 midterm. They hypothesis testing material is potentially quite challenging, and certainly very dense, so the more bolstering and reinforcement of your learning the better.

The actual topic of Week 4 is a specific kind of *Statistical Inference* called *Hypothesis Testing*. Specifically, we'll examine $\alpha$-significance level decisions using *simulation* and *permutation* *p-values* for one sample and hypothesis testing for two samples, as well as Type I and Type II errors. Implementation of these procedures largely on the two new R coding constructs of `sample(x, size=n, prop=1/n, replace=FALSE)` and `for (i in 1:N){ ... }`, as well as some cleaver use of `group_by()`, `summarise()` and a new `diff()` function.  

- We also introduce $\LaTeX$ formatting $H_0, H_{1}, H_{A}, \alpha, \bar x, \hat p, \mu,$ and $\sigma$, which are repsectively `$H_0, H_{1}, H_{A}, \alpha, \bar{x}, \hat{p}, \mu$` and `$\sigma$`.  This overleaf [introduction](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes#Adding_math_to_LaTeX) to formatting math statements in $\LaTeX$, or the specific topics of [subscripts](https://www.overleaf.com/learn/latex/Subscripts_and_superscripts), [symbols](https://www.overleaf.com/learn/latex/List_of_Greek_letters_and_math_symbols), and here's a list from stackexchange of some possible [accent decorators](https://tex.stackexchange.com/questions/66537/making-hats-and-other-accents-bold) such as "bar" and "hat".

> - If you would find a textbook presentation of these topics helpful, check out sections 2.1, 2.2, 2.3, and 2.4 of [Introductory Statistics with Randomization and Simulation from OpenIntro](https://leanpub.com/isrs). You can download the textbook for free by using a price of 0, which is absolutely fine since you're students.
> - For an additional presentation of two sample permutation-based hypothesis testing, check out the [excellent slides](https://ntaback.github.io/UofT_STA130/Fall2018/week6/sta130_oct15_week6-annotated.pdf) from a previous STA130 instructor. These slides are especially recommended for their compelling data examples of "gender bias in promotion recommendation" and "whether or not you can recover from an all-nighter in a couple days".

### Week 5: Introduction to the Course Project 

|<img src="https://static.independent.co.uk/s3fs-public/thumbnails/image/2014/08/15/01/AssetAccessCA0SIS94.jpg" width=400px>|<img src="https://www.pnas.org/cms/10.1073/pnas.0708244105/asset/15443f90-1bca-4350-916c-6f0e62f6873e/assets/graphic/zpq0050894180001.jpeg" width=300px>|
|-|-|

- **The [Course Project](#course-project) will be introduced in Tut on Friday of this week.**
- **READ the [Course Project](#course-project) description BEFORE Tut on Friday of this week.**
- There is *No Lecture* on Thanksgiving (Monday).
- Complete **Part 3** of the **Week 4** [Problem Set](https://github.com/pointOfive/STA130_ProblemSet45) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet45&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269908) by 5 p.m. ET on Thursday.
- It is **Strongly Recommended** that you complete the *Ungraded Quercus Practice Quizzes* on [One](https://q.utoronto.ca/courses/277998/quizzes/279243) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_PracticeQuiz_OneSampleHypothesisTest_ABCD&urlpath=rstudio%2F&branch=main)] and [Two](https://q.utoronto.ca/courses/277998/quizzes/279244) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_PracticeQuiz_TwoSampleHypothesisTest_gratitude&urlpath=rstudio%2F&branch=main)] Sample Hypothesis Tests to bolster and reinforce of your learning of the potentially challenging, and certainly very dense, hypothesis testing material.


### Week 6: Bootstrap Confidence Intervals

|<img src="https://images.hhbrown.com/Justin/Pair/BR735-617x563.jpg" width=250px>|<img src="https://sites.nicholas.duke.edu/statsreview/files/2013/06/cipretty.jpg" width=500px>|
|-|-|

| [Slides](https://github.com/pointOfive/STA130_Week6_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week6_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week6_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week6_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet6) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet6&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269908) by 5 p.m. ET Thursday |
|-|-|
|  | Ungraded Optional [Quercus Practice Quiz](https://q.utoronto.ca/courses/239327/quizzes/271819) | 

This week introduces a second class of *Statistical Inference* methods known as *Confidence Interval*. Specifically, we consider *Bootstrapping Confidence Intervals*, which are based on the underlying premise of approximating the unavailable population with the available sample (which naturally benefits from increased sample sizes $n$).  We show the long-term behavior of different *Confidence Intervals* relative to the Confidence Intervals width (controlled by the Confidence level of the interval), and compare and contrast *Confidence Intervals* with *Hypothesis Tests*. We also introduce the "p-value controversy", as well as the "measure of evidence" perspective of p-values (as opposed to $\alpha$-level significance testing), but again return to *Confidence Intervals* as an effective way to communicate statitical inference findings. We note that  *Confidence Intervals* suffer from fewer potential interpretation pitfalls than p-value based analyses, but for the same reason (that parameter values are *unknown* but **fixed**) have the technical peculiarity that they provide probabilities about themselves as procedures rather the parameter values they estimate (resulting in the use of term *Confidence*). We discuss the role of the sample size for the width of the *Confidence Interval* (as opposed to the level of confidence of the interval).  And we visualze the behavior of the *Sampling Distribution* (the percentiles of which define *Confidence Intervals*) as a function of $n$ and the *skewness* of the original population.

- The course slides outline the topic list for this section of the course. For another treatment of the *Bootstrap Confidence Interval* workflow, please see [Chapter 13: Estimation](https://inferentialthinking.com/chapters/13/Estimation.html) from the [Inferential Thinking](https://inferentialthinking.com) textbook.  For more specific explanations of certain topics, or further details of the subtle technical issues, please search out sources online. 


### Week 7: Midterm Review and Friday Midterm

|<img src="http://intake.education/sites/default/files/2022-07/exam-2020.jpg" width=500px>|
|-|



- Monday's lecture period will be will be used as a review for the midterm.
- **The Course Midterm will take place in Tut on Friday of this week.**

### Week 8: Simple Linear Regression

|<img src="https://saylordotorg.github.io/text_introductory-statistics/section_14/88a6e0919d8617c025826c1e187ad591.jpg" width=500px>|<img src="https://miro.medium.com/max/960/1*jt-pyQQ7bgL2lyganse0nQ.png" width=500px>|
|-|-|



| [Slides](https://github.com/pointOfive/STA130_Week8_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week8_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week8_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week8_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet7-Week8) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet7-Week8&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/272781) by 5 p.m. ET Thursday |
|-|-|
|  | Ungraded Optional [Quercus Practice Quiz](https://q.utoronto.ca/courses/239327/quizzes/272781) | 

Week 8 introduces the `geom_point()` plot and `facet_grid()` layout from `ggplot2`, as well as the Correlation measure $r$ of linear association. The Simple Linear Regression (normal) model is then introduced, and the aspects of its specification are explored. Finally, model interpretability, the Coefficient of Determination $R^2$, indicator variables and scaling, and Hypothesis Testing in the Simple Linear Regression context are addressed.

- As Simple Linear Regression is such a fundamental methodology, if you're looking for further explanations and information you will be able to readily find resources online with some searching.

### Week 9: Reading Week

|<img src="https://media.cntraveler.com/photos/61eae278c101d1d3fd6ac204/master/w_3872,h_2592,c_limit/Aruba_GettyImages-170618386.jpg" width=500px>|
|-|

Have great break!

### Week 10: Multivariate Linear Regression

|<img src="https://i.stack.imgur.com/fkkoH.png" width=400px>|<img src="https://i.imgur.com/DT4H1Yk.jpg" width=500px>|
|-|-|

| [Slides](https://github.com/pointOfive/STA130_Week10_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week10_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week10_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week10_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet8-Week10) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet8-Week10&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/275202) by 5 p.m. ET Thursday |
|-|-|
|  | Ungraded Optional [Quercus Practice Quiz](https://q.utoronto.ca/courses/239327/quizzes/275202) + [More Practice Questions](multivariate_regression_quiz.pptx)| 

Week 10 extends to the Simple Linear Regression framework into Multivariate Linear Regression. The Prediction exercise is compared to the Hypothesis Testing and Estimation frameworks as another form of Statistical Inference. The Coefficient of Determination $R^2$ is revisited, and Variable Selection using Hypothesis Testing is examined with specific attention payed to the effects of Multicollinearity (observable Confounding) and Practical versus Statistical Significance. The Out of Sample (80/20) Train-Test framework is then introduced along with RMSE and explored, and the role of chance in Hypothesis Testing and Out of Sample Testing is emphasized. Finally, interactions are introduced and some model comparision and selection demonstrations are given. 

- As Multivariate Linear Regression is such a fundamental methodology, if you're looking for further explanations and information you will be able to readily find resources online with some searching.


### Week 11: Classification Decision Trees

|<img src="https://miro.medium.com/max/1400/1*sJOaKrX2-PQLsI3qaVqmCQ.png" width=500px>|<img src="https://laughingsquid.com/wp-content/uploads/cat-decision.jpg" width=250px>|
|-|-|


| [Slides](https://github.com/pointOfive/STA130_Week11_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week11_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week11_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week11_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet9-Week11) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet9-Week11&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/277450) by 5 p.m. ET Thursday |
|-|-|
|  | Ungraded Optional [Quercus Practice Quiz](https://q.utoronto.ca/courses/239327/quizzes/277450) | 

Week 11 introduces Binary (and Multi-Class) Classification Decision Trees.  Classifification is a prediction methodology that is related to Regression based prediction and along with Regression completes the prediction category of Statistical Inference. While the Hypothesis Testing and Estimation categories of Statistical Inference are traditionally "statistical", the prediction category is often a part of Machine Learning and Data Science.  Simple Linear and Multivariate Regression are examples of statistical models which are used for prediction; whereas, Decision Trees are examples of predictive Machine Learning algorithms which are used for prediction.  There are many examples of predictive Machine Learning algorithms which do prediction (such as Random Forests); and, there are statistical models which do clssification (such as logistic regression, which is slightly misnomered). 

The difference between Classification and Regression is that Classification predicts "classes" (like "yes" or "no") while Regression predicts real-valued outputs (such as the price of something).  When predicting specific classes you are making decisions which are "right" or "wrong" (as opposed to in regression where your prediction is off by some amount called the "residual"). In this sense, Classification is conceptually similar to Hypothesis testing in that Type I and Type II errors characterize the types of incorrect decisions you can make about a hypothesis, whereas in Classification the analogous notions are called False Positives and False Negatives.  Based on these error, and the correct classifications called True Positives and True Negatives, a number of "Metrics" are used to quantify the performance of the classification method; namely, for example, precision, sensitivity/recall (True Positive Rate, or one minus False Positive Rate), and Specificity (True Negative Rate, or one minus False Negative Rate). The implications of all of these aspects in the context of a specific application is explored carefully, in addition to their technical specifications. In particular, Confusion Matrices relative to which all these metrics and considerations can be framed are of central importance and are thus a focal point of the discussion and analysis. 

As noted, Decision Trees comprise a particular class of Classification Algorithms. The various aspects of Decision Tree methods are explored and detailed, including: node and branching structures, their recursive partitioning treatment of the data, and the thresholding mechanism by which they can favor reducing False Positives or False Negatives (depending on prioritization of these errors implied by the application domain). Model comparision is considered, and the 80/20 Train-Test methodology is reviewed and again applied in the service of this objective. 

- As Classification, Confusion Matrices, and Decision Trees (and all related details and terminologies) are such fundamental methodologies in Prediction, Data Science, and Machine Learning, if you're looking for further explanations and information you will be able to readily find resources online with some searching.


### Week 12: Ethics, Confounding, and Study Design

|<img src="https://www.scu.edu/media/mobi/blog-variants/Ethics-Blog-760x550-760x550.png" width=275px>|<img src="https://sixsigmadsi.com/wp-content/uploads/2021/05/confounding.png" width=200px>|<img src="http://blog.manuscriptedit.com/wp-content/uploads/2014/01/Analytical-Study.jpg" width=350px>|
|-|-|-|


| [Slides](https://github.com/pointOfive/STA130_Week12_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week12_Slides&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet10-Week12) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet10-Week12&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/277998/assignments/910651) by 5 p.m. ET Thursday |
|-|-|
|  | Ungraded Optional [Quercus Practice Quiz #1](https://q.utoronto.ca/courses/277998/quizzes/285166) and (#2)[https://q.utoronto.ca/courses/277998/quizzes/285168] | 

Some fantastic HIGHLY RECOMMENDED reading for this, our last last lecture week of class is the [Data Science Ethics](https://mdsr-book.github.io/mdsr2e/ch-ethics.html) chapter from the Baumer et al. [Modern Data Science with R](https://mdsr-book.github.io/mdsr2e/) textbook. This reading will provide a reflective and structured opportunity to review the key ethics topics that are idiomatic within the data analysis arena. After reviewing these topics ourselves -- including ethics around Webscrapping, APIs, free and informed consent, privacy, and algorithmic bias -- we will then introduce the notion of confounding, through which we will discuss the various forms of experimental and observational study designs; namely, controlled randomized experiements, and prospective, cohort, case-control, and longitudinal studies. If the topics learning about the world through data collection studies interests you then you should seriously consider taking [STA304: Surveys, Sampling and Observational Data](https://artsci.calendar.utoronto.ca/course/sta304h1) at some point in your future careers.


### Week 13: Final Review

### Also Week 13: Course Proejct Presentations

- Thursday, December 8th at the usual Monday Lecture time



