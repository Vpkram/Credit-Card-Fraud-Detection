# Credit-Card-Fraud-Detection
This project aims to detect fraudulent credit card transactions using Logistic Regression, a simple yet effective Machine Learning classification algorithm. The main objective is to identify fraudulent transactions accurately from a highly imbalanced dataset and understand how Machine Learning can be applied in real-world financial security systems.

📊 Dataset

The dataset used in this project is sourced from Kaggle and contains anonymized credit card transaction details.

Total transactions: 284,807
Fraudulent transactions: 492
Highly imbalanced dataset with very few fraud cases
Features V1 to V28 are transformed using PCA for confidentiality purposes
Additional features include:
Time
Amount
Class (Target Variable)
0 → Legitimate Transaction
1 → Fraudulent Transaction
🧠 Model: Logistic Regression
Type
Binary Classification Model
Preprocessing Techniques
Data cleaning and preprocessing
Feature and target separation
Train-test data splitting
Handling imbalanced data using Random Under-Sampling
Data normalization and scaling
Why Logistic Regression?
Simple and interpretable model
Fast training and prediction
Effective baseline algorithm for binary classification problems
Performs efficiently on structured datasets
⚙️ Tech Stack
Python
Google Colab / Jupyter Notebook
Libraries Used
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
📈 Project Workflow
Importing and analyzing dataset
Data preprocessing and cleaning
Handling class imbalance
Splitting training and testing data
Training Logistic Regression model
Predicting fraudulent transactions
Evaluating model accuracy and performance
🎯 Objective

The primary objective of this project is to build a Machine Learning model capable of detecting fraudulent credit card transactions efficiently. The project also helps in understanding real-world fraud detection systems, imbalanced datasets, and classification model evaluation techniques.

✅ Conclusion

This project demonstrates that Logistic Regression combined with proper preprocessing and imbalance handling techniques can effectively identify fraudulent transactions. It provides practical exposure to Machine Learning workflows, financial data analysis, and fraud detection methodologies.
