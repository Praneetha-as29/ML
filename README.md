# Machine Learning Projects

This repository contains 3 hands-on machine learning projects built using real-world datasets, implemented in Python using Jupyter/Colab notebooks.

## 📂 Projects

### 1. 📱 Spam SMS Detection
- **Goal:** Classify SMS messages as spam or ham.
- **Tech Stack:** Python, Pandas, Scikit-learn, TF-IDF, Naive Bayes.
- **Result:** 96.7% Accuracy.

### 2. 👥 Customer Churn Prediction
- **Goal:** Predict if a customer will leave a telecom service.
- **Tech Stack:** Logistic Regression, Random Forest, Label Encoding, SMOTE.
- **Key Features:** Tenure, MonthlyCharges, Contract Type, Internet Service.
- **Result:** ~82% Accuracy with strong recall on churned customers.

### 3. 💳 Credit Card Fraud Detection
- **Goal:** Detect fraudulent credit card transactions.
- **Tech Stack:** Random Forest, SMOTE, Scikit-learn, PCA-preprocessed data.
- **Challenge:** Extremely imbalanced dataset (~0.17% fraud cases).
- **Result:** 97% Accuracy, 75% Recall on fraud class.

---

## 📁 Folder Structure

```bash
ML/
├── SPAM_SMS_DETECTION.ipynb
├── CUSTOMER_CHURN_PREDICTION.ipynb
├── CREDIT_CARD_FRAUD_DETECTION.ipynb
└── README.md
