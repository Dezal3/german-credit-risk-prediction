# german-credit-risk-prediction
Machine learning model to predict loan default risk using Random Forest with under sampling to hand class imbalance 

## Overview
Built a machine learning model to predict whether a loan applicant 
is likely to default using Random Forest on real banking data.

## Tools Used
Python, pandas, scikit-learn

## Approach
- Handled missing values in Saving accounts and Checking account
- Used .map() to encode binary target variable
- Applied undersampling to address class imbalance (70/30 split)
- Built Random Forest classifier
- Extracted feature importance to identify key default drivers

## Results
- Accuracy: 0.59
- Precision: 0.57
- Recall: 0.66
- F1 Score: 0.61

## Key Finding
Top predictors of default were credit amount, loan duration, 
and applicant age. Gender was removed from the model due to 
algorithmic bias concerns.
