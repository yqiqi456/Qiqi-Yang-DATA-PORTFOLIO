# Customer Churn Prediction

## Project Overview

This project develops a machine learning model to predict customer churn for a telecommunications company.

The objective is to identify customers at risk of leaving and uncover the key business drivers behind churn behaviour.

Using Logistic Regression, the model predicts customer churn and provides actionable retention insights.

---

## Business Problem

Customer acquisition is significantly more expensive than customer retention.

The business wants to:

- Predict customers likely to churn
- Understand churn drivers
- Improve customer retention
- Reduce revenue loss

---

## Dataset

Source:
Telco Customer Churn Dataset

Records:
7,043 customers

Target Variable:
Churn (Yes / No)

Features:

- Customer demographics
- Contract type
- Payment methods
- Internet services
- Monthly charges
- Tenure

---

## Data Cleaning

Steps performed:

- Removed customerID
- Converted TotalCharges to numeric
- Removed missing values
- Encoded target variable
- Applied One-Hot Encoding
- Standardised numerical features

---

## Machine Learning Model

Algorithm:

- Logistic Regression

Train-Test Split:

- 80% Training
- 20% Testing

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score

---

## Model Performance
