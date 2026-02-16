📌 Project Overview

Customer churn is one of the biggest challenges in subscription-based businesses.

This project builds a Machine Learning model to predict whether a telecom customer is likely to churn and deploys it as an interactive Streamlit dashboard.

The system helps businesses identify high-risk customers and take proactive retention actions.

🎯 Problem Statement

Identify customers who are likely to leave the service based on:

Usage behavior

Contract details

Billing information

Payment methods

Service subscriptions

🛠 Tech Stack

Python

Pandas & NumPy

Scikit-Learn

Imbalanced-Learn (SMOTE)

Logistic Regression

Streamlit

Plotly (Interactive Charts)

📊 Machine Learning Workflow

1️⃣ Data Cleaning
2️⃣ Feature Engineering
3️⃣ Handling Imbalanced Data using SMOTE
4️⃣ Model Comparison:

Logistic Regression

Random Forest

Gradient Boosting

XGBoost

Neural Network
5️⃣ Model Selection using ROC-AUC
6️⃣ Threshold Optimization
7️⃣ Deployment using Streamlit

📈 Model Performance
Metric	Score
ROC-AUC	0.83
Accuracy	73%
Churn Recall	78%

The model prioritizes recall to reduce revenue loss from missed churn customers.

📊 Key Business Insights

🔥 Fiber optic users show highest churn probability

💰 High monthly charges increase churn risk

📅 Long-term contracts reduce churn

💳 Electronic check users churn more frequently

🚀 Dashboard Features

Real-time churn prediction

Churn probability gauge visualization

Risk categorization (Low / Medium / High)

Auto-calculated Total Charges

Interactive UI for testing customer scenarios
