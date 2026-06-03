# Financial Fraud Detection Using Machine Learning

## Project Overview

This project investigates the use of machine learning techniques for detecting fraudulent credit card transactions. The objective is to evaluate whether transaction-related features can effectively distinguish fraudulent transactions from legitimate ones.

The analysis includes data preprocessing, exploratory data analysis (EDA), model development, threshold tuning, calibration analysis, cost-based evaluation, and feature importance analysis.

## Dataset

The dataset contains credit card transaction records with the following information:

* Transaction Amount
* Month
* Day of Week
* Weekend Indicator
* Transaction Location
* Transaction Type
* Fraud Label (Target Variable)

## Methodology

### Data Preprocessing

* Missing value inspection
* One-hot encoding of categorical variables
* Train-test split (80:20, stratified)

### Exploratory Data Analysis

* Fraud rate by location
* Fraud rate by transaction type
* Amount distribution by fraud status
* Feature correlation analysis

### Machine Learning Models

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

### Model Evaluation

* Confusion Matrix
* ROC Curve
* Precision-Recall Curve
* Threshold Tuning
* Calibration Analysis
* Cost-Based Analysis

## Key Findings

* Transaction amount distributions were similar for fraud and non-fraud transactions.
* Correlation analysis showed very weak relationships between the target variable and available predictors.
* All classification models achieved limited fraud detection performance.
* Threshold tuning and calibration provided only marginal improvements.
* Cost analysis indicated that missed fraud cases contributed most of the total financial loss.

## Repository Contents

* `Credit_Card_Fraud.ipynb` – Complete analysis notebook
* `report.pdf` – Internship project report
* `*.png` – EDA plots and model evaluation figures

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Author

**Sumana Jana**

Internship Project – Data Science and Analytics
