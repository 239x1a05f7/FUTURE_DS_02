# 📊 Telecom Customer Churn Analysis Dashboard

## 🚀 Project Overview

Customer churn is one of the most significant challenges faced by telecommunication companies. Retaining existing customers is often more cost-effective than acquiring new ones. This project analyzes customer behavior, identifies key factors contributing to churn, and presents actionable business insights through an interactive dashboard.

The project combines **Exploratory Data Analysis (EDA)**, **Machine Learning**, and **Business Intelligence** techniques to help stakeholders understand customer retention patterns and make data-driven decisions.

---

## 🎯 Project Objectives

* Analyze customer churn patterns.
* Identify the major factors influencing customer churn.
* Build an interactive business dashboard.
* Generate actionable business insights.
* Support decision-making with data visualization.
* Demonstrate predictive analytics using the Random Forest algorithm.

---

## 📂 Dataset Information

The dataset contains customer-level information from a telecom company, including:

* Account Weeks
* Contract Renewal
* International Plan
* Voice Mail Plan
* Customer Service Calls
* Monthly Charges
* Day, Evening, Night & International Usage
* Churn Status (Target Variable)

**Target Variable**

* **0** → Customer Retained
* **1** → Customer Churned

---

## 🛠️ Technologies Used

| Technology       | Purpose                         |
| ---------------- | ------------------------------- |
| Python           | Data Cleaning & Analysis        |
| Pandas           | Data Manipulation               |
| NumPy            | Numerical Computing             |
| Matplotlib       | Data Visualization              |
| Scikit-learn     | Machine Learning                |
| HTML5            | Dashboard Structure             |
| CSS3             | Dashboard Styling               |
| JavaScript       | Dashboard Interactivity         |
| Chart.js         | Interactive Charts              |
| Tableau          | Business Intelligence Dashboard |
| Jupyter Notebook | Data Analysis                   |

---

## 📈 Dashboard Features

### Executive KPIs

* 👥 Total Customers
* 📉 Churn Rate
* ✅ Retention Rate
* 🤖 Random Forest Model Accuracy
* 💰 Average Monthly Charge
* 📅 Average Customer Lifetime

---

### Interactive Visualizations

* Customer Churn Distribution
* Contract Renewal vs Churn
* Customer Service Calls vs Churn
* Monthly Charges by Churn
* Account Weeks by Churn
* International Plan vs Churn
* Voice Mail Plan Analysis
* Random Forest Feature Importance
* Customer Segmentation Analysis

---

### Interactive Filters

* Contract Renewal
* International Plan
* Voice Mail Plan
* Customer Churn
* Account Weeks

---

## 🤖 Machine Learning Model

A **Random Forest Classifier** was used to predict customer churn and identify the most influential features affecting customer retention.

The model provides feature importance rankings that help explain which customer attributes contribute most to churn prediction.

> **Note:** Replace model evaluation metrics (Accuracy, Precision, Recall, F1-Score, ROC-AUC) with the actual values generated from your notebook.

---

## 📊 Key Business Insights

* Customers with **4 or more customer service calls** exhibit a significantly higher churn rate.
* Customers who **do not renew their contracts** are much more likely to churn.
* **International Plan** subscribers demonstrate higher churn than the overall customer base.
* Customers with **higher monthly charges** are more likely to leave.
* Longer customer tenure is associated with improved retention.
* Feature importance analysis highlights customer service interactions and plan selection as major predictors of churn.

---

## 💡 Business Recommendations

* Contact customers proactively after multiple service calls.
* Provide renewal incentives before contract expiration.
* Develop targeted retention campaigns for high-risk customer segments.
* Review pricing strategies for customers with high monthly charges.
* Reward loyal customers with personalized offers.
* Retrain the predictive model periodically using updated customer data.

---

## 📸 Dashboard Preview

> Add screenshots of your dashboard here.

Example:

```text
dashboard.png
```

---

## 📁 Project Structure

```text
Telecom-Churn-Analysis/
│
├── Data/
│   ├── telecom_churn.csv
│
├── Notebook/
│   ├── Telecom_Churn_Analysis.ipynb
│
├── Dashboard/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│
├── Images/
│   ├── dashboard.png
│
├── Report/
│   ├── Telecom_Churn_Report.pdf
│
├── README.md
│
└── requirements.txt
```

---

## 📌 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Machine Learning Model Development
6. Model Evaluation
7. Dashboard Development
8. Business Insights & Recommendations

---

## 📈 Future Enhancements

* Real-time dashboard updates.
* Integration with SQL databases or cloud storage.
* Additional machine learning models for comparison.
* Customer Lifetime Value (CLV) prediction.
* Automated churn alert system.
* Deployment as a web application.

---

## 👤 Author

**Ashwini**

B.Tech – Computer Science Engineering

Aspiring Data Analyst | Business Analyst | Machine Learning Enthusiast

---

## ⭐ Acknowledgements

This project was developed as part of a **Data Science & Analytics Internship** to demonstrate practical skills in data analysis, visualization, business intelligence, and predictive analytics.

If you found this project useful, consider giving it a ⭐ on GitHub.
