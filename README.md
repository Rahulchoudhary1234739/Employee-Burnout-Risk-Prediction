# Employee Burnout Risk Prediction using Machine Learning

## 📌 Overview
Employee burnout is a growing concern in modern workplaces, affecting productivity, employee well-being, and retention. This project aims to predict the burnout risk score (0–1) of employees using machine learning regression techniques based on workplace and mental health indicators.

This project was developed as part of a college-hosted Kaggle competition.

---

## 🎯 Problem Statement
Given anonymized employee data including job role, workload, stress level, work-life balance, sleep patterns, and mental health indicators, the objective is to build a regression model to accurately predict the burnout score.

- Problem Type: Regression
- Target Variable: `burnout_score` (Continuous value between 0 and 1)
- Evaluation Metric: Root Mean Squared Error (RMSE)

---

## 📊 Dataset Features
The dataset includes:

- Job Role
- Workload Level
- Work-Life Balance Score
- Job Satisfaction
- Stress Level
- Sleep Hours
- Mental Health Indicators
- Demographic Information (Anonymized)

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Feature scaling (if applied)
- Removed outliers (if applicable)

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of burnout score
- Correlation heatmap
- Relationship between stress and burnout
- Impact of work-life balance on burnout

### 3️⃣ Models Implemented
- Linear Regression
- Random Forest Regressor
- Gradient Boosting / XGBoost (if used)

---

## 📈 Model Evaluation

Evaluation Metric: **RMSE (Root Mean Squared Error)**

Best Model: *[Replace with your best model name]*  
Achieved RMSE: *[Replace with your score]*

Lower RMSE indicates better predictive performance.

---

## 🔍 Key Insights

- High stress levels strongly correlate with burnout
- Poor work-life balance significantly increases burnout risk
- Low job satisfaction contributes to higher burnout score
- Sleep patterns impact mental fatigue levels

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost (if used)

---

## 📁 Project Structure

Employee-Burnout-Risk-Prediction/
│── employee-burnout-prediction.ipynb  
│── README.md  
│── requirements.txt  

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
