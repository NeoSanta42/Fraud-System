Project Overview

This project analyzes M-Pesa transaction data to identify fraudulent transactions using a Random Forest Classifier. The notebook performs data exploration, fraud analysis, data preprocessing, model training, and evaluation.

Objectives
Explore M-Pesa transaction data.
Identify patterns associated with fraudulent transactions.
Build a machine learning model to detect fraud.
Evaluate model performance using classification metrics.
Dataset Features

The dataset contains transaction information such as:

TransactionID,
TransactionType,
Amount,
SenderCounty,
ReceiverCounty,
DeviceChangedRecently,
FailedPinAttempts,
NewLocationLogin,
Fraudulent (Target Variable).

Technologies Used:
Python,
Pandas,
Matplotlib,
Seaborn,
Scikit-learn,
Jupyter Notebook,
Exploratory Data Analysis (EDA),

The analysis includes:

Checking dataset shape

Identifying numerical and categorical columns

Handling duplicate records

Checking missing values

Calculating:
Total transaction amount,
Total fraudulent transaction amount,
Fraud percentage,
Average fraud amount,
Average non-fraud amount,

Visualizations
Fraud by Transaction Type.
Fraud by Receiver County,
Fraud by Sender County,
Device Change vs Fraud,
Feature Importance Plot

Key Findings

Transactions above KES 100,000 show higher fraud risk.

Users with multiple failed PIN attempts are more likely to experience fraud.

New location logins are associated with higher fraud rates.

Recent device changes are linked to increased fraudulent activity.
