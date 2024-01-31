# Credit Card Fraud Detection Project
Credit card fraud is a significant concern in the financial industry, leading to substantial financial losses for both consumers and institutions. This project aims to address this issue by developing a robust fraud detection model using machine learning techniques.

## Overview:

### Dataset:
The analysis is conducted on a dataset containing credit card transactions, where fraud occurrences are rare compared to legitimate transactions.

### Approach:
Various machine learning models are employed to identify fraudulent transactions, including Logistic Regression, K-Nearest Neighbors, Decision Trees, Random Forest, XGBoost, and Support Vector Machines (SVM).

### Sampling Techniques:
To handle the class imbalance, oversampling techniques such as Random Oversampling, SMOTE, and ADASYN are implemented.

### Model Evaluation:
The models are evaluated using metrics like accuracy, ROC-AUC, and confusion matrices. Special attention is given to minimizing false negatives to enhance fraud detection.

### Hyperparameter Tuning:
XGBoost Optimization: A Randomized Search Cross-Validation is performed to fine-tune hyperparameters for the XGBoost model, enhancing its predictive capabilities.

### Results:
The XGBoost model, trained on a dataset with Random Oversampling and validated using StratifiedKFold Cross-Validation, demonstrates high accuracy and an impressive ROC-AUC score of 0.97.
The top three features influencing fraud detection are identified as features 14, 10, and 4.

### Conclusion:
The selected XGBoost model with Random Oversampling and StratifiedKFold CV emerges as the most suitable for credit card fraud detection, offering a balance between accuracy and the ability to handle imbalanced classes.
