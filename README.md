# Hackerstreet-Prediction-of-Heart-Disease-Using-Ml-Algorithim-
Created by:Team  Terminal Stack

TOOL DEVELOPMENT
The full code for this article can be found here. It is implemented in Python and different classification algorithms are used. Below is a brief description of the general approach that I employed:

Data cleaning and pre-processing: Here I checked and dealt with missing and duplicate variables from the data set as these can grossly affect the performance of different machine learning algorithms (many algorithms do not tolerate missing data).
Exploratory Data Analysis: Here I wanted to gain important statistical insights from the data and the things that I checked for were the distributions of the different attributes, correlations of the attributes with each other and the target variable and I calculated important odds and proportions for the categorical attributes.
Feature Selection: Since having irrelevant features in a data set can decrease the accuracy of the models applied, I used the Boruta Feature Selection technique to select the most important features which were later used to build different models.
Model development and comparison: I used four classification models, i.e., Logistic Regression, K-Nearest Neighbors, Decision Trees and Support Vector Machine, After which I compared the performance of the models using their accuracy and F1 scores. I then settled with the best performing model.
