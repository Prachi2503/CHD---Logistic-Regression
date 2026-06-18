# CHD---Logistic-Regression
Logistic Regression from scratch for predicting 10-year Coronary Heart Disease (CHD) risk using the Framingham dataset.
# Logistic Regression for Coronary Heart Disease (CHD) Prediction

## Project Overview

This project implements Logistic Regression from scratch using Python and NumPy to predict the 10-year risk of Coronary Heart Disease (CHD) using the Framingham Heart Study dataset.

The objective is to build and evaluate a binary classification model capable of identifying individuals at risk of developing CHD based on demographic, lifestyle, and clinical health indicators.

## Dataset

The dataset contains patient information including:

* Gender
* Age
* Education
* Smoking status
* Cigarettes per day
* Blood pressure medication usage
* History of stroke
* Hypertension
* Diabetes
* Total cholesterol
* Systolic blood pressure
* Diastolic blood pressure
* BMI
* Heart rate
* Glucose level

Target Variable:

* TenYearCHD

  * 1 = Patient develops CHD within 10 years
  * 0 = No CHD within 10 years

## Project Workflow

1. Data Cleaning and Preprocessing
2. Feature Normalization
3. Train/Test Split
4. Logistic Regression Implementation from Scratch
5. Gradient Descent Optimization
6. Model Evaluation
7. Confusion Matrix Analysis
8. ROC Curve and AUC Analysis
9. Threshold Tuning
10. New Patient Risk Prediction

## Model Performance

### Default Threshold (0.50)

* Test Accuracy: 85.5%
* Recall: 7.0%
* F1 Score: 0.128

Although the model achieved high accuracy, it identified only a small percentage of actual CHD cases due to class imbalance.

### ROC Analysis

* AUC: 0.76

The ROC curve indicates that the model has reasonable discriminatory power and is capable of distinguishing between CHD and non-CHD patients.

### Threshold Optimization

Threshold tuning was performed to improve the balance between Precision and Recall.

* Best Threshold: 0.23
* Best F1 Score: 0.423

Lowering the classification threshold significantly improved the model's ability to identify patients at risk of CHD.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

## Key Learning Outcomes

* Logistic Regression implementation from scratch
* Feature normalization
* Gradient Descent optimization
* Model evaluation using Accuracy, Precision, Recall, and F1 Score
* Confusion Matrix interpretation
* ROC Curve and AUC analysis
* Threshold tuning for imbalanced datasets

## Author

Prachi Patel
