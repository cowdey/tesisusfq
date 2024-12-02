<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comparative Evaluation of Machine Learning Models for Credit Score Prediction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            color: #333;
        }
        h1, h2, h3 {
            color: #0056b3;
        }
        ul {
            margin: 10px 0;
            padding-left: 20px;
        }
        li {
            margin-bottom: 5px;
        }
        .section {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <h1>Comparative Evaluation of Machine Learning Models for Credit Score Prediction</h1>
    <p>
        This repository contains the code and results of the master's degree project in Data Science entitled
        <strong>"Comparative Evaluation of Supervised Machine Learning Models for Credit Score Prediction using CACPECO Data."</strong>
        The main objective of the work is to propose a reproducible supervised learning-based framework for predicting credit scores from internal data, 
        thus minimizing reliance on external credit rating agencies.
    </p>

    <div class="section">
        <h2>Project Overview</h2>
        <p>
            Credit scoring is a crucial tool for financial institutions, as it allows assessing the creditworthiness of customers. 
            This project addresses the challenges faced by small institutions with limited access to external data. Using real datasets from CACPECO and Lending Club, 
            a robust pipeline was developed including:
        </p>
        <ul>
            <li><strong>Data preprocessing:</strong> Label encoding, random oversampling, normalization, and feature selection.</li>
            <li><strong>Model training:</strong> Evaluation of 7 supervised learning models:
                <ul>
                    <li>Regression: Random Forest Regressor, Linear Regression.</li>
                    <li>Classification: Random Forest Classifier, Support Vector Classifier, K-Nearest Neighbors, Linear Discriminant Analysis, Gaussian Naive Bayes, and Decision Tree Classifier.</li>
                </ul>
            </li>
            <li><strong>Hyperparameter optimization:</strong> Using GridSearchCV to maximize model performance.</li>
            <li><strong>Metrics evaluation:</strong> Regression metrics (MAE, MSE, RMSE, R²) and classification (accuracy, precision, recall, F1 score).</li>
        </ul>
    </div>

    <div class="section">
        <h2>Key Findings</h2>
        <ul>
            <li><strong>Top Models:</strong></li>
            <ul>
                <li>Regression: Random Forest Regressor (R² = 0.94).</li>
                <li>Classification: Gaussian Naive Bayes and Linear Discriminant Analysis with balanced metrics.</li>
            </ul>
            <li><strong>Impact:</strong> This approach enables resource-constrained institutions to perform reliable creditworthiness assessments using their internal data.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Repository Structure</h2>
        <h3>1. Exploratory Data Analysis (EDA.ipynb)</h3>
        <ul>
            <li>Initial data cleaning and visualization.</li>
            <li>Exploratory analysis to understand correlations between variables.</li>
            <li>Identification of outliers and class balancing.</li>
        </ul>

        <h3>2. Model Training and Evaluation (Models.ipynb)</h3>
        <ul>
            <li>Implementation of the machine learning pipeline.</li>
            <li>Training and evaluation of the models.</li>
            <li>Comparison of metrics to select the best approaches.</li>
        </ul>
    </div>
</body>
</html>
