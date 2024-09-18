# Stroke-prediction-using-ML

# Project Overview
This project focuses on developing a stroke prediction model using two advanced machine learning techniques: Quadratic Discriminant Analysis (QDA) and Support Vector Machines (SVM). The model is trained and tested on healthcare data to predict the likelihood of a patient having a stroke. The workflow involves data preprocessing, feature selection, model training, and evaluation using cross-validation and ROC-AUC scores.

# Key Features
Data Preprocessing: Handling missing data, standardization, and encoding of categorical features.
Feature Selection: Using statistical techniques (ANOVA F-test) to select the most important features for the model.

# Machine Learning Models:
Quadratic Discriminant Analysis (QDA): Captures different covariance structures between the classes, making it suitable for distinguishing between patients who are at risk of stroke and those who are not.
Support Vector Machines (SVM): A robust classifier that can handle non-linear relationships in the data, providing accurate predictions with high dimensionality.
Model Evaluation: Evaluating model performance using cross-validation and calculating ROC-AUC scores, ensuring the model generalizes well to new, unseen data.

# Installation
Prerequisites
Python 3.x
Libraries:

## pandas
## numpy
## scikit-learn
## matplotlib
