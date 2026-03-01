# Employee-Burnout-Risk-Prediction
Employee burnout is a growing concern in modern workplaces, impacting productivity and well-being. 
This project aims to predict the burnout risk score (0–1) of employees using workplace and mental health indicators.
The problem is formulated as a regression task and evaluated using RMSE.
The dataset includes:
- Job role
- Workload level
- Work-life balance score
- Job satisfaction
- Stress level
- Sleep patterns
- Mental health indicators
- ## Exploratory Data Analysis

- Analyzed distribution of burnout scores
- Identified correlation between stress level and burnout
- Observed impact of work-life balance on employee well-being
- - Handled missing values
- Encoded categorical variables
- Scaled numerical features
- Created derived stress index feature
- ## Models Implemented

- Linear Regression
- Random Forest Regressor
- Gradient Boosting / XGBoost
- ## Evaluation Metric

Root Mean Squared Error (RMSE)

Best Model: Random Forest Regressor  
Achieved RMSE: 0.06104
## Key Factors Contributing to Burnout

- High stress level
- Poor work-life balance
- Low job satisfaction
- Long working hours
- ## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- XGBoost
- Employee-Burnout-Risk-Prediction/
│── employee-burnout-prediction.ipynb
│── README.md
│── requirements.txt
1. Clone the repository
2. Install dependencies using requirements.txt
3. Run the Kaggle Notebook
- Hyperparameter tuning using GridSearchCV
- Cross-validation for better generalization
- Deployment using Flask/Streamlit
- Model explainability using SHAP
