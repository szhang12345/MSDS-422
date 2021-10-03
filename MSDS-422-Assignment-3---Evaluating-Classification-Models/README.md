# MSDS-422-Assignment-3---Evaluating-Classification-Models

# Bank Marketing Study

# Management Problem
Imagine that you are advising the bank about machine learning methods to guide telephone marketing campaigns.
Which of the two modeling methods would you recommend and why? And, given the results of your research, which group of banking clients appears to be the best target for direct marketing efforts (similar to those used with previous telephone campaigns)? 

# Solution Overview
Use three binary explanatory variables relating to client banking history: default, housing, and loan. Predict the binary response variable: Has the client subscribed to a term deposit? Use all banking client observations with complete data for these study variables. Employ two classification methods: (1) logistic regression as described in Chapter 4 of the Géron (2017) textbook and (2) naïve Bayes classification. Evaluate these methods within a cross-validation design, using the area under the receiver operating characteristic (ROC) curve as an index of classification performance. Model techniques include SciKit Learn 'KNeighborsClassifier', 'Naive Bayes' & 'Logistic Regression' as well as cross validation methods such as ROC curve.
