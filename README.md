# Diabetes_SupervisedML

### Overview
This project aims to utilize supervised machine learning techniques to create models which may predict/determine whether a patient is diabetic or not, granted an array of predictor/explainatory variables. The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 

## Exploratory Data Analysis (EDA)

- Conducted EDA to gain insights on diabetes.csv dataset
- Explored missing values, correlations, data distributions, class imbalances and potential outliers

## Data Preprocessing

- Replaced all zero and or potentially missing information with their categorical means
- Scaled and normalized numeric columns
- Performed addressed imbalanced data

## Machine Learning Models

- Developed Logistic Regression and Random Forest models
- Utilized cross-validation to assess model generalization
- Evaluated model performance utilizing the following metrics:
    - Accuracy, precision, recall, F1-score, and ROC-AUC
- Compared performance of supervised machine learning models

## Findings

- Logistic regression outperformed the random forest model in terms of accuracy, precision and ROC-AUC
    - The random forest model outperformed in terms of recall and F1-score
- Cross-validation results indicated stable performance for both models
- Feature importance analysis was primarily used for the random forest

## Future Goals
- Further hyperparameter tuning and feature selection to further increase metric scores
- Deployment of generated models for real-world predictions