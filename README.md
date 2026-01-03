# Fraud-Detection
Credit Card Fraud Detection project using Logistic Regression. Includes EDA, categorical encoding, model training, and evaluation with precision, recall, F1-score, and accuracy to identify fraudulent transactions.

# Credit Card Fraud Detection using Logistic Regression

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using a supervised machine learning approach. Logistic Regression is applied to classify transactions as fraud or non-fraud based on transaction and customer-related features.

## 📊 Dataset
The dataset contains transaction-level information including:
- Transaction amount
- Merchant category
- Customer gender
- Transaction location
- Fraud label (target variable)

## 🔍 Exploratory Data Analysis (EDA)
- Distribution of transaction amounts by fraud status using histograms
- Box plots to compare transaction amount spread between fraud and non-fraud cases
- Insights on overlap and variability of transaction amounts

## 🛠️ Data Preprocessing
- Categorical features encoded using LabelEncoder
- Feature and target separation
- Train-test split (70% training, 30% testing)

## 🤖 Model Used
- **Logistic Regression**
- Suitable for binary classification problems
- Predicts probability of a transaction being fraudulent

## 📈 Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Classification Report

Key observation:
- High recall for fraud cases, ensuring most fraudulent transactions are detected
- Moderate overall accuracy, highlighting class imbalance challenges

## 🧠 Conclusion
Logistic Regression performs effectively in identifying fraudulent transactions, especially when recall is prioritized. However, transaction amount alone is insufficient, and combining multiple features improves detection performance.


