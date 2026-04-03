# Customer Churn Project

## Overview:
This project is investigating customer churn using the machine learning technique called Random Forest. 
The aim is to classify whether a customer is likely to churn or not based on features from the Telco Customer Churn dataset.

## Project Aim
The main objectives of the project are:
- build a baseline machine learning model using AI-generated code
- identify weaknesses in the generated code
- improve the code step by step
- justify each improvement
- evaluate the final model against the original baseline
- reflect on the strengths and weaknesses of AI-assisted coding

## Machine Learning Task
This is a supervised binary classification problem.
- Target variable: `Churn`
- Classes: churn / no churn
The initial baseline model uses a Random Forest Classifier.

## Iteration Strategy
2. replacing missing-value deletion with imputation
3. introducing a preprocessing pipeline
4. using `ColumnTransformer`
5. comparing against Logistic Regression
6. adding cross-validation
7. including ROC-AUC
8. performing hyperparameter tuning
