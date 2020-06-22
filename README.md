# Advanced Methods in Data Analysis

*Instructor: Alejandro Correa Bahnsen*

- email: <al.bahnsen@gmail.com>
- twitter: [@albahnsen](https://twitter.com/albahnsen)
- github: [albahnsen](http://github.com/albahnsen)


The use of statistical models in computer algorithms allows computers to make decisions and predictions, and to perform tasks that traditionally require human cognitive abilities. Machine learning is the interdisciplinary field at the intersection of statistics and computer science which develops such algorithms and interweaves them with computer systems. It underpins many modern technologies, such as speech recognition, internet search, bioinformatics, computer vision, Amazon’s recommender system, Google’s driverless car and the most recent imaging systems for cancer diagnosis are all based on Machine Learning technology.

This course on Time Series Analysis, Machine Learning and Natural Language Processing  will explain how to build systems that learn and adapt using real-world applications. Some of the topics to be covered include time series analysis, machine learning, python data analysis, natural language processing models and recurrent models. The course will be project-oriented, with emphasis placed on writing software implementations of learning algorithms applied to real-world problems, in particular, churn modeling, natural language processing, sentiment detection, among others.


## Requiriments 
* [Python](http://www.python.org) version 3.7;
* [Numpy](http://www.numpy.org), the core numerical extensions for linear algebra and multidimensional arrays;
* [Scipy](http://www.scipy.org), additional libraries for scientific programming;
* [Matplotlib](http://matplotlib.sf.net), excellent plotting and graphing libraries;
* [IPython](http://ipython.org), with the additional libraries required for the notebook interface.
* [Pandas](http://pandas.pydata.org/), Python version of R dataframe
* [Seaborn](stanford.edu/~mwaskom/software/seaborn/), used mainly for plot styling
* [scikit-learn](http://scikit-learn.org), Machine learning library!

A good, easy to install option that supports Mac, Windows, and Linux, and that has all of these packages (and much more) is the [Anaconda](https://www.continuum.io/).

GIT!! Unfortunatelly out of the scope of this class, but please take a look at these [tutorials](https://help.github.com/articles/good-resources-for-learning-git-and-github/)

## Evaluation

* 75% Projects (3 projects, 25% each)
* 15% Exercises
* 10% Class participation


## Schedule

### Time Series Analysis
| Date | Session         | Notebooks/Presentations          | Exercises |
| :----| :----| :------------- | :------------- | 
| June 16th | ARIMA Processes | <ul><li>[1 - Intro to TSA](https://nbviewer.jupyter.org/github/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/01-IntroTSA.ipynb) </li> <li>[2 - ARIMA processes](https://nbviewer.jupyter.org/github/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/02-ARIMA.ipynb) </li></ul> | <ul><li>[E1 - TSA Applications](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E1%20-%20Examples%20TSA.md) </li><li>[E2 - Python TSA Analysis](https://nbviewer.jupyter.org/github/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E02-TSA.ipynb) </li> <li>[E3 - ARIMA](https://nbviewer.jupyter.org/github/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E03-ARIMA.ipynb) </li> </ul> | 
| June 18th | Working with TSA | <ul><li>[3 - Prophet](https://nbviewer.jupyter.org/github/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/03-TSA-prophet.ipynb) </li> </ul> |   <ul><li>[E4 - Panel Data](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E04%20-%20Panel%20Data.md) </li> <li>[E5 - Prophet](https://nbviewer.jupyter.org/github/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E05-prophet.ipynb) </li> <li>[P1 - TSA](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/P1-TSL.md) </li> </ul>| 

### Machine Learning Systems
| Date | Session         | Notebooks/Presentations          | Exercises |
| :----| :----| :------------- | :------------- | 
| June 23rd | Decision Trees & Ensembles | <ul><li>[4 - Decision Trees](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/04-DecisionTrees.ipynb) </li> <li>[5 - Bagging](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/05-Ensembles_Bagging.ipynb) </li></ul>| <ul><li>[E6 - DT](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E06%20-%20Decision%20Trees%20Overview.md) </li> <li>[E7 - DT & Ensembles](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E7-DecisionTrees_Bagging.ipynb) </li></ul> | 
| June 24th | Random Forest and XGBoost | <ul><li>[6 - Random Forests](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/06-Ensembles_RandomForest.ipynb) </li> <li>[7 - XGBoost](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/07-Ensembles_Boosting.ipynb) </li></ul>| <ul><li>[E8 - Ensembles](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E08%20-%20Ensembles%20Trees%20Overview.md) </li> <li>[E9 - Random Forest & Gradient Boosting](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E8-RandomForests_Boosting.ipynb) </li></ul> | 
| June 25th | Machine Learning as a Service  |  <ul><li>[8 Introduction to Rest APIs](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/08-IntroductionToAPIs.ipynb) </li> <li>[9 - Model Deployment](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/09-Model_Deployment.ipynb) </li> <li>[10 - APIs in AWS](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/notebooks/10-CreatingAPIinAWS.ipynb) </li></ul> | <ul><li>[E10 - API Review](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/E10%20-%20microservices.md) </li> <li>[P2 - Trees and APIs](https://github.com/albahnsen/AdvancedMethodsDataAnalysisClass/blob/master/Exercises/P2-UsedVehiclePricePrediction.ipynb) </li></ul> | 

 ### Natural Language Processing
| Date | Session         | Notebooks/Presentations          | Exercises |
| :----| :----| :------------- | :------------- | 
| June 30th | Natural Language Processing  |  <ul><li>[11 - Introduction to NLP]() </li></ul> <ul><li>[12 - Introduction to NLP II ]() </li></ul> | <ul><li>[E12 - NLP Review]() </li><li>[E13 - Sentiment Analysis]() </li> </ul> | 
| July 1st |  Sentiment Analysis | <ul><li>[13 - Sentiment Analysis]() </li></ul> | <ul><li>[E14 - Homeworks Analysis]() </li>  </ul> |
| July 2nd |  NLP using Neural Networks | <ul><li>[14 - Introduction to NN - MLP]() </li><li>[15 - LSTM]() </li></ul> | <ul> <li>[P3 - NLP Movies Analysis API]() </li> </ul> |





