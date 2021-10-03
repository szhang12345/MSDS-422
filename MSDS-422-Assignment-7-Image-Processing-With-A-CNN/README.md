# MSDS-422-Assignment-7-Image-Processing-With-A-CNN

# Management Problem
Assume that we are providing advice to a website provider who is looking for tools to automatically label images provided by end users. As we look across the factors in the study, making recommendations to management about image classification, we are most concerned about achieving the highest possible accuracy in image classification. That is, we should be willing to sacrifice training time for model accuracy. What type of machine learning model works best? If it is a convolutional neural network, what type of network should we use? Part of this recommendation may concern information about the initial images themselves (input data for the classification task). What types of images work best?

# Solution Overview
Employ at least a 2x2 completely crossed experimental design for Cats vs Dogs classification project. A train-test-validation regimen is used in this assignment and convolutional neural networks (CNNs) within Python TensorFlow is utilized.
The steps for the analysis are the following:
1) Shuffle and resize the data and split it into training, test and validation data sets.
2) Using the best performance model from assignment 6 ‘DNN’ technique as the baseline model, 2 hidden layers with 100 nodes per layer.
3) Apply ‘CNN ‘method for filtering and processing images, 2 and 3 conv layers with color or grayscale are used.
4) Compare the model timing and accuracy.
