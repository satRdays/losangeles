# SatRday LA 2019 Sessions

Workshop | Speaker(s) | More info
------------------------------------|------------------------|--------
Using Data Science to solve Platform Problems at TrueCar | Rachel Shuyan Wang | [>](#Using-Data-Science-to-solve-Platform-Problems-at-TrueCar)
Productionizing R scripts in the cloud | Gergely Daróczi | [>](#Productionizing-R-scripts-in-the-cloud)
Better Research Planning Through Simulation | Neal Fultz | [>](#Better-Research-Planning-Through-Simulation)
Performing Data Science: A Musician's Perspective | Leondra James | [>](#Performing-Data-Science-A-Musicians-Perspective)
Future: Friendly Parallel and Distributed Processing in R for Everyone | Henrik Bengtsson | [>](#Future-Friendly-Parallel-and-Distributed-Processing-in-R-for-Everyone)
From correlation to causation: measuring ad effectiveness at scale | Tamara Greasby | [>](#From-correlation-to-causation:-measuring-ad-effectiveness-at-scale)
Multiple Response (Multivariate) Regression models in R | Cesar Acosta-Mejia | [>](#Multiple-Response-Multivariate-Regression-models-in-R)
Pipes or Brackets: The Similarities and Differences between Dplyr and Data.Table and the Power of Un | Jeremy Guinta, Amy Linehan | [>](#Pipes-or-Brackets-The-Similarities-and-Differences-between-Dplyr-and-DataTable-and-the-Power-of-Un)
---

## Using Data Science to solve Platform Problems at TrueCar
#### Rachel Shuyan Wang
##### Data Science Manager at TrueCar
In this talk, Rachel will share her success on using Data Science methodology to solve several problems on the TrueCar platform, and demonstrate how these algorithms have improved user experience, matching efficiency, as well as increased total revenue. The methods and algorithms she has tried range from as simple as binning and linear regression, to as complicated as deep learning and neutral networks. She will discuss how platforms face similar data science problems and how these TrueCar methods can be applied to other platform services. Other than the technology, Rachel will also share her experience working as a business focusing manager coming from an engineering background, and what she has learned along the way.


## Productionizing R scripts in the cloud
#### Gergely Daróczi
##### DataOps at System1

One of the greatest strength of R is the ease and speed of developing a prototype (let it be a report or dashboard, a statistical model or rule-based automation to solve a business problem etc), but deploying to production is not a broadly discussed topic despite its importance. This hands-on talk focuses on best practices and actual R packages to help transforming the prototypes developed by business analysts and data scientist into production jobs running in a secured environment that is easy to maintain -- discussing the importance of logging, standardizing code style, source-code versioning, unit and integration tests, securing credentials, effective helper functions to connect to database, open-source and SaaS job schedulers, dockerizing the run environment and scaling infrastructure.


## Better Research Planning Through Simulation
#### Neal Fultz

Research plans need to specify the population of interest, a sampling method, an experimental assignment method, and a method to estimate and test parameters of interest. In all but the most simple designs, these steps can interact, unintentionally leading to biased or under-powered studies, and ex-ante diagnostics (such as power calculations) may not have easy, closed form solutions.

Instead, researchers turn to simulation methods. We have implemented DeclareDesign, a set of free and open-source R packages, to make due diligence much easier:

* fabricatr - create realistic synthetic data sets, with hierarchical, panel and correlated structure. 

* randomizr - conduct random sampling and assignment with clusters, blocks or strata. 

* estimatr - fast estimators for design-based inference (with clustered and robust standard errors) 

* DeclareDesign - an extensible framework for declaring, simulating, and diagnosing research designs.

The suite of packages allows researchers to mix and match different strategies, and run simulations to determine the best plan to answer their research questions.

## Performing Data Science: A Musician's Perspective 
#### Leondra James
##### Manager, Analytics & Operations at Saatchi & Saatchi

A motivational talk regarding the key to learning data science, geared towards professionals / students with a non-STEM academic background. Told from the perspective of a data analytics professional / data science student with both a liberal arts and business/ analytics background. Highlights the strengths and necessity of performing / liberal arts students and how their skillset can apply to data science and contribute to the field.


## Future: Friendly Parallel and Distributed Processing in R for Everyone
#### Henrik Bengtsson
##### UCSF, Assoc Prof, CS/Stats, R since 2000

In this talk, I'll present the future ecosystem, which provides a simple, unified framework for parallel and distributed processing in R. It allows you to "write parallel code once" regardless of the operating system and compute environment.

In programming, a 'future' is an abstraction for a value that may be available at some point in the future. The non-blocking nature of futures makes them ideal for asynchronous evaluation of expressions in R, e.g. in parallel on the local machine, on a set of remote machines, via an HPC job scheduler, or in the cloud.

At its core, there are two construct: 'f <- future({ expression })' to evaluate an expression in parallel and 'v <- value(f)' to retrieve its result at a later point in the code. Based on these constructs, higher-level map-reduce constructs can be created, e.g. 'future_lapply()', and doFuture backends for 'foreach()'. How and when futures are resolved is specified by 'plan()' without having to modify the R code. The future framework is available on CRAN and has been used in production for several years.

R packages:

* future (https://cran.r-project.org/package=future)

* future.apply (https://cran.r-project.org/package=future.apply)

* doFuture (https://cran.r-project.org/package=doFuture)

Keywords: parallel processing, distributed processes, compute cluster, high-performance compute (HPC) environment, performance


## From correlation to causation: measuring ad effectiveness at scale
#### Tamara Greasby
##### Director of Data Science @ The Trade Desk
Everyone has had that one ad for that one pair of shoes follow them everywhere they go on the internet. Why does that happen? Especially if you already bought the shoes?! To make sense of this, it's worth understanding how marketers have historically measured ad effectiveness -- and why the problem is harder than it seems. After an overview of some of commonly used methods, I'll walk through how we've approached the problem at The Trade Desk including how we use R to complement our production systems.

## Shiny: A GUI for the Tidyverse
#### Carl Ganz
##### CTO Good Tree
The Tidyverse aims to provide an interface for data analysis that abstracts away complexity as much as possible. In my talk, I will discuss how Shiny fits into the Tidyverse framework. I will go into detail about the significance of abstraction in the Tidyverse, and how Shiny provides additional abstractions. My hope is that this talk will deepen attendees understanding of the Tidyverse, while providing practical applications of Shiny.

## Multiple Response (Multivariate) Regression models in R
#### Cesar Acosta-Mejia
##### Faculty member, Department of Industrial and Systems Engineering at USC
In many applications, several responses are of interest. 
For example, predicting the sales of substitute goods (the demand of one is linked to that of other goods).
If predicting the sales of a set of substitutes is of interest, a multiple response regression model may be appropriate.

Most applications where prediction is of interest include fitting a regression model for each response.
When responses are some how related, a multivariate response regression should be used.

We show how to build a model to fit several responses (or dependent variables) 
from several common predictor variables using R.
Even though under the standard linear regression assumptions the fitted equations 
are the same as those that result from fitting each response to the set of predictors, the predictions may not be independent. 

For univariate regression models, the accuracy of the prediction is given by a prediction interval. When several responses are related, the accuracy is given by a prediction region .

Therefore, Confidence regions and Prediction regions substitute the usual 
confidence intervals and prediction intervals from univariate linear regression models.
For the simplest case, with just two responses, the confidence and prediction regions become 
confidence and prediction ellipses.
We do not go into the multivariate statistics behind these models.
But rather we show examples to develop the intuition behind the relevant conclusions.

Using a two-response example, we show that if the predictions are positively (negatively) correlated,
overprediction of one response may lead to overprediction (underprediction) of the other response.
In this example, we use data visualization to show how the responses are related to the common set of predictors.

## Pipes or Brackets: The Similarities and Differences between Dplyr and Data.Table and the Power of Un 
#### Jeremy Guinta, Amy Linehan
##### Data Scientist; Litigation Consultant; Statistical Expert at Ankura Consulting
In the world of R programming, dplyr consistently emerges as a popular, successful and common way of coding for both new and experienced R programmers. Neat, organized and versatile, dplyr provides anyone from a beginning programmer to an advanced professional a wide range of functionality to organize, clean, and analyze data. However, at times, especially if working with data containing millions of observations, there is another alternative to dplyr. Providing many of the same benefits as dplyr, data.table is also consistently a faster, more memory efficient and compact way of programming in the R language. Many experienced R programmers rely on either dplyr or data.table to advance and improve their analyses over base R. However, understanding and using the packages interchangeably, together and understanding when an analysis calls for one package over the other enables programmers to take their work to the next level. Using both dplyr and data.table in a career, project, or even together in a single script provides numerous opportunities for more efficient, clean and organized analyses. Learn from industry experts the pros and cons of both data.table and dplyr and situations where one package can be utilized more efficiently over the other as well as how to rely on both packages within a single analysis.
Beginning with an introduction to both packages, this presentation will delve into the basic syntax, use, and functions in both dplyr and data.table. This presentation is geared towards any programmer – from beginner just introducing themselves to R to professionals who are interested in diversifying their code to address and solve different problems. The introduction to both packages will be robust and thorough, providing even a programmer without experience in either package the ability to follow along and understand. After an introduction to each package, the presentation will address the strong pros and cons for dplyr and data.table and compare the two. Specifically, the presentation will focus on the differences between speed, syntax, memory, joins and the use of date fields between the packages. The presentation will highlight situations in which one package triumphs as well as how to incorporate both packages smoothly within an analysis.
Led by industry experts who use both packages in real world data analysis, this presentation will rely on real-world examples and data to illustrate the advantages and disadvantages of each package.Additional examples will highlight how to address the same situation or analysis two different ways: in dplyr and in data.table. 
The goal of this presentation is to the leave the audience excited and engaged about not one but two powerful packages in R that can transform the speed, efficiency and approach to a vast number of analyses within academia and across professional fields. Furthermore, this presentation will introduce the audience to applicable methods of both packages with messy and large data that professional programmers engage with regularly. Regardless of if you enter the presentation as a new R programmer, a die-hard Hadley and pipe fan or a dedicated data.table user, this presentation will provide you with countless opportunities and ways to diversity your programming, think critically about how you’re approaching an analysis, and witness how popular dplyr and data.table functions and commands are utilized to perform real-world professional analyses.
