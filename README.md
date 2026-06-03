# Financial Fraud Detection Using Machine Learning

## Project Overview

This project investigates the application of machine learning techniques for detecting fraudulent credit card transactions.

The study evaluates the performance of Logistic Regression, Decision Tree, Random Forest, and XGBoost models using multiple evaluation approaches including threshold tuning, calibration analysis, cost-based analysis, and feature importance analysis.

## Dataset Features

- Transaction Amount
- Month
- Day of Week
- Weekend Indicator
- Transaction Location
- Transaction Type
- Fraud Label (Target Variable)

## Methodology

### Data Preprocessing
- Missing value inspection
- One-hot encoding of categorical variables
- Train-test split (80:20)

### Exploratory Data Analysis
- Fraud rate by location
- Fraud rate by transaction type
- Amount distribution analysis
- Correlation analysis

### Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### Evaluation Techniques
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- Threshold Tuning
- Calibration Analysis
- Cost Analysis
- Feature Importance

## Key Findings

- Transaction amount showed limited separation between fraud and non-fraud transactions.
- Correlations between predictors and the fraud label were generally weak.
- All models demonstrated limited fraud detection capability.
- Threshold tuning and calibration produced only marginal improvements.
- Cost analysis indicated that missed fraud cases contributed most of the overall financial loss.
- Feature importance analysis identified transaction amount as the most influential variable.

## Repository Structure

- `Credit_Card_Fraud.ipynb` : Complete project notebook
- `Credit_Card_Fraud_Detection_Report.pdf` : Final internship report
- `*.png` : EDA and model evaluation figures

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Author

**Sumana Jana**

Internship Project – Data Science and Analytics

### Project Mentors / Team Members

- Ameya
- Govind
- P D Manoj
- Rahul Reddy
- Swaroop Ambati
