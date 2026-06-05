# Customer Churn Analysis using Python

## Project Overview

This project focuses on analyzing customer churn behavior in a telecom company using Python. The objective is to identify factors contributing to customer churn and generate actionable business insights through Exploratory Data Analysis (EDA), data cleaning, and visualization.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographics, account information, services subscribed, billing details, and churn status.

### Dataset Features

- Customer ID
- Gender
- Senior Citizen Status
- Partner & Dependents
- Tenure
- Internet Service
- Contract Type
- Monthly Charges
- Total Charges
- Payment Method
- Churn Status

Total Records: **7,043 Customers**

---

## Objectives

- Perform data cleaning and preprocessing.
- Identify customer churn patterns.
- Analyze the impact of contract types on churn.
- Analyze the relationship between monthly charges and churn.
- Compare churn rates across internet service categories.
- Generate business insights and recommendations.

---

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

---

## Data Cleaning

The following preprocessing steps were performed:

- Converted `TotalCharges` from string to numeric format.
- Identified missing values.
- Removed records with missing TotalCharges values.
- Validated dataset structure and datatypes.

---

## Exploratory Data Analysis (EDA)

### 1. Customer Churn Distribution

- Overall churn rate: **26.54%**
- Approximately 1 out of every 4 customers left the company.

### 2. Contract Type Analysis

| Contract Type  | Churn Rate |
| -------------- | ---------- |
| Month-to-month | 42.71%     |
| One Year       | 11.28%     |
| Two Year       | 2.85%      |

### 3. Monthly Charges Analysis

| Customer Type      | Average Monthly Charges |
| ------------------ | ----------------------- |
| Retained Customers | $61.31                  |
| Churned Customers  | $74.44                  |

### 4. Internet Service Analysis

| Internet Service | Churn Rate |
| ---------------- | ---------- |
| DSL              | 19.00%     |
| Fiber Optic      | 41.89%     |
| No Internet      | 7.43%      |


### 5. Senior Citizen Analysis

| Customer Group      | Churn Rate |
| ------------------- | ---------- |
| Non-Senior Citizens | 23.65%     |
| Senior Citizens     | 41.68%     |

---

## Visualizations

The project includes visualizations for:

- Customer Churn Distribution
- Churn by Contract Type
- Monthly Charges vs Churn
- Churn by Internet Service
- Senior Citizen Churn Analysis

---

## Key Business Insights


- Customers with month-to-month contracts are significantly more likely to churn compared to customers with long-term contracts.
- Customers paying higher monthly charges tend to leave more frequently.
- Fiber Optic users exhibit the highest churn rate among all internet service categories.
- Senior citizens have a substantially higher churn rate and may require targeted retention strategies.
- Long-term contracts are strongly associated with customer retention.

---

## Business Recommendations

- Introduce incentives for customers to move from month-to-month plans to annual contracts.
- Review pricing and service quality for Fiber Optic customers.
- Develop retention programs targeting senior citizens.
- Offer loyalty discounts for customers with high monthly charges.
- Implement proactive churn prediction and customer engagement initiatives.
