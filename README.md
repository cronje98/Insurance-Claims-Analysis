# Insurance-Claims-Analysis
Insurance Claims Cost Prediction and Business Intelligence Dashboard (Python + Excel + Machine Learning)

This project analyzes insurance claims data to identify key drivers of medical costs and build a predictive model using machine learning. It also includes an interactive Excel dashboard for business reporting.

The goal is to combine Python-based analytics, machine learning, and Excel BI tools to simulate a real-world insurance analytics workflow.

# DATASET
index	
PatientID	
age	
gender	
bmi	
bloodpressure	
diabetic	
children	
smoker		
region
Claims (target variable)

# Tools & Technologies
Python (Pandas, NumPy)
Matplotlib & Seaborn
Scikit-learn
Excel (Pivot Tables, Charts, Slicers)
Jupyter Notebook

===========================

# Machine Learning Model

Model Performance:
Linear Regression
R² (Test): 0.73
Dataset size: 1,333 observations

<img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/0d6a41e3-e837-42a1-a9a1-79035f1ea173" />

# Smoking status had the largest positive coefficient, indicating the strongest association with increased insurance claim costs in the fitted model. BMI, blood pressure, and the number of children( now also visible) also showed positive associations. Regional variables and gender had comparatively smaller effects.

===========================

# Excel Dashboard

An interactive Excel dashboard was built featuring:

KPI cards (Total cases, Avg claims, % smokers)
Pivot charts (Smoker, BMI, Age analysis)
Interaction analysis (Smoker × BMI)
Slicers (Smoker, Gender, Age)

# Dashboard Preview
<img width="928" height="326" alt="Screenshot 2026-07-02 163130" src="https://github.com/user-attachments/assets/900155e5-40ab-4e93-9a59-623341629467" />

================================================================

# Key insights (EDA):
-->Smokers incur significantly higher insurance charges
-->BMI has a strong positive relationship with claims
-->Interaction effects exist between smoking and BMI
=








