# Predicting-Heart-Failure

## Machine Learning Comparative Investigation

### Dataset Overview

This project uses the "DataClean-fullage.csv" dataset, derived from a larger observational study conducted at the Hero DMC Heart Institute in Ludhiana, Punjab, India. The dataset includes 6,611 observations and 53 variables, capturing detailed patient information, including demographics, medical history, and heart condition data. The dataset was sourced from Kaggle and has undergone preprocessing to remove irrelevant variables and balance the response variable outcomes for heart failure.

### Project Overview

This project investigates the use of supervised and unsupervised machine learning algorithms to predict heart failure and uncover natural clustering patterns within the dataset. The project involves:

Developing and comparing supervised machine learning models, including Logistic Regression and Naive Bayes, to predict heart failure.
Implementing unsupervised machine learning algorithms like Agglomerative Hierarchical Clustering (AHC) and DBSCAN to explore natural clusters related to heart failure.
Utilizing Association Rule Mining (ARM) to identify potential associations between heart failure and other medical conditions in the dataset.
The project concludes that Logistic Regression, optimized through stepwise regression, provided the highest accuracy (99.85%) for predicting heart failure. AHC, particularly using Ward’s method, was the most effective clustering algorithm, revealing distinct clusters that align with known outcomes. However, no significant association rules were discovered through ARM.

### Repository Contents

R Script: The R code used for data preprocessing, model development, and evaluation across supervised, unsupervised, and descriptive machine learning techniques.

Dataset: The "DataClean-fullage.csv" dataset, which includes patient data used for training and testing the models.

Written Report: A detailed report documenting the methodologies, results, and insights gained from the comparative investigation of machine learning models for heart failure prediction.

### Source

The dataset was sourced from Kaggle, specifically from the "Coronary Artery Disease - Analysis" dataset. The data provides a rich resource for studying heart failure and related medical conditions.

