# 🚀 Customer Churn Analytics & Retention Intelligence Platform

An end-to-end Data Science project designed to identify customers at risk of churning, uncover key drivers behind customer attrition, and provide actionable retention strategies through machine learning, SQL analytics, and interactive Power BI dashboards.

---

## 📌 Business Problem

Customer retention is one of the most critical challenges for subscription-based businesses. Acquiring a new customer is significantly more expensive than retaining an existing one.

This project helps organizations:

- Predict which customers are likely to churn
- Understand factors contributing to churn
- Segment customers based on risk
- Design targeted retention campaigns
- Support data-driven decision making through dashboards

---

## 🎯 Project Objectives

- Analyze customer demographics, service usage, and account information.
- Build machine learning models to predict customer churn.
- Identify key churn drivers using explainable AI techniques.
- Generate actionable business insights for customer retention.
- Create executive-level dashboards for monitoring churn trends and KPIs.

---

## 🏗️ Solution Architecture

text SQL Server Database         │         ▼  Data Extraction  (SQL Views)         │         ▼  Data Cleaning & EDA         │         ▼  Feature Engineering         │         ▼  SMOTE Balancing         │         ▼  Model Training         │         ▼  Churn Prediction         │         ▼  Power BI Dashboard         │         ▼  Business Insights & Retention Strategy 

---

## 📊 Exploratory Data Analysis (EDA)

Performed comprehensive analysis to understand customer behavior and churn patterns:

- Missing value analysis
- Customer demographics analysis
- Service usage trends
- Contract type comparison
- Monthly charges distribution
- Churn rate by customer segments
- Correlation analysis

### Key Insights

- Customers with month-to-month contracts showed significantly higher churn rates.
- Higher monthly charges correlated with increased churn probability.
- Long-term customers demonstrated stronger retention.
- Customers with multiple subscribed services were less likely to churn.

---

## 🤖 Machine Learning Pipeline

### Data Preprocessing

- Missing value treatment
- Feature encoding
- Feature scaling
- Data balancing using SMOTE
- Train-test split

### Models Evaluated

| Model | Purpose |
|---------|---------|
| Logistic Regression | Baseline model |
| Random Forest | Ensemble learning |
| XGBoost | Gradient boosting |
| LightGBM | High-performance boosting |
| K-Nearest Neighbors | Distance-based classification |

---

## 🏆 Best Performing Model

### LightGBM (Balanced Dataset)

Performance Metrics:

- Precision: 0.90
- Recall: 0.89
- F1 Score: 0.90

The LightGBM model achieved the best balance between precision and recall, making it suitable for identifying potential churners while minimizing false positives.

---

## 🔬 Experiment Tracking

MLflow was used to:

- Track model experiments
- Compare model performance
- Store hyperparameters
- Monitor evaluation metrics
- Log feature importance explanations

---

## 🧠 Explainable AI

LIME (Local Interpretable Model-Agnostic Explanations) was used to explain individual churn predictions.

This helped identify:

- Why a customer was predicted to churn
- Which features influenced the prediction most
- Potential retention opportunities

---

## 📈 Power BI Dashboard

The Power BI dashboard provides:

### Executive Summary Dashboard

- Total Customers
- Churn Rate
- Revenue Impact
- Customer Segmentation
- Service Utilization Analysis

### Churn Prediction Dashboard

- High-Risk Customer Identification
- Predicted Churn Probability
- Customer-Level Insights
- Retention Opportunity Analysis

---

## 💡 Business Recommendations

Based on model findings:

### High-Risk Customers

- Offer personalized discounts
- Launch targeted retention campaigns
- Provide loyalty rewards

### Contract Optimization

- Encourage migration from month-to-month contracts to long-term plans

### Revenue Protection

- Prioritize outreach to high-value customers with elevated churn risk

---

## 🛠️ Technology Stack

### Data Engineering
- SQL Server
- SQL Views
- ETL Workflows

### Data Analysis
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-Learn
- XGBoost
- LightGBM
- SMOTE

### MLOps
- MLflow
- DVC

### Visualization
- Power BI

---

## 📂 Project Deliverables

- SQL Data Extraction Layer
- EDA Reports
- Machine Learning Pipeline
- Churn Prediction Engine
- Explainability Reports (LIME)
- Power BI Dashboards
- Business Retention Recommendations

---

## 📈 Impact

This solution enables organizations to proactively identify customers likely to churn and implement targeted retention strategies, helping improve customer lifetime value, reduce revenue loss, and support data-driven business decisions
