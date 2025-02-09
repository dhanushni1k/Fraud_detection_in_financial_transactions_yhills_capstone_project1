# Fraud_detection_in_financial_transactions_yhills_capstone_project2
# Fraud Detection in Financial Transactions

## Description
This project aims to detect fraudulent financial transactions using machine learning techniques. It involves classification models, anomaly detection, and PCA visualization to identify fraudulent activities effectively.

## Features
- Data preprocessing with normalization and feature selection
- Handling imbalanced datasets using SMOTE
- Training classification models (Random Forest, XGBoost)
- Evaluating model performance using classification metrics
- Anomaly detection using Isolation Forest
- PCA visualization for fraud detection

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- imbalanced-learn

## Installation
Ensure you have Python installed, then install dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

## Dataset
The dataset used is `creditcard.csv`, containing transaction details with labels indicating fraud (`Class = 1`) or normal (`Class = 0`).

## Usage
Run the script:
```bash
python fraud_detection.py
```

## Model Training & Evaluation
- **Random Forest & XGBoost:** Used for classification of transactions.
- **Evaluation Metrics:** Confusion matrix and classification report.
- **Anomaly Detection:** Isolation Forest is used to detect unusual patterns.
- **PCA Visualization:** 2D visualization of fraudulent vs. non-fraudulent transactions.

## Output
- Classification reports for fraud detection models.
- A scatter plot visualizing fraudulent transactions.
