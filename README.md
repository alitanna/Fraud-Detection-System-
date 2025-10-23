# Fraud Detection System (Machine Learning)

This project builds a **Fraud Detection System** using machine learning models to identify fraudulent financial transactions.  
It includes data preprocessing, model training, evaluation, and model saving — all in a ready-to-run Jupyter Notebook.

---

## Features
- Works with **real or synthetic** data
- Handles **highly imbalanced** datasets using SMOTE (optional)
- Compares multiple models:
  - Logistic Regression  
  - Random Forest  
  - XGBoost (optional)
- Evaluates using:
  - ROC AUC  
  - Precision-Recall AUC  
  - Classification Report  
  - Confusion Matrix visualization
- Saves the best model and scaler for future predictions
- Simple prediction function for new transactions

---

## Workflow
1. Load dataset (`creditcard.csv`) or auto-generate synthetic data  
2. Perform exploratory data analysis (EDA)  
3. Preprocess and scale features  
4. Train multiple models  
5. Evaluate performance metrics  
6. Select and save the best model  
7. Predict on new transaction data

