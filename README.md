# ML Group2 Work
# Customer Churn Prediction Project

## Project Overview

This project focuses on predicting customer churn in a bank. Using a dataset of customer demographics, finances, and engagement details, we built machine learning models to identify customers at risk of leaving the bank. Early detection of churn allows the bank to take proactive measures to improve retention.

---

## Dataset Description

- **Rows**: ~10,000 bank customers  
- **Target**: `Exited` (1 = churned, 0 = stayed)  
- **Features**:
  - CreditScore
  - Geography
  - Gender
  - Age
  - Tenure
  - Balance
  - NumOfProducts
  - HasCrCard
  - IsActiveMember
  - EstimatedSalary

---

## Installation Instructions

No installation needed if you're using **Google Colab**.  
To run the notebook:

1. Upload the dataset to your **Google Drive**
2. Mount Google Drive in Colab
3. Run each cell step-by-step

---

## Usage Guide

The notebook is split into the following sections:

1. **Data Cleaning**: Drops irrelevant columns, handles categoricals
2. **Preprocessing**: Scales numerical values
3. **Modeling**:
   - Logistic Regression
   - Random Forest
4. **Evaluation**:
   - Accuracy
   - ROC AUC
   - Classification Report
5. **Model Comparison**

---

## Key Findings

- **Random Forest** outperformed Logistic Regression in terms of ROC AUC and accuracy.
- **Age**, **Balance**, and **IsActiveMember** were strong indicators of churn.
- Customers with higher balances who are inactive are most likely to leave.

---

## Future Improvements

- Add more models like **XGBoost** or **LightGBM**
- Perform **hyperparameter tuning** for better performance
- Handle **class imbalance** if dataset becomes skewed
- Add **SHAP analysis** for deeper explainability

---

## Business Impact

By predicting customer churn early, the bank can:
- Target high-risk customers with retention offers
- Improve customer satisfaction and loyalty
- Minimize revenue loss due to unexpected churn

---
