# Task 2 – Titanic Classification (Report)

_Date: November 06, 2025_

## Objective
Build a basic **classification** model (Logistic Regression) on Titanic to predict survival.

## Approach
- Features: `Pclass, Sex, Age, Fare`
- Cleaned missing values; encoded `Sex` (male=0, female=1)
- Split data (80/20) with stratification
- Trained `LogisticRegression` and evaluated accuracy + report

## Key Findings
- `Sex` and `Pclass` are strong predictors.
- The baseline model yields solid accuracy for a simple setup.

## Files
- `Intermediate_Titanic_Model.ipynb`
