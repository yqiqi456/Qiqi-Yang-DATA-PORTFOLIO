# Customer Churn Prediction

## Project Overview

Customer churn is one of the most critical business problems in subscription-based industries.

This project aims to identify customers who are likely to leave a telecom company and uncover the key factors driving churn.

Using machine learning techniques, I developed a predictive model to support customer retention strategies and reduce revenue loss.

---

## Business Problem

Customer acquisition is significantly more expensive than customer retention.

The objective of this project is to:

- Identify churn risk customers
- Understand churn drivers
- Support retention campaigns
- Improve customer lifetime value

---

## Dataset

Source:

IBM Telco Customer Churn Dataset

Records:

- 7,043 customers

Features:

- Customer demographics
- Contract information
- Internet services
- Payment methods
- Monthly charges
- Total charges

Target Variable:

- Churn (Yes / No)

---

## Data Cleaning

Steps performed:

- Checked missing values
- Converted TotalCharges to numeric
- Removed invalid records
- Encoded categorical variables
- One-Hot Encoding
- Standardisation using StandardScaler

Final dataset:

- 7,032 records
- 30 predictive features

---

## Exploratory Data Analysis

### Overall Churn Rate

26.5%

### Contract Type Impact

| Contract Type | Churn Rate |
|--------------|------------|
| Month-to-month | 42.7% |
| One Year | 11.3% |
| Two Year | 2.8% |

### Monthly Charges

Average Monthly Charges:

- Churned Customers: £74.44
- Retained Customers: £61.27

### Customer Tenure

Average Tenure:

- Churned Customers: 18 Months
- Retained Customers: 38 Months

---

## Machine Learning Model

Model:

Logistic Regression

Train-Test Split:

80% / 20%

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score

---

## Results

Accuracy:

78.7%

Classification Report:

| Metric | Churn |
|----------|----------|
| Precision | 0.62 |
| Recall | 0.52 |
| F1 Score | 0.56 |

Confusion Matrix:

| | Predicted No | Predicted Yes |
|------|------|------|
| Actual No | 915 | 118 |
| Actual Yes | 181 | 193 |

---

## Key Churn Drivers

Factors increasing churn risk:

- Fiber Optic Internet
- High Total Charges
- Streaming Services
- Electronic Check Payment
- Paperless Billing

Factors reducing churn risk:

- Long Tenure
- One-Year Contract
- Two-Year Contract
- Online Security
- Technical Support

---

## Business Recommendations

1. Promote long-term contracts

Customers with two-year contracts showed significantly lower churn rates.

2. Increase customer support adoption

Online Security and Tech Support strongly reduce churn risk.

3. Target high-risk customers

Build retention campaigns for:

- Month-to-month customers
- Fiber optic users
- Electronic check users

---

## Skills Demonstrated

- Python
- Pandas
- NumPy
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Machine Learning
- Logistic Regression
- Model Evaluation
- Business Analytics

---

## Project Structure

```text
Customer-Churn-Prediction
│
├── data
├── notebooks
├── screenshots
├── README.md
└── churn_prediction.py
```
