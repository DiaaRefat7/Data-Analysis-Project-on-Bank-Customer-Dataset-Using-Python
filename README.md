# 🏦 Credit Card Customers - EDA & Churn Analysis

## 📌 Overview
This project explores a credit card customers dataset to analyze **customer behavior, demographics, transactions, and attrition (churn)** patterns.  
The main goal is to identify key factors behind customer attrition and provide **data-driven recommendations** to improve retention strategies.

---

## 📊 Dataset
Source: [Kaggle - Credit Card Customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

- **Rows:** 10,127 customers  
- **Columns:** 21 features  
- **Target Variable:** `Attrition_Flag` (Existing / Attrited customer)

Main features include:
- Demographics: Gender, Age, Education, Marital Status, Income  
- Credit card details: Credit limit, Total transaction count, Utilization ratio  
- Customer behavior: Inactive months, Contacts with bank, Dependent count  

---

## 🔎 Exploratory Data Analysis (EDA)
EDA focused on:
- **Distribution of Attrition**
- **Demographic analysis** (Gender, Age, Marital status, Education, Income)
- **Transaction behavior** (transaction counts, transaction amount, utilization ratio)
- **Customer-bank interaction** (contacts with bank, inactive months)
- **Credit limits** and spending patterns

Visualizations include:
- Histograms, Bar charts, and Pie charts
- Distribution plots for attrited vs existing customers

---

## 📈 Key Insights
1. Female customers show slightly higher attrition.  
2. Married and graduate customers churn more.  
3. Low-income customers have extremely high attrition.  
4. Attrited customers usually contact the bank **2–5 times** before leaving.  
5. Most churned customers made **20–60 transactions** before attrition.  
6. Customers with **3 inactive months** are likely to churn.  
7. Low credit limits and low utilization rates strongly relate to attrition.  
8. Middle-aged customers (40–60 years) show higher attrition.  

---

## 💡 Recommendations
- Improve customer support for low-income and graduate customers.  
- Offer personalized incentives for middle-aged customers.  
- Proactively engage customers with **3+ inactive months**.  
- Increase satisfaction for customers who frequently contact support.  
- Provide flexible credit limit adjustments.  

---

## ⚙️ Installation & Usage
Clone the repo and install requirements:
```bash
git clone https://github.com/yourusername/credit-card-customers-eda.git
cd credit-card-customers-eda
pip install -r requirements.txt
