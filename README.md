# FOAR-705

#Digital humanities proof of concept: Understanding Online Chat with Sentiment Analysis 

##Background

This project was put together as part of the FOAR705 -- Digital Humanities -- masters level course at Macquarie University (Sydney, Australia). It is a proof of concept, attempting to use a combination of machine and lexicon based approaches to sentiment analysis to extract data from the live chat of a Twitch broadcast. 

Summation of R packages utilized primarily in this project

#cleaning package 
library(tm) - https://cran.r-project.org/web/packages/tm/index.html
A framework for text mining applications within R.

#data visualization in R 
library(ggplot2) - http://ggplot2.org/
ggplot2 is a plotting system for R

#lexicon analysis 
library(syuzhet) - https://cran.r-project.org/web/packages/syuzhet/index.html
Extracts sentiment and sentiment-derived plot arcs from text using three sentiment dictionaries conveniently packaged for consumption by R users.

#importing large data into R
library(data.table) - https://cran.r-project.org/web/packages/data.table/index.html
Fast aggregation of large data (e.g. 100GB in RAM), fast ordered joins, fast add/modify/delete of columns by group using no copies at all, list columns, a fast friendly file reader and parallel file writer.

#text classificaiton and evaluation 
library(RWeka) - https://cran.r-project.org/web/packages/RWeka/index.html
Weka is a collection of machine learning algorithms for data mining tasks written in Java, containing tools for data pre-processing, classification, regression, clustering, association rules, and visualization.

#word stemming
library(SnowballC) - https://cran.r-project.org/web/packages/SnowballC/index.html
An R interface to the C libstemmer library that implements Porter's word stemming algorithm for collapsing words to a common root to aid comparison of vocabulary

#classification and regression training 
library(caret) - https://cran.r-project.org/web/packages/caret/index.html
Misc functions for training and plotting classification and regression models.

#classification 
library(rminer) - https://cran.r-project.org/web/packages/rminer/index.html
Facilitates the use of data mining algorithms in classification and regression (including time series forecasting) tasks by presenting a short and coherent set of functions.

#support vector machine classifier 
library(kernlab) - https://cran.r-project.org/web/packages/kernlab/index.html
Kernel-based machine learning methods for classification, regression, clustering, novelty detection, quantile regression and dimensionality reduction.

#classification and regression
library(rpart) - https://cran.r-project.org/web/packages/rpart/index.html
Recursive partitioning for classification, regression and survival trees.

DATA VISUALIZATION 

http://wordcram.org/

WordCram lets you generate word clouds in Processing. It does the heavy lifting – text analysis, collision detection – for you, so you can focus on making your word clouds as beautiful, as revealing, or as silly as you like.






