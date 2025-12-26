# Telecom Customer Churn Analysis & Prediction

## Project Overview
Customer churn is a major challenge for telecom companies as retaining customers is more cost-effective than acquiring new ones.  
This project focuses on analyzing customer behavior, identifying key churn drivers through Exploratory Data Analysis (EDA) and building machine learning models to predict customer churn.

---

## Objectives
- Analyze customer demographics and service usage patterns  
- Perform Exploratory Data Analysis (EDA) to understand churn behavior  
- Build and evaluate machine learning models for churn prediction  
- Derive actionable business insights to reduce customer churn  

---

## Dataset Description
The dataset contains customer-level information including:
- Demographics: Gender, Age, Senior Citizen  
- Account information: Tenure, Contract Type, Payment Method  
- Services subscribed: Internet Service, Tech Support, Streaming  
- Billing details: Monthly Charges, Total Charges  
- Target variable: **Churn (Yes / No)**  

---

## Exploratory Data Analysis (EDA)
EDA was performed to uncover patterns and trends related to customer churn:
- Churn distribution across different customer segments  
- Impact of contract type, tenure, and payment method on churn  
- Relationship between monthly charges and churn  
- Univariate and bivariate analysis using visualizations  

### Key Insights
- Customers with **month-to-month contracts** show higher churn rates  
- **Short-tenure customers** are more likely to churn  
- Absence of **tech support and online security** increases churn  
- Higher monthly charges are associated with increased churn  

---

## Data Preprocessing
- Handled missing and inconsistent values  
- Encoded categorical variables  
- Scaled numerical features where required  
- Split data into training and testing sets  

---

## Model Building
The following machine learning models were implemented:
- Decision Tree  
- Random Forest  

---

## Model Evaluation
Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix   

**Best Performing Model:**  
Random Forest (based on overall balanced performance)

---

## 🧰 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

