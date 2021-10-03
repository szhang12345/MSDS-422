# Assignment-5-Principal-Components-Analysis-Clustering

Management Problem
From a management perspective, the predictive accuracy of models must be weighed against the costs of model development and implementation. Suppose you were the manager of a data science team responsible for implementing models for computer vision (classification of images analogous to the MINST problem). Would you recommend using PCA as a preliminary to machine learning classification? Explain your thinking.

 
Solution Overview
This exercise uses a random forest learning method for multiclass prediction of handwritten digits in the MNIST dataset. The model techniques use Random Forest Classifier to build model and execute principal components analysis (PCA) on the combined training and test set data together, generating principal components that represent 95 percent of the variability in the explanatory variables. Then rebuild another RFC and Use k-means clustering to group MNIST observations into 1 of 10 categories and then assign labels.
