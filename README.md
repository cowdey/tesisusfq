# tesisusfq

Comparative Evaluation of Machine Learning Models for Credit Score Prediction

This repository contains the code and results of the master's degree project in Data Science entitled "Comparative Evaluation of Supervised Machine Learning Models for Credit Score Prediction using CACPECO Data." The main objective of the work is to propose a reproducible supervised learning-based framework for predicting credit scores from internal data, thus minimizing reliance on external credit rating agencies.

Credit scoring is a crucial tool for financial institutions, as it allows assessing the creditworthiness of customers. This project addresses the challenges faced by small institutions with limited access to external data. Using real datasets from CACPECO and Lending Club, a robust pipeline was developed including:

Data preprocessing: Label encoding, random oversampling, normalization, and feature selection.
Model training: Evaluation of 7 supervised learning models:
Regression: Random Forest Regressor, Linear Regression.
Classification: Random Forest Classifier, Support Vector Classifier, K-Nearest Neighbors, Linear Discriminant Analysis, Gaussian Naive Bayes, and Decision Tree Classifier.
Hyperparameter optimization: Using GridSearchCV to maximize model performance.
Metrics evaluation: Regression metrics (MAE, MSE, RMSE, R²) and classification (accuracy, precision, recall, F1 score).

Key Findings

Top Models:
Regression: Random Forest Regressor (R² = 0.94).
Classification: Gaussian Naive Bayes and Linear Discriminant Analysis with balanced metrics.
Impact: This approach enables resource-constrained institutions to perform reliable creditworthiness assessments using their internal data.

Repository Structure
1. Exploratory Data Analysis (EDA.ipynb)

Contains:

Initial data cleaning and visualization.
Exploratory analysis to understand correlations between variables.
Identification of outliers and class balancing.

2. Model Training and Evaluation (Models.ipynb)

Includes:

Implementation of the machine learning pipeline.
Training and evaluation of the models.
Comparison of metrics to select the best approaches.
