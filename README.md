# Kaggle Customer Churn Prediction

This project is a binary classification task from Kaggle, focusing on predicting whether a customer will churn.

## Project Overview
The goal of this project is to build a machine learning model to predict customer churn based on customer profile, contract, payment, and service usage information.

## Model
- LightGBM

## Main Work
- Data loading and preprocessing
- Feature engineering
- Cross-validation
- Local parameter tuning
- Final prediction and submission file generation

## Feature Engineering
Some of the engineered features include:
- Service count features
- Contract and payment interaction features
- Tenure-related features
- Charge-related features
- Frequency encoding for selected categorical variables

## Validation Strategy
- Stratified K-Fold Cross Validation
- Evaluation metric: ROC-AUC

## Best Result
- Best 3-fold CV AUC: **0.916146**
- Final 5-fold CV AUC: **0.916376**

## Project Structure
```text
kaggle-customer-churn-prediction/
├── README.md
├── requirements.txt
├── notebooks/
│   └── lgb_fe_tuned_v2.ipynb
└── outputs/
    └── submission_lgb_tuned_fe.csv
