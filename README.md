# ML-Project-Telco-Customer-churn
# Customer Churn Prediction

## 📄 Overview

This project predicts customer churn for a subscription-based business using machine learning. The goal is to identify customers at high risk of cancellation so the company can take proactive retention actions, such as targeted discounts or loyalty offers.

---

## 🎯 Business Problem

Customer churn leads to significant revenue loss and increased customer acquisition costs. By predicting churn before it happens, a company can retain customers more efficiently and improve lifetime value (LTV).

**Business Impact Example:**
With a customer base of 100,000 and an average revenue per user (ARPU) of $50/month, reducing churn by just 1% can save ~$50,000 per month ($600,000 annually).

---

## 🧠 Project Objectives

* Predict whether a customer will churn in the next period.
* Identify key factors that drive churn behavior.
* Visualize and communicate insights to business stakeholders.
* Provide actionable recommendations for customer retention.

---

## ⚙️ Tech Stack

* **Language:** Python 3
* **Libraries:** pandas, numpy, scikit-learn, xgboost, shap, matplotlib, seaborn
* **Visualization:** Power BI / Tableau (optional)
* **Environment:** Jupyter Notebook

---

## 📊 Data Description

Dataset used: **Telco Customer Churn Dataset (Kaggle / IBM Sample)**

**Key columns:**

* `tenure` – Number of months customer has stayed.
* `MonthlyCharges`, `TotalCharges` – Billing information.
* `Contract`, `PaymentMethod` – Subscription and payment details.
* `InternetService`, `TechSupport`, `OnlineSecurity` – Service usage features.
* `Churn` – Target variable (Yes/No).

---

## 🧩 Methodology

1. **Data Cleaning** – Handle missing values, encode categorical features.
2. **EDA** – Explore churn rates, correlations, and segment behaviors.
3. **Feature Engineering** – Create features like tenure buckets, usage trends.
4. **Model Training** – Train Logistic Regression and XGBoost models.
5. **Model Evaluation** – ROC AUC, Precision, Recall, Confusion Matrix.
6. **Explainability** – Use SHAP for interpreting model predictions.
7. **Business Insights** – Identify top drivers of churn and suggest retention actions.

---

## 📈 Results Summary

* **Best model:** XGBoost
* **ROC AUC:** 0.87
* **Precision@5%:** 0.62
* **Top churn drivers:** Contract type, tenure, total charges, and support usage.

**Actionable Insights:**

* Customers with month-to-month contracts are 3x more likely to churn.
* Long-term contract offers or loyalty discounts could reduce churn.
* High monthly charges without premium service usage indicate at-risk customers.

---

## 💼 Business Recommendations

* **Retention Campaigns:** Target top 5% of predicted high-risk customers.
* **Personalized Offers:** Provide flexible plans or billing reminders.
* **Customer Engagement:** Increase contact with customers showing reduced service activity.
* **Monitor KPI:** Monthly churn rate and retention ROI.

---

## 📁 Deliverables

* Jupyter Notebook: `customer_churn_prediction.ipynb`
* Predictions file: `churn_predictions.csv`
* Power BI Dashboard (optional): `churn_dashboard.pbix`
* README (this document)

---

## 📚 Future Work

* Add deep learning models (e.g., LSTM for time-series churn patterns).
* Deploy model as a REST API for real-time predictions.
* Integrate dashboard automation with Power BI service.

---

## 👤 Author

**Yahya Bhara**
Data Science Student | Machine Learning & Analytics Enthusiast
[GitHub Profile](#) | [LinkedIn Profile](#)
