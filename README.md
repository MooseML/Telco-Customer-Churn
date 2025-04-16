# Telco-Customer-Churn
This project predicts customer churn using IBM's Telco dataset and machine learning models like Random Forest, XGBoost, and Logistic Regression. It focuses on data cleaning, feature engineering, and addressing class imbalance with SMOTEENN.
## Table of Contents
- [Overview](#overview)
- [Project Goals](#project-goals)
- [Dataset](#dataset)
- [Methods](#methods)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

---

## Overview
This project focuses on predicting customer churn for a fictional telecom company, Telco. Churn prediction helps subscription-based services identify at-risk customers, enabling proactive retention strategies. The analysis includes:
- Exploratory Data Analysis (EDA)
- Feature engineering to handle categorical and numerical variables
- Addressing class imbalance with SMOTEENN
- Building and evaluating machine learning models

## Project Goals
The primary goal is to build a reliable machine learning model that predicts customer churn and provides actionable insights to reduce turnover.

## Dataset
- **Source:** IBM's Telco Customer Churn Dataset
- **Details:** 
  - 7,043 customer records
  - 21 features including demographics, subscription details, and churn status
- **Key Features:**
  - Numerical: `tenure`, `MonthlyCharges`, `TotalCharges`
  - Categorical: `Contract`, `PaymentMethod`, `InternetService`, etc.

## Methods
1. **Data Cleaning:** Fixed missing values, standardized numerical features, and encoded categorical variables.
2. **Exploratory Data Analysis (EDA):** Investigated patterns and relationships between features and churn.
3. **Feature Engineering:** Addressed multicollinearity and engineered relevant features (e.g., Revenue per Month).
4. **Modeling:** Evaluated multiple machine learning models:
   - Logistic Regression
   - Random Forest
   - XGBoost
   - Voting Classifier (ensemble of models)
5. **Evaluation:** Used metrics like ROC-AUC, recall, F1-score, and confusion matrices to assess model performance.

## Results
- **Best Model:** [Random Forest]
- **Performance:**
  - Accuracy: [0.95]
  - ROC-AUC: [0.99]

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MooseML/Telco-Customer-Churn.git

2. Navigate to the project directory:
   ```bash
   cd Telco-Customer-Churn

3. Install dependencies:
   ```bash
   pip install -r requirements.txt

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook telco_churn_analysis.ipynb
   
2. Follow the steps in the notebook to reproduce the analysis.

## Acknowledgments

- **Dataset:** This project utilizes the [Telco Customer Churn Dataset](https://github.com/IBM/telco-customer-churn-on-icp4d/tree/master/data) provided by IBM.
- The project is inspired by real-world churn analysis for subscription-based services and its applications in improving customer retention strategies.
