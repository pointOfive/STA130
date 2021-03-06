

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

> *Prior to Winter 2020 this was an **In-Person** course (e.g., [F18](https://ntaback.github.io/UofT_STA130/Fall2018/fall2018_course_content.html), [F19](https://www.statistics.utoronto.ca/sites/www.statistics.utoronto.ca/files/STA130_syllabus_F19.pdf), [W20](https://www.statistics.utoronto.ca/sites/www.statistics.utoronto.ca/files/STA130H1S.pdf)). From Fall 2020 to Winter 2022 it was transitioned to an **Online** course (e.g., [W22](https://q.utoronto.ca/courses/253019)). The current course transitions these iterative course developments back into the previous **In-Person** format. Specifically, the Winter 2022 Online [.ppt and pre-recording material](https://q.utoronto.ca/courses/253019) is integrated into leveraged and reworked [Rstudio Rmd](https://can01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.dropbox.com%2Fl%2Fscl%2FAACmrT8hzMyabinD1Ioc4_CWCLbgwhZx4lU&data=05%7C01%7Cscott.schwartz%40utoronto.ca%7C07bd03b4049f4302640108da3e67cd9b%7C78aac2262f034b4d9037b46d56c55210%7C0%7C0%7C637890913830493523%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C2000%7C%7C%7C&sdata=7uY5HYCnQ9Rqp4U5KOSh9UigGyzhCfymDSehiQSC6xA%3D&reserved=0) and [beamer pdf](https://ntaback.github.io/UofT_STA130/Fall2018/fall2018_course_content.html) materials of the previous **In-Person** courses.*

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

- [Schedule](#schedule)
- [Grading](#grading)
  - [Accomodations](#accomodations)
  - [Best 7/9 policy](#best-79-policy)
    - [Student Health](#best-79-policy)  
  - [Participation](#participation)
- [Help](#help)
- [Calendar](#calendar)
- [Course project](#course-project)
- [Outline](#outline) (where you'll find all the course material)

## Schedule

The course (on average across students) should take 10 hours a week with 7 hours allocated for

| Section     |             | Monday     | Thursday       | Friday     |
|-------------|-------------|------------|----------------|------------|
|  L0101      |  9:10 AM ET | Lec (2hrs) |                | In-Person Tut work (2hrs) |
|  L0201      | 2:10 PM ET  | Lec (2hrs) |                | In-Person Tut work (2hrs) | 
| L0101+L0201 | 5:00 PM ET  |            | R (2hr) HW Due |            |
| L0101+L0201 | 10:00 PM ET |            |                | Tut work (+1hr) Due |

and 3 hours left available for study and review, office hours and piazza discussion boards, and eventual team project work.

## Grading

| Components             | Notes                | Absence Policy            | Accomodation Requests | 
|------------------------|----------------------|---------------------------|-----------------------|
| 7% R Homework          | 9 assignments        | Best 7/9 are Scored       | See below             |
| 14% In-Person Tut work | 9 activities         | Best 7/9 are Scored       | See below             |
| 20% Course project     |                      | Due Dec 8th               | Emergency Absenses ONLY  |
| 20% Midterm            |                      | Reweights to Final if Missed | Automatic          |
| 34% Final exam         |                      | Excused Absence Rescheduling | Handled through FAS |
| 5% Participation       | Mentorship + Surveys | Due Dec 8th               | No Extensions Available |
| N/A Lectures           | Not Recorded         | N/A                       | Lecture `.Rmd`+Slides Available |
| N/A Study Material     | Not Graded           | Optional Material         | N/A                   |

#### Accomodations

| Accomodation | Contingency Request Recipient(s) | Notes |
|-|-|-|
| Best 7/9 policy | Automatic: no student action required |
| Extended 7/9 policy | [College Registrar](https://www.artsci.utoronto.ca/current/academic-advising-and-support/college-registrars-offices) + sta130@utorono.ca | Notice must be provided within one week of return to UofT activities |
| Final Exam | [FAS Exam Deferrel Petition](https://www.artsci.utoronto.ca/current/faculty-registrar/petitions/deferred-exams) | The Faculty of Arts and Sciences administers the final exam |
| Miderm Exam | Final Reweighting | This is automatic so no request is required | 
| Course Porject | sta130@utorono.ca | Extensions will be granted only for Emergency Absenses ONLY |

#### Best 7/9 policy

For students having a "normal" experience acclimating to the UofT context, 
this should provide a comfortable buffer against minor unexpected events or schedule management growing pains. For example

- if you have several assignments due at once and are unable to complete an R Homework assignment in time
- if you're not feeling well and are unable to attend TUT and turn in the TUT activity work in time

you'll get a "zero" but if this is one of your two lowest two scores in a categegory it will be dropped won't count towards that categories final score.

***Physical Health***: This policy is intended support your ability to make positive personal and community health choices.  This policy should encourage staying home and resting when it's the right thing to do. 

***Personal Well-Being***: It is increasingly understood that belonging and community are extremely important for our emotional health, and coming to class and doing your work is a part of your sense of belonging in our community. Sometimes it can be good to "take a break", too, and this policy certainly covers that.

Contingencies involving **three absences** due to health related issues can be initiated through your [College Registrar](https://www.artsci.utoronto.ca/current/academic-advising-and-support/college-registrars-offices) and can be accomodated upon the recommendation of the Registrar with the following limitations:

- Accomodations involving **three absences** due to health related issues will be considered provided that notice of the advent of special circumstances is made to both (a) the [College Registrar](https://www.artsci.utoronto.ca/current/academic-advising-and-support/college-registrars-offices) and (b) sta130@utorono.ca within one week of return to University activities. 
- Accomodations beyond the "Best 7/9 policy" involving one or two health related absences will not be considered.
- Accomodations beyond the "Best 7/9 policy" involving time management challenges will not be considered.
- So if you've already "used up" your "Best 7/9 policy" but then get sick, you won't be able to omit additional "zeros".

#### Participation

Complete the DoSS STA130 mentorship program. The STA130 mentorship program is composed of 3 pillars designed to facilitate your engagement and inclusion in our community. To get credit for each pillar you must BOTH (a) attend an event (b) and submit a reflection of your experience. Reflections are due by 10 p.m. ET on December 8th.

- Mentor meeting (1%)
- Career event (1%)
- Social event (1%) 

Help us with "get to know the class" and "how'd we do" surveys.

- Beginning of course survey (1%)
- End of course survey (1%)


## Help

| Ask your Tut TA | Get One on One Help | Get help from Classmates | 
|-|-|-|
| Friday Tuts | TA Online Office Hours | Online Discussion Board |



## Calendar

Fall 2022 semester begins Thursday, September 8th.  Friday, September 9th there is no tutorial. 
The first day of class and the first day of tutorial occur during the week of September 12th.

| Week of | Topic                                     | Monday Lec     | Thursday 5PM | Friday Tut | Friday 10PM |
|---------|-------------------------------------------|----------------|--------------|-------------------|------------|
| Sep 12  | Jupyterhub, Rstudio, R Basics             | 9:10AM/2:10PM | HW1 Due      | 9:10AM/2:10PM    | Tut 1 Due  |
| Sep 19  | Distributions and Statistics              | 9:10AM/2:10PM | HW2 Due      | 9:10AM/2:10PM    | Tut 2 Due  |
| Sep 26  | Data Wrangling with Tidy                  | 9:10AM/2:10PM | HW3 Due      | 9:10AM/2:10PM    | Tut 3 Due  |
| Oct 3   | One and Two Sample Inference              | 9:10AM/2:10PM | HW4 Due      | 9:10AM/2:10PM    | Tut 4 Due  |
| Oct 10  | *THANKSGIVING DAY: NO CLASS, RESCHEDULED  |                |              | 9:10AM/2:10PM    | **Projet Introduction** |
| Oct 17  | Sampling Dists and Bootstrap CIs          | 9:10AM/2:10PM | HW5 Due      | 9:10AM/2:10PM    | Tut 5 Due  |
| Oct 24  | **Midterm Review**                        | 9:10AM/2:10PM |              | 9:10AM/2:10PM    | **Midterm Exam**   |
| Oct 31  | Linear Regression I                       | 9:10AM/2:10PM | HW6 Due      | 9:10AM/2:10PM    | Tut 6 Due  |
| Nov 7   | READING WEEK                              |                |              |                   |            |
| Nov 14  | Linear Regression II                      | 9:10AM/2:10PM | HW7 Due      | 9:10AM/2:10PM    | Tut 7 Due  |
| Nov 21  | Classification Trees                      | 9:10AM/2:10PM | HW8 Due      | 9:10AM/2:10PM    | Tut 8 Due  |
| Nov 28  | Study Design, Confounding, Ethics         | 9:10AM/2:10PM | HW9 Due      | 9:10AM/2:10PM    | Tut 9 Due  |
| Dec 5   | **Final Review**                          | 9:10AM/2:10PM |              |                   |            |
|         | *Oct 10 -> Dec 8th Reschedule             |                | **Thursday** |                   |            |
|         |                                           |                | **Dec 8th**  |                   |            |
|         |                                           |                | **9:10AM/2:10PM**        |      |            |
|         |                                           |                | **Project (DUE)**  |                   |            |
|         |                                           |                | **Presentations** |              |            |


## Course project

The course project will be done in consultation with our "project collaborator" [Dr. Heman Shakeri](https://datascience.virginia.edu/people/heman-shakeri) of the [University of Virginia's](https://www.virginia.edu/) (UVA) [Data Science Institute](https://datascience.virginia.edu/) (DSI). The DSI is a recently created [School](https://datascience.virginia.edu/pages/uva-plans-new-school-data-science) (the 12th) of this [premier](https://www.usnews.com/best-colleges/uva-6968/overall-rankings) US university originally founded by [Thomas Jefferson](https://www.virginia.edu/aboutuva) the [principal author](https://en.wikipedia.org/wiki/Thomas_Jefferson) of the US [Declaration of Independence](https://en.wikipedia.org/wiki/United_States_Declaration_of_Independence).

Dr. Shakeri's research, in conjuction with the [Department of Biomedical Engineering](https://engineering.virginia.edu/departments/biomedical-engineering) and 
[Systems Biology and Biomedical Data Sciences](https://engineering.virginia.edu/departments/biomedical-engineering/research/systems-biology-and-biomedical-data-sciences),
is motivated by the experience with cancer of a close family friend. So, Heman (Dr. Shakeri) wants to use "data-driven identification and control of high-dimensional dynamical systems" to detect deviations away from normal cellular function and intervene to interrupt the pregression of cancer before it can establish a deleterious cellular homeostasis in order to  give family's more time with their loved ones and close friends.

The data we will work with is based on advances in the fields of [Flow Cytometry](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5939936/) for single cell analysis and [Mass Spectrometry](https://www.broadinstitute.org/technology-areas/what-mass-spectrometry) for measurement of cellular proteomic processes (the [phenotypical process endpoint](https://en.wikipedia.org/wiki/Central_dogma_of_molecular_biology) of cellular function and behavior). Based on these technologies, the multivariate landscape of proteomic activity can be measured for a single cell in any experiemental condition for any cell type (e.g., cancerous and benign cellular lines) at scale. By understanding typical cellular homeostatis of healthy and deliterious cells, and observing the phenotypical transformation of cellular proteomic homeostatsis over time in response to different treatments, it is hoped that we will eventually understand how to direct deleterious cellular states to transition into non-deleterious states. I.e., "data-driven identification and control of high-dimensional dynamical systems".

The data observations simultaneously measure 17 so-called [AP-1 transcription factors](https://en.wikipedia.org/wiki/AP-1_transcription_factor) over thousands of cells in a given experiemental condition. By repeatedly observing this protein complex (as is done in this data), the correlation between the different proteins can be observed. Further, the evolution of these dependencies can be observed over time as a response to different interventions. And even further, the emergence of downstream cellular phenotypes in response to changes of the state of the AP-1 system can also be observed and can be characterized through 4 other "phenotype" proteins (whose measurements are also available in this data set). Thus, though our course project, we seek to understand the inter-dependence between the AP-1 proteins, and their driving relationship with downstream cellular phenotypes, which might eventually suggest how we can intervene along this pathway to induce transformation away from deletarious cellular states. 

## Outline

### Week 1: Jupyterhub, Rstudio/Rmd, and R Basics and Libraries)

| [Slides](https://github.com/pointOfive/STA130_Week1_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week1_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week1_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week1_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet1) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet1&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269319) by 5 p.m. ET Thursday |
|-|-|
| [PollEV](https://pollev.com/sta) In-Class Questions Round [1](https://PollEv.com/surveys/i80dlyI1tanNNrvFwC74C/respond), [2](https://PollEv.com/surveys/a5mpfyaCt7s2wjpd4g1cy/respond), [3](https://PollEv.com/surveys/TTyRWyCnpBiQlDENmFG9E/respond), [4](https://PollEv.com/surveys/Y04VP2B2iE7j4gtHBTMPq/respond), [5](https://PollEv.com/surveys/iyPJyiwyHLcjmF3kbQNwo/respond) | |

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

| [Slides](https://github.com/pointOfive/STA130_Week2_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week2_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week2_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week2_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet2) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet2&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269319) by 5 p.m. ET Thursday |
|-|-|
| [PollEV](https://pollev.com/sta) In-Class Questions Round [1](https://PollEv.com/surveys/fr3VWMEBXve0CAxxM1rIu/respond), [2](https://PollEv.com/surveys/5I8qbQ9DrPyHPivrRfOjJ/respond), [3](https://PollEv.com/surveys/t0wHO6X6Mb65iBBAlJ6zq/respond) | Ungraded Optional [Quercus Practice Quiz](https://q.utoronto.ca/courses/239327/quizzes/269319) | 

Week 2 differentiates ([numerical](https://www.jove.com/science-education/12573/how-data-are-classified-numerical-data) and [ordinal](https://www.jove.com/science-education/12574/ordinal-level-of-measurement) and [nominal](https://www.jove.com/science-education/12798/nominal-level-of-measurement) data types [categorical](https://www.jove.com/science-education/12797/how-data-are-classified-categorical-data)) and explores the [technical details](https://r4ds.had.co.nz/vectors.html) of [R data types](https://rstudio.cloud/learn/primers/1), which directly informs the choice of [appropriate visualizations of data](https://www.jove.com/science-education-library/160/summarizing-and-visualizing-data). Building on this foundation, the `ggplot2` ["grammer of graphics"](https://www.amazon.com/Grammar-Graphics-Statistics-Computing/dp/0387245448/ref=as_li_ss_tl) syntax is then introduced (with associated learning and refernce resources listed below) using the examples of `bar`, `histogram`, and `boxplot` `geom_`'s (but of course there are [MANY](https://datavizcatalogue.com), [MANY](https://www.data-to-viz.com) other kinds of plots, too). The `fig.size` and `fig.width` [R Markdown sizing parameters](https://r4ds.had.co.nz/graphics-for-communication.html?q=fig.width#figure-sizing) are also introduced at this stage (and again see below for additional R Markdown learning and reference materials). Standard location ([mean](https://www.jove.com/science-education/12810/arithmetic-mean), [median](https://www.jove.com/science-education/12815/median), [mode](https://www.jove.com/science-education/12814/what-is-a-mode)) and [scale](https://www.scribbr.com/statistics/variability/) (range, IQR, variance, standard deviation) statistics for characterizing distributions are introduced, and higher order distributional characterizations are covered ([skewness](https://www.jove.com/science-education/12816/skewness), etc.).

| ggplot2 Resources and References | Markdown Resources and References |
|----------------------------------|-----------------------------------|
| [Official Cheatsheet](https://github.com/rstudio/cheatsheets/blob/main/data-visualization-2.1.pdf)|[RStudio Markdown Cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)|
| &nbsp;&nbsp;&nbsp; [Finding Answers](https://ggplot2.tidyverse.org/#getting-help)| &nbsp;&nbsp;&nbsp; [R4DS Introduction](https://r4ds.had.co.nz/r-markdown.html) |
| [Learning Resources](https://ggplot2.tidyverse.org/#learning-ggplot2)| &nbsp;&nbsp;&nbsp; [RStudio Introduction](https://rmarkdown.rstudio.com/) |
| &nbsp;&nbsp;&nbsp; [Official Usage](https://ggplot2.tidyverse.org/#usage)| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [knitr Documentation](https://yihui.org/knitr/) | 
| &nbsp;&nbsp;&nbsp; [R4DS Textbook](https://r4ds.had.co.nz/data-visualisation.html)| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [.Rmd Documentation](https://bookdown.org/yihui/rmarkdown/) |
| &nbsp;&nbsp;&nbsp; [DoSS Toolkit](https://dosstoolkit.com/#to-ggplot-or-not-to-ggplot)| [Markdown Tutorial](https://www.markdowntutorial.com/)|

### Week 3: Tidy Data and Data Wrangling

| [Slides](https://github.com/pointOfive/STA130_Week3_Slides) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week3_Slides&urlpath=rstudio%2F&branch=main)] + [Demo](https://github.com/pointOfive/STA130_Week3_Demo) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week3_Demo&urlpath=rstudio%2F&branch=main)] | [Problem Set](https://github.com/pointOfive/STA130_ProblemSet3) [[Jupyterhub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet3&urlpath=rstudio%2F&branch=main)] due [on Quercus](https://q.utoronto.ca/courses/239327/quizzes/269908) by 5 p.m. ET Thursday |
|-|-|
| [PollEV](https://pollev.com/sta) In-Class Questions Round [1](https://PollEv.com/surveys/fr3VWMEBXve0CAxxM1rIu/respond), [2](https://PollEv.com/surveys/5I8qbQ9DrPyHPivrRfOjJ/respond), [3](https://PollEv.com/surveys/t0wHO6X6Mb65iBBAlJ6zq/respond) | Ungraded Optional [Quercus Practice Quiz](https://q.utoronto.ca/courses/239327/quizzes/269908) | 

Week 3 is concerned with defining "Tidy Data" and introducing the following "Data Wrangling" functions from the `dplyr` library.

| | | | | |
|-----------|-------------|----------|------------|------------|
|`filter()` |`mutate()`   |`mean()`  |`min()`     |`&`         |
|`select()` |`case_when()`|`median()`|`max()`     |`\|`        |
|`rename()` |`summarise()`|`var()`   |`quantile()`|`!`         |
|`arrange()`|`group_by()` |`sd()`    |`n()`       |`%in%`      |
|`desc()`   |`is.na()`    |`IQR()`   |`sum()`     |`rm.na=TRUE`|


For additional introductions to these topics see the [Tidy Data](https://r4ds.had.co.nz/tidy-data.html) and [Transformation](http://r4ds.had.co.nz/transform.html) of the [R4DS textbook](https://r4ds.had.co.nz/index.html).  For additional `dplyr` resources please see the UofT [DoSS Toolkit](https://dosstoolkit.com/#hand-me-my-plyrs) and the official [`dplyr`](https://dplyr.tidyverse.org/#cheat-sheet) cheat sheet. Additional advanced data wrangling tools are available through the [dplyr](https://dplyr.tidyverse.org/) and [tidyr](https://tidyr.tidyverse.org/) [tidyverse](https://www.tidyverse.org/) libraries.  For additional `tidyr` resources please see the official [`tidyr`](https://tidyr.tidyverse.org/#cheatsheet) cheat sheet.





### Module 4: Statistical Inference for a Single Sample Proportion

### Module 5: Permutation Tests for Two Groups

### Midterm Review

### Module 6: Sampling Distributions and Bootstrap Confidence Intervals

### Module 7: Linear Regression I

### Module 8: Linear Regression II

### Module 9: Classification Trees

### Module 10: Study Design, Confounding, and Ethics

### Final Review
