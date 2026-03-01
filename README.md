# Employee Burnout Risk Prediction using Machine Learning

## Overview

Employee burnout is a critical issue in modern workplaces, impacting productivity, employee well-being, and organizational performance. This project focuses on predicting the burnout risk score of employees using machine learning regression models based on anonymized workplace and mental health data.

This project was developed as part of a college-hosted Kaggle competition centered around HR analytics and predictive modeling.

---

## Problem Statement

Given employee-level data containing job role, workload, stress levels, work-life balance, sleep patterns, and other well-being indicators, the objective is to build a regression model that accurately predicts the burnout score.

Problem Type: Regression  
Target Variable: burnout_score (continuous value between 0 and 1)  
Evaluation Metric: Root Mean Squared Error (RMSE)

---

## Dataset Description

The dataset consists of anonymized employee information, including:

- Job role and department  
- Workload level and working conditions  
- Work-life balance score  
- Job satisfaction level  
- Stress level indicators  
- Sleep and mental health related features  
- Demographic attributes (anonymized)  

Two datasets were provided:

- Training dataset (with burnout_score)  
- Test dataset (without burnout_score)  

---

## Machine Learning Workflow

### 1. Data Preprocessing

- Loaded training and test datasets  
- Handled missing values  
- Applied Label Encoding to categorical features  
- Ensured consistent preprocessing between train and test sets  
- Set RANDOM_SEED = 42 for reproducibility  

### 2. Cross Validation Strategy

- Implemented KFold Cross Validation  
- Evaluated models using RMSE across folds  
- Reduced overfitting and improved generalization  

---

## Models Implemented

The following regression models were trained and evaluated:

- Ridge Regression  
- ExtraTreesRegressor  
- LightGBM Regressor  
- CatBoost Regressor  

An ensemble/stacking approach was used to combine predictions from multiple models for improved performance.

---

## Model Evaluation

Evaluation Metric: Root Mean Squared Error (RMSE)

Lower RMSE indicates better predictive accuracy.

Best Model: Replace with your best model name  
Final RMSE Score: Replace with your final score  

---

## Key Insights

- Higher stress levels significantly increase burnout risk  
- Poor work-life balance strongly correlates with higher burnout scores  
- Job satisfaction has a noticeable inverse relationship with burnout  
- Ensemble methods improve performance compared to individual models  

---

## Tech Stack

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- LightGBM  
- CatBoost  
- Jupyter Notebook  

---

## Project Structure

Employee-Burnout-Risk-Prediction/
│── employee-burnout-prediction.ipynb  
│── README.md  
│── requirements.txt  

---

## How to Run the Project

1. Clone the repository  
2. Install dependencies using:

   pip install -r requirements.txt  

3. Open the notebook and run all cells  

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV or Optuna  
- More advanced stacking strategies  
- Feature importance analysis  
- Model explainability using SHAP  
- Deployment using Streamlit or Flask  

---

## Author

Rahul Choudhary  
B.Tech CSE (Data Science)  
ABES Engineering College  
