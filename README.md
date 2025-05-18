# Credit Card Fraud Detection

This project implements a **Credit Card Fraud Detection** system using machine learning techniques. The code trains two classification models — Logistic Regression and Random Forest — on a highly imbalanced dataset to identify fraudulent credit card transactions.

---

## Project Overview

- The dataset contains credit card transactions labeled as fraudulent (1) or legitimate (0).
- Features include anonymized principal components, transaction amount, and time.
- The dataset is highly imbalanced, with only a small fraction of transactions marked as fraud.
- The project includes data preprocessing, scaling, model training, evaluation, and ROC curve visualization.
- No oversampling or synthetic data techniques (like SMOTE) are used in this implementation.

---

## Dataset

The dataset used is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.

**You can download the dataset here:**  
[Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## Usage Instructions

1. Download the dataset from the Kaggle link above.  
2. Place the `creditcard.csv` file in the same directory as the code.  
3. Run the Python script or Jupyter notebook containing the code.  
4. The script will:  
   - Load and preprocess the data.  
   - Train Logistic Regression and Random Forest models.  
   - Evaluate and print classification metrics.  
   - Plot ROC curves for both models.

---

## Dependencies

Make sure you have the following Python libraries installed:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

You can install them via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
