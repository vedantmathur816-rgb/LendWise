# Loan Default Prediction

A machine learning project for predicting whether a borrower is likely to fully repay a loan.

## Overview

This project uses borrower credit and financial information to build a classification model that can support better lending and risk-assessment decisions.

## Workflow

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Train/test split with stratification
- Cross-validation
- Model comparison
- Confusion matrix and classification metrics
- Selection of the best-performing model

## Models

- Decision Tree
- Random Forest
- Gradient Boosting

## Dataset

The dataset contains 9,578 loan records and features related to credit history, income, debt-to-income ratio, FICO score, revolving credit, inquiries, delinquencies, and public records.

The target column is `not.fully.paid`:
- `0` → loan fully paid
- `1` → loan not fully paid

## Result

Gradient Boosting is evaluated against the other models, with particular attention to classification errors and the ability to identify potentially risky loans.

> Model performance depends on the train/test split, preprocessing, and evaluation setup. Results shown in the notebook should be used as the source of truth.

## Tech Stack

**Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · Jupyter Notebook**

## Project Structure

```text
Loan-Default-Prediction/
├── Loan_Default_Prediction.ipynb
├── loan_borrower_data.csv
├── requirements.txt
├── .gitignore
└── README.md
```

## Author

**VEDANT MATHUR**
