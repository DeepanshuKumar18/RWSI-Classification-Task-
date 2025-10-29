---
#  Retail Web Sales Insights (RWSI) Project

The **RWSI (Retail Web Sales Insights)** project focuses on analyzing and predicting customer behavior in an online sales dataset.  
The main goal is to predict whether a customer will **convert monetarily (make a purchase)** based on various demographic, transactional, and behavioral features.

This project uses **Machine Learning** classification algorithms — Logistic Regression, Random Forest, and XGBoost — to build a robust model that identifies conversion patterns and helps improve marketing strategies.

---

##  Overview
This repository contains the Jupyter notebook **`RWSI.ipynb`**, which performs:

- Exploratory Data Analysis (EDA)  
- Data preprocessing and encoding  
- Feature engineering  
- Model training and evaluation  

The project aims to identify factors affecting **Monetary Conversion** in the dataset.

---

##  Project Details
| Component | Description |
|------------|-------------|
| **Dataset File** | `rwsi_data.csv` |
| **Target Column** | `MonetaryConversion` |
| **Task Type** | Classification |
| **Models Used** | Logistic Regression, Random Forest, XGBoost |
| **Metrics** | Accuracy, F1-Score, Confusion Matrix |
| **Libraries** | pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, imblearn |

---

##  Workflow
1. **Data Loading:** Read the dataset using pandas.  
2. **Preprocessing:** Handle missing values, remove duplicates, and encode categorical columns.  
3. **Feature Engineering:** Separate numerical and categorical features.  
4. **Model Training:** Train and compare Logistic Regression, Random Forest, and XGBoost models.  
5. **Evaluation:** Evaluate using Accuracy, F1-Score, and Confusion Matrix.

---


