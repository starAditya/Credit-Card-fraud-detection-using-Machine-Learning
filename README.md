# Credit Card Fraud Detection Using Machine Learning

## Abstract

Credit card fraud is a major global issue, causing billions of dollars in losses every year. This project uses machine learning techniques to detect fraudulent transactions by identifying suspicious patterns in transaction data. The model is trained on historical transaction data and evaluated on unseen data.

---

## Overview

With the rapid increase in credit card usage worldwide, ensuring transaction security has become critical. Fraud cases have increased significantly over the years, making it essential to build intelligent systems that can detect fraudulent activities efficiently.

There are two main types of fraud:

* Unauthorized account creation (identity theft)
* Unauthorized use of existing accounts

This project focuses on detecting such frauds using machine learning algorithms.

---

## Project Goals

* Detect fraudulent credit card transactions
* Compare multiple machine learning models
* Identify the best-performing algorithm
* Provide insights using graphs and evaluation metrics

---

## Dataset

* Source: Kaggle Dataset
* Transactions: 284,808
* Features: 31

### Key Features:

* Time: Time elapsed between transactions
* Amount: Transaction amount
* Class:

  * 0 → Normal transaction
  * 1 → Fraudulent transaction

Note: Most features are transformed using PCA for privacy.

---

## Algorithms Used

* K-Nearest Neighbors (KNN)
* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn

---

## Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Scaling
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Model Comparison

---

## Results

The models were evaluated based on performance metrics such as accuracy and classification performance. The best-performing model was selected based on results.

---

## Conclusion

This project demonstrates how machine learning can effectively detect fraudulent credit card transactions. By comparing multiple algorithms, suitable models can be identified to help reduce financial fraud and improve security systems.
