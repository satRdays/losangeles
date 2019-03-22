# SatRday LA 2019 Keynotes

Keynote | Speaker | More info
------------------------------------|------------------------|--------
Lifting the Curtain on Machine Learning | Norm Matloff | [>](#Lifting-the-Curtain-on-Machine-Learning)
Scalable Automatic Machine Learning with H2O | Erin LeDell | [>](#Scalable-Automatic-Machine-Learning-with-H2O)
---

## Lifting the Curtain on Machine Learning
#### Norm Matloff
##### CS Prof, UC Davis
I will present two R packages, polyreg and prVis, that are aimed at taking a questioning look at some machine learning (ML) methods -- why do they work (when they do), and can we develop simpler methods that are just as effective if not more so?  No prior background in ML will be assumed.

## Scalable Automatic Machine Learning with H2O
#### Erin LeDell
##### Chief Machine Learning Scientist at H2O.ai
The focus of this presentation is scalable and automatic machine learning using the H2O machine learning platform.  H2O is an open source, distributed machine learning platform designed for big data.  The core machine learning algorithms of H2O are implemented in high-performance Java, however, fully-featured APIs are available in R, Python, Scala, REST/JSON, and also through a web interface. Since H2O's algorithm implementations are distributed, this allows the software to scale to very large datasets that may not fit into RAM on a single machine. H2O currently features distributed implementations of Generalized Linear Models, Gradient Boosting Machines, Random Forest, Deep Neural Nets, Stacked Ensembles (aka "Super Learners"), dimensionality reduction methods (PCA, GLRM), clustering algorithms (K-means), anomaly detection methods, among others.

We will provide a brief overview of the field of Automatic Machine Learning, followed by a detailed look inside H2O's AutoML algorithm.  H2O AutoML provides an easy-to-use interface which automates data pre-processing, training and tuning a large selection of candidate models (including multiple stacked ensemble models for superior model performance), and due to the distributed nature of the H2O platform, H2O AutoML can scale to very large datasets.  The result of the AutoML run is a "leaderboard" of H2O models which can be easily exported for use in production.  R and Python code with H2O machine learning code examples are available on GitHub for participants to follow along on their laptops. 
