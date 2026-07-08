# customer-churn-prediction
Predicting customer churn using Logistic Regression and Random Forest
# Customer Churn Prediction

Predicting whether a telecom customer is likely to churn (leave the service) using historical usage and account data.

## Problem Statement
Customer churn is costly for subscription-based businesses. This project builds a machine learning model to identify customers at risk of churning, so the company can take proactive retention action.

## Dataset
- **Source:** [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- ~7,000 customer records with usage, billing, and demographic features

## Approach
1. Data cleaning (handling missing values, type conversion)
2. Encoding categorical variables
3. Train-test split (80/20)
4. Trained two models: Logistic Regression and Random Forest
5. Evaluated using Accuracy, AUC-ROC, and Classification Report
6. Visualized top features driving churn

## Results
- Random Forest outperformed Logistic Regression on AUC-ROC
- Key churn drivers: contract type, tenure, and monthly charges

## Tech Stack
Python, pandas, scikit-learn, matplotlib

## How to Run
1. Open `untitled0.ipynb` in Google Colab or Jupyter
2. Download the dataset from the Kaggle link above
3. Run all cells in order
