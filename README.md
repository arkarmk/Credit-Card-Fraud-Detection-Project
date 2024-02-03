# Credit Card Fraud Detection Project
Credit card fraud is a significant concern in the financial industry, leading to substantial financial losses for both consumers and institutions. This project aims to address this issue by developing a robust fraud detection model using machine learning techniques.

## Overview:

### Dataset:
The analysis is conducted on a dataset containing credit card transactions, where fraud occurrences are rare compared to legitimate transactions.

### Approach:
Various machine learning models are employed on both imbalance and balanced datasets to identify fraudulent transactions, including Logistic Regression, K-Nearest Neighbors, Decision Trees, Random Forest and XGBoost.

### Sampling Techniques:
To handle the class imbalance, oversampling techniques such as Random Oversampling, SMOTE, and ADASYN are implemented.

### Model Evaluation:
The models are evaluated using metrics like accuracy, ROC-AUC, and confusion matrices. Special attention is given to minimizing false negatives to enhance fraud detection.

### Hyperparameter Tuning for model trained on imbalanced dataset:
XGBoost Optimization: A Randomized Search Cross-Validation is performed to fine-tune hyperparameters for the XGBoost model.

### Results:
The Logistic model with l2 regularisation, trained on a dataset with Random Oversampling and validated using StratifiedKFold Cross-Validation, demonstrates high accuracy and an ROC-AUC score of 0.9833.
The top three features influencing fraud detection are identified as features 14, 12, and 4.

### Conclusion:
For imbalanced data: XGBoost model with StratifiedKFold CV emerges is the most suitable for credit card fraud detection.
For balanced data: The Logistic model with l2 regularisation, trained on a dataset with Random Oversampling and validated using StratifiedKFold Cross-Validation is the most suitable for credit card fraud detection.

Overall: The Logistic model with l2 regularisation is the best model.

