# Online Payments Fraud Detection with Machine Learning

## Overview

The rise of online payment systems has brought convenience but also an increase in payment frauds, especially with credit cards. 

Detecting online payment fraud is crucial for credit card companies to protect customers from unauthorized charges. This project utilizes machine learning to detect fraudulent transactions and ensure the security of online payments.

## Dataset

The dataset used for this project is sourced from Kaggle and contains historical information about fraudulent transactions. It includes the following columns:

- **step**: Represents a unit of time where 1 step equals 1 hour
- **type**: Type of online transaction
- **amount**: The amount of the transaction
- **nameOrig**: Customer initiating the transaction
- **oldbalanceOrg**: Balance before the transaction
- **newbalanceOrig**: Balance after the transaction
- **nameDest**: Recipient of the transaction
- **oldbalanceDest**: Initial balance of recipient before the transaction
- **newbalanceDest**: New balance of recipient after the transaction
- **isFraud**: Indicates whether the transaction is fraudulent (1 for fraud, 0 for non-fraud)

## Problem Statement

The goal of this project is to train a machine learning model to classify transactions as fraudulent or non-fraudulent based on their features. 

By analyzing historical data of fraudulent transactions, the model can learn patterns and detect potential fraud in real-time online payments.
