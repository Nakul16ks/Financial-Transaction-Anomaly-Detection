# Financial-Transaction-Anomaly-Detection
Project Overview

Financial fraud has become a major concern with the rapid growth of digital transactions. Fraudulent transactions usually represent only a very small portion of total transactions, which makes detection challenging. Traditional methods often fail to accurately detect anomalies while maintaining low false positive rates.

This project proposes a Machine Learning–based framework for Financial Transaction Anomaly Detection using LightGBM and SMOTE to handle the severe class imbalance present in financial datasets. The system analyzes transaction patterns and identifies suspicious activities that may indicate fraudulent behavior.

🎯 Problem Statement

With the increasing volume of online financial transactions, detecting fraudulent or anomalous activities has become critical for financial institutions. Fraud datasets are highly imbalanced because fraudulent transactions represent only a tiny fraction of total transactions.

Traditional detection systems struggle to identify fraud effectively due to this imbalance. Therefore, there is a need for an intelligent system that can accurately detect anomalies while minimizing false positives.

🎯 Objectives

To build a machine learning model capable of detecting anomalous financial transactions.

To address class imbalance in fraud datasets using SMOTE (Synthetic Minority Over-sampling Technique).

To improve fraud detection performance using Light Gradient Boosting Machine (LightGBM).

To analyze transaction patterns and classify transactions as normal or anomalous.

⚙️ Technologies Used

Python

Machine Learning

LightGBM

SMOTE

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

📊 Methodology

The framework follows several steps to detect anomalies in financial transactions:

1️⃣ Data Collection

A financial transaction dataset is collected containing features such as transaction amount, time, and other relevant variables.

2️⃣ Data Preprocessing

The dataset is cleaned by removing missing values, normalizing features, and preparing the data for model training.

3️⃣ Handling Class Imbalance

Since fraudulent transactions are rare, SMOTE is used to generate synthetic samples of the minority class to balance the dataset.

4️⃣ Feature Engineering

Important transaction features are extracted and selected to improve the performance of the machine learning model.

5️⃣ Model Training

The LightGBM algorithm is used to train the anomaly detection model due to its high efficiency and accuracy for classification problems.

6️⃣ Model Evaluation

The model performance is evaluated using metrics such as:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

7️⃣ Anomaly Detection

The trained model identifies suspicious transactions that deviate from normal transaction patterns.
