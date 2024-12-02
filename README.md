#tesisusfq
<br />
<p align="center">
  <a href="https://github.com/cowdey/tesisusfq.git">
    <img src="images/credit_score_logo.png" alt="Credit Score" height="250">
  </a>

  <h3 align="center">Comparative Evaluation of Machine Learning Models for Credit Score Prediction</h3>

  <p align="center">
    Master's degree thesis project in Data Science at Universidad San Francisco de Quito (USFQ)
    <br />
    <a href="https://github.com/cowdey/tesisusfq.git/issues">Report Bug</a>
    ·
    <a href="https://github.com/cowdey/tesisusfq.git/issues">Request Feature</a>
  </p>
</p>

<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About the Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

## About the Project

This repository contains the code and results of the master's degree project in Data Science entitled **"Comparative Evaluation of Supervised Machine Learning Models for Credit Score Prediction using CACPECO Data."** The main objective of this project is to propose a reproducible supervised learning-based framework for predicting credit scores from internal data, thus minimizing reliance on external credit rating agencies.

Credit scoring is a crucial tool for financial institutions as it allows assessing the creditworthiness of customers. This project addresses the challenges faced by small institutions with limited access to external data. Using real datasets from CACPECO and Lending Club, a robust pipeline was developed including:

- **Data preprocessing:** Label encoding, random oversampling, normalization, and feature selection.
- **Model training:** Evaluation of 7 supervised learning models:
  - Regression: Random Forest Regressor, Linear Regression.
  - Classification: Random Forest Classifier, Support Vector Classifier, K-Nearest Neighbors, Linear Discriminant Analysis, Gaussian Naive Bayes, and Decision Tree Classifier.
- **Hyperparameter optimization:** Using GridSearchCV to maximize model performance.
- **Metrics evaluation:** Regression metrics (MAE, MSE, RMSE, R²) and classification (accuracy, precision, recall, F1 score).

### Built With

- Python3:
  - [scikit-learn](https://scikit-learn.org)
  - [pandas](https://pandas.pydata.org)
  - [matplotlib](https://matplotlib.org)

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- Python 3.8 or later
- Virtual environment manager (e.g., `venv` or `conda`)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/cowdey/tesisusfq.git

2. Navigate to the project directory:   
   cd tesisusfq
   
3. Create and activate a virtual environment (optional but recommended):
   python -m venv env
   source env/bin/activate  # Linux/Mac
   env\Scripts\activate     # Windows
   
4. Install the required packages:
   pip install -r requirements.txt

### Usage
1. Open EDA.ipynb to explore the data analysis process, including data cleaning, visualization, and correlation analysis.
2. Open Models.ipynb to review the machine learning pipeline implementation, model training, and evaluation.

<p align="center"> <a href="https://github.com/cowdey/tesisusfq.git"> <img src="images/pipeline_diagram.png" alt="Pipeline Diagram" height="250"> </a> </p>


### Contact
Ángel David Llerena Camacho - dllerena@estud.usfq.edu.ec

Project Link: https://github.com/cowdey/tesisusfq.git

### Acknowledgements

Universidad San Francisco de Quito (USFQ)
CACPECO for providing the datasets used in this project

