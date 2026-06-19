# Credit Card Fraud Detection

Detects fraudulent credit card transactions using Machine Learning.

## Dataset
Credit Card Transactions Fraud Detection: 1.2M+ transactions (Kaggle)

## Models Used
- Logistic Regression: ROC-AUC: 0.8495
- Decision Tree: ROC-AUC: 0.9427 ✅ Best
- Random Forest: ROC-AUC: 0.9293

## Tools
Python, scikit-learn, SMOTE, pandas, matplotlib, seaborn

## Key Results
- Best Model: Decision Tree
- ROC-AUC Score: 0.9427
- Fraud Recall: 93% (catches 93 out of every 100 fraud cases)
- Dataset: 1,296,675 training transactions

## Features Used
Transaction amount, hour, day, month, age, distance between cardholder and merchant, city population, category, gender, state

## How to Run
1. Download dataset from Kaggle
2. Place fraudTrain.csv and fraudTest.csv in data/ folder
3. pip install pandas scikit-learn matplotlib seaborn joblib imbalanced-learn
4. python classifier.py
