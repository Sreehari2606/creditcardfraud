﻿Credit Card Fraud Detection
This project is focused on detecting fraudulent transactions using machine learning algorithms. The primary objective is to build a model that can accurately identify fraudulent credit card transactions while minimizing false positives.

Project Overview
The dataset used in this project contains transactions made by European cardholders over two days in September 2013. The dataset is highly imbalanced, with only 0.172% of transactions being fraudulent. The data includes 31 columns, such as transaction time, amount, and anonymized features derived from PCA (Principal Component Analysis).

Steps Involved
Data Preprocessing:

Handling missing values
Scaling the features
Splitting the data into training and testing sets
Model Selection:

Testing various machine learning models like Logistic Regression, Random Forest, and Support Vector Machines (SVM)
Evaluating models based on precision, recall, F1-score, and ROC-AUC
Model Tuning:

Hyperparameter tuning using GridSearchCV
Addressing class imbalance with techniques like SMOTE (Synthetic Minority Over-sampling Technique)
Model Evaluation:

Analyzing the model performance on the test set
Visualizing the results using confusion matrix and ROC curve
Results
The final model achieved a high recall rate for detecting fraudulent transactions, with an acceptable level of precision. The model is capable of identifying fraudulent transactions effectively, making it a valuable tool for credit card fraud prevention.

How to Use
You can download the dataset used for this project from the following Google Drive link:

[Download Credit Card Fraud Dataset](hhttps://drive.google.com/file/d/1aQR-lk-cmS_MOKYTkYQMZSsvs0S3mBDs/view?usp=drive_link)
https://drive.google.com/file/d/1aQR-lk-cmS_MOKYTkYQMZSsvs0S3mBDs/view?usp=drive_link


To reproduce the results or run the model on a new dataset, open the CreditCardFraud.ipynb notebook in Google Colab and follow the steps outlined.

Questions?
If you have any questions or need clarification, feel free to reach out to me directly. I'm happy to help!

