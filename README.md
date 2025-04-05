# Fraud-Detection-in-Financial-Transaction
This project tackles the problem of detecting fraudulent transactions in a financial dataset containing 6.3 million records. The goal is to build a machine learning model that proactively identifies fraud and provides actionable business insights.

📊 Dataset
6,362,620 transactions

10 key features including transaction type, amount, and account balances

Target: isFraud (1 = fraud, 0 = normal)

🔧 Techniques Used
Exploratory Data Analysis (EDA)

Feature Engineering (errorBalanceOrig, errorBalanceDest)

One-Hot Encoding for transaction types

XGBoost Classifier with class imbalance handling

Evaluation using Precision, Recall, F1-Score, and ROC-AUC

✅ Results
Recall (fraud class): 100%

Precision (fraud class): 83%

AUC Score: 0.9999

Key indicators of fraud: Account draining behavior, balance discrepancies, and suspicious transaction types

🛡️ Recommendations
Real-time fraud scoring based on model predictions

Monitor newbalanceOrig == 0, high errorBalanceOrig, and risky transaction patterns

Continuously retrain model with fresh data

