# Neural-Network

## Overview
In this project, I created a deep learning neural network to analyze donation data to provide insights on effectiveness of donations.
1. Import, analyze, clean, and preprocess a “real-world” classification dataset.
2. Select, design, and train a binary classification model of your choosing.
3. Optimize model training and input data to achieve desired model performance.

## Analysis Overview
I used three layers. Input layer with two hidden layers. Having 2-3 times the amount of neurons in the hidden layer as the number of inputs is suggested.
## Steps
1. Combine rare categorical via bucketing
2. Encode categorical variables using one-hot encoding
3. Standardize numerical variables using TensorFlow's StandardScaler class.
 
 ## Summary
A binary classifier that is capable of predicting whether or not an applicant will be successful if funded by Alphabet Soup using the features collected in the provided dataset is created.

## Rcommendation
I would use Random Frorest Classifiers as an alternative to solve the classification problem. This model combines multiple smaller models into a more robust and accurate model.It has the advantage in robustness and scalability. The data would be easy to be transformed and fit into this model. Overall, it would be more effificnet.
