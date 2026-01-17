# diabetic-readmission-prediction
Predicting 30-day hospital readmission for diabetic patients.
# Diabetic Patient Readmission Prediction

## Problem Statement
Predict 30-day hospital readmission for diabetic patients using EHR data.

## Dataset
UCI Diabetes 130-US Hospitals Dataset (1999–2008)

## Approach
- Data cleaning & feature engineering
- Class imbalance handling
- Model training & evaluation
- Threshold tuning for recall optimization

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest (Final Model)
- XGBoost

## Final Model
Random Forest with class weighting and threshold tuning  
Recall achieved: >70%

## Key Features
- Service utilization
- Discharge disposition
- Number of diagnoses
- Time in hospital

## Business Impact
Early identification of high-risk patients reduces readmission costs.

## Tools
Python, Pandas, Scikit-learn, XGBoost,Random Forest
