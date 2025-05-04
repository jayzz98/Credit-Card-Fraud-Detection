
# 🛡️ Credit Card Fraud Detection using Logistic Regression

This project demonstrates a machine learning approach to detect fraudulent credit card transactions using a publicly available dataset. The key steps include data preprocessing, handling class imbalance through under-sampling, feature scaling, and training a logistic regression model. The model is evaluated for accuracy on both training and testing datasets.

## 🔍 Features:
- Data exploration and cleaning
- Handling imbalanced data (under-sampling)
- Feature-target separation
- Data scaling with `StandardScaler`
- Model training with `LogisticRegression`
- Evaluation using accuracy metrics

## 🛠️ Tech Stack:
- Python
- Pandas, NumPy
- scikit-learn (Logistic Regression, Pipeline, Preprocessing, Metrics)

## 📊 Dataset:
The dataset contains transactions made by credit cards in September 2013 by European cardholders. It is highly imbalanced, with only ~0.17% fraudulent cases.

> **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## ✅ Results:
The model achieves high accuracy on both training and test sets after balancing the dataset and proper preprocessing.
