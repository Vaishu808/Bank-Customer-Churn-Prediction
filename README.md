# Bank-Customer-Churn-Prediction
Customer churn is one of the most significant challenges faced by banks and financial institutions. Retaining existing customers is often more cost-effective than acquiring new ones.

This project focuses on building a Bank Customer Churn Prediction System that identifies customers who are likely to leave the bank, enabling proactive retention strategies. Using Machine Learning and Deep Learning techniques, the system analyzes customer demographic, behavioral, and financial data to predict churn probability.

# Problem Statement

The objective of this project is to predict whether a bank customer will exit (churn) or stay, based on historical customer data such as:

1. Credit Score
2. Age
3. Tenure
4. Account Balance
5. Number of Products
6. Activity Status
7. Estimated Salary

# Dataset
Source: Kaggle – Bank Customer Churn Dataset
Target Variable: Exited
1 → Customer churned
0 → Customer stayed

# Key Features
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- IsActiveMember
- EstimatedSalary

# Feature Engineering
To enhance model performance, additional features were engineered, including:
Transaction Frequency
Recent Large Withdrawals
Customer Loyalty Score

# Models Implemented
The following models were trained and evaluated:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. XGBoost Classifier
5. Artificial Neural Network (ANN)

# Evaluation Metrics
Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- ROC–AUC Score
- ROC Curves for comparative analysis

# Results
Ensemble and deep learning models outperformed baseline models.
ANN and XGBoost achieved the highest ROC–AUC scores.
The system can rank customers based on churn probability, enabling banks to prioritize high-risk customers for retention efforts.

# Tech Stack
1. Programming Language:
Python
2. Libraries & Frameworks:
NumPy
Pandas
Matplotlib
Scikit-learn
TensorFlow / Keras
XGBoost
Tkinter (for UI)

# Tools
Jupyter Notebook
Git & GitHub
