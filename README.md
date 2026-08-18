# german-credit-risk-prediction
Machine learning model to predict loan default risk using Random Forest with under sampling to hand class imbalance 

## Overview
Built a machine learning model to predict whether a loan applicant is likely to default using Random Forest on real banking data.

## Tools Used
Python, pandas, scikit-learn, matplotlib

## Features
Age, credit amount, duration, job

## Approach
- Handled missing values in Saving accounts and Checking account
- Used .map() to encode binary target variable
- Applied undersampling to address class imbalance (70/30 split)
- Built Random Forest classifier
- Extracted feature importance to identify key default drivers

## Model performance
- Accuracy: 0.67
- Precision (defaulters): when model flagged someone as likely to default, was correct 39% of time.
- Recall (defaulters): the model correctly identified 20% of actual defaulters

## Key Finding
Top predictors of default were credit amount, loan duration, 
and applicant age. Gender was removed from the model due to 
algorithmic bias concerns.
