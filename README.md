# Loan Eligibility Prediction using Ensemble Learning

## Overview

This project focuses on predicting loan eligibility for Dream Housing Finance company using an ensemble of machine learning algorithms. The dataset contains customer details such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and more. The goal is to automate the loan eligibility process based on these features, using ensemble learning techniques.

## Dataset

### Source and Objective
The dataset is provided by Dream Housing Finance for the purpose of automating the loan eligibility process. The variables include Loan_ID, Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, and the target variable Loan_Status.

### Data Preprocessing
- Handling missing values and duplicates.
- Encoding categorical variables.
- Scaling numerical features using RobustScaler.
- Splitting the data into training and testing sets.

## Model Training - Individual Models

### Logistic Regression, Decision Tree, SVM
- Training individual models on the preprocessed data.
- Evaluating the performance of each model.

## Model Training - Ensemble Learning

### Hard Voting Classifier
- Combining Logistic Regression, Decision Tree, and SVM using a Hard Voting Classifier.
- Evaluating the ensemble model's performance.

### Soft Voting Classifier
- Combining Logistic Regression, Decision Tree, and SVM using a Soft Voting Classifier.
- Evaluating the ensemble model's performance.

### Bagging Classifier
- Utilizing a Bagging Classifier with a base estimator of RandomForestClassifier.
- Evaluating the Bagging Classifier's performance.

### Gradient Boosting Classifier
- Training a GradientBoostingClassifier and evaluating its performance.

### XGBoost Classifier
- Training an XGBClassifier and evaluating its performance.

### LightGBM Classifier
- Training a LGBMClassifier and evaluating its performance.

### CatBoost Classifier
- Training a CatBoostRegressor for regression tasks.
- Evaluating the CatBoost model's performance.

## Results

- Presenting the classification reports for each model.
- Analyzing the performance of individual models and ensemble methods.

## Additional Libraries

- imbalanced-learn for resampling techniques.
- xgboost, lightgbm, catboost for specialized ensemble models.

## Conclusion

This project demonstrates the application of ensemble learning techniques to predict loan eligibility based on customer details. The combination of individual models through ensemble methods enhances predictive accuracy.

## Disclaimer

The dataset used in this project is a hypothetical scenario created for educational purposes. It does not represent real-world data from Dream Housing Finance.
