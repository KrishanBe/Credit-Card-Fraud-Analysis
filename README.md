# Credit-Card-Fraud-Analysis

**BUSINESS UNDERSTANDING**

Problem Statement:

Company ABC, a major credit card company, faces challenges with their existing fraud detection system. The current system exhibits slow responsiveness in recognizing new patterns of fraud, leading to significant financial losses. To address this issue, they have contracted us to design and implement an algorithm that can efficiently identify and flag potentially fraudulent transactions for further investigation. The data provided consists of two tables: "cc_info," containing general credit card and cardholder information, and "transactions," containing details of credit card transactions that occurred between August 1st and October 30th.

Objective:

The primary goal of this project is to build an advanced fraud detection system using neural networks to identify transactions that appear unusual and potentially fraudulent. By applying object-oriented programming (OOPs) concepts, we aim to develop a scalable and modular solution that can handle large volumes of data and provide valuable insights to Company ABC.

Main Execution:

Creates a FraudDetectionModel instance with the merged DataFrame (df).
Performs data preprocessing and builds the K-Means model.
Creates fraud labels for each transaction based on K-Means clusters.
Visualizes the distribution of fraudulent transactions.
Splits the data into training and testing sets.
Builds and trains the neural network model.
Evaluates the model performance on the test set.
Visualizes the distribution of fraudulent vs. non-fraudulent transactions.
