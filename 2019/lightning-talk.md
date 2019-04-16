# SatRday LA 2019 Lightning Talks

Lightning Talk | Speaker(s) | More info
------------------------------------|------------------------|--------
A Tidy Analysis of LAX Holiday Traffic Using Twitter and R | Greg Botwin | [>](#A-Tidy-Analysis-of-LAX-Holiday-Traffic-Using-Twitter-and-R)
R for teaching ecology | Gaurav Kandlikar | [>](#R-for-teaching-ecology)
Integrating R and Google Drive or Collaborative Research | Hannah Rempel | [>](#Integrating-R-and-Google-Drive-or-Collaborative-Research)
Physical Culture and Working Memory | Michael Espero | [>](#Physical-Culture-and-Working-Memory)
Computing information criteria for multilevel models using different sample sizes | Wendy Christensen | [>](#Computing-information-criteria-for-multilevel-models-using-different-sample-sizes)
How R-Maps Showed an Old Industry a New Route | Yujia Guan, Amar Natt, PhD | [>](#How-R\-Maps-Showed-an-Old-Industry-a-New-Route)
---

## A Tidy Analysis of LAX Holiday Traffic Using Twitter and R
#### Greg Botwin
##### Researcher at Cedars-Sinai
[Slides](https://github.com/satRdays/losangeles/blob/master/2019/slides/08LightningTalks/01A%20Tidy%20Analysis%20of%20LAX%20Holiday%20Traffic%20Using%20Twitter%20and%20R%20-%20UPDATED.pdf) | 
[Video](https://youtu.be/D-MYUGZLrdQ)

Los Angeles’s notorious “soul destroying” traffic reaches peak levels of frustration during the holiday period. From 2018-DEC-19 through 2019-JAN-02, the Los Angeles International Airport (LAX) twitter (@flyLAXairport) account posted hourly traffic updates detailing the time it took to reach Terminal 1 from three common transit routes, and the time necessary to complete one loop on the upper or lower levels. In this talk I will highlight the utility of the rtweet package and the use of tidy data principles with tidyverse tools in performing an exploratory data analysis. I will show the variation in LAX traffic times by route, time, and day during the 2018-2019 holiday season and generate some basic advice on how one can save some time and sanity.


## R for teaching ecology
#### Gaurav Kandlikar
##### PhD Candidate, UCLA Department of Ecology and Evolutionary Biology
[Slides](https://github.com/satRdays/losangeles/blob/master/2019/slides/08LightningTalks/02gkandlikar-r-for-teaching-ecology.pdf)
Introductory undergraduate ecology courses often introduce students to population dynamics models which track, for example, the dynamics of competing species in natural systems. Students in these classes generally have a background in biology and limited exposure to mathematical or statistical thinking. This can make it difficult for students to learn the lessons from population dynamics models or to analyze complex ecological data. Here, I will present a set of basic Shiny apps that help convey these ecological models, and also present a Shiny app designed to help students interactively analyze data from environmental DNA sequencing studies.


## Integrating R and Google Drive or Collaborative Research
#### Hannah Rempel
##### M.S. Student, Biological Sciences, Cal Poly
[Slides](https://github.com/satRdays/losangeles/blob/master/2019/slides/08LightningTalks/03HRempel_SatRdaysLALightingTalk_RandGDrive.pdf)
Collaborative research and a move towards reproducible data analysis have become increasingly prevalent not only in data science but also biological and social sciences. However, knowing how to use and integrate these resources can be daunting– particularly for those who use statistics and R in collaborative research but are not statisticians. How do you manage projects with data that span across years, locations and with collaborators varying in knowledge of R and data management practices? How do you maintain consistent entry, documentation and version control of data and scripts modified by multiple people across years? In this talk, I discuss how to interweave R and Google Drive. Google Drive is familiar, free and accessible to everyone– including for those not versed in R or Git. Google Docs allows clear documentation of data and scripts with readily navigable links. Google Sheets facilitates data entry by multiple users, with validation and column/sheet protection to manage data upstream before reading and cleaning sheets in R. I will share my experiences and tips from working with 15+ undergraduates and researchers from other institutes on a project spanning 5+ years.


## Physical Culture and Working Memory
#### Michael Espero
##### Certified Data Scientist
[Slides](https://docs.google.com/presentation/d/1bwYYwOFlvZjyEjNS_yElC3IwulV1AXre0g0l9DdOW2g/)

This 5-minute lightning talk will be a blitz through recent literature and an R workflow conducting the wrangling, summary, visualization, and statistical testing of a small sample of experimental data.


## Computing information criteria for multilevel models using different sample sizes
#### Wendy Christensen
##### University of California, Los Angeles
[Slides](https://github.com/satRdays/losangeles/blob/master/2019/slides/08LightningTalks/05Christensen%20SatRDay%20Lightning%20Talk.pdf)

Multilevel models are a popular choice for researchers seeking to model clustered data. Likelihood ratio tests are used to select among nested multilevel models, but in the case of non-nested models, information criteria are a viable alternative method of model selection. There are many information criteria available, which are often described as being either asymptotically efficient (e.g. AIC, AICC) or asymptotically consistent (e.g. BIC, CAIC). The formulae for these information criteria differ, but the model-specific inputs are the same across criteria. These include the model’s deviance, the number of estimated parameters, and, for criteria that are sample size-dependent, the sample size. In the context of multilevel modeling, there are two valid sample sizes: the total number of observations (N) and the number of clusters (m). Statistical software packages used for multilevel modeling, including R packages like lme4 and nlme, usually provide information criteria computed based on one of the valid sample sizes. In this talk, I will demonstrate how to use R to compute information criteria for multilevel models using either N or m as the sample size. 


## How R-Maps Showed an Old Industry a New Route
#### Yujia Guan, Amar Natt, PhD
##### Econ One Research
[Slides](http://rpubs.com/Yujia/483519)

Economic consulting for litigation is a conservative industry. Analysis tools are dominated by Stata and SAS, while new software tools are widely regarded with suspicion. There is little will for innovation. A senior economist’s desire for attractive maps to be used in a large price-fixing case created an opportunity to introduce R as a powerful open-source alternative to traditional statistical tools: models and maps! The sophisticated story-telling power and captivating outlook delivered by R maps induced further interest from leadership regarding the advantages and capabilities of R. This small point of entry has slowly stirred a tide of change in a very entrenched industry.
