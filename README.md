# Karnataka-banking-fraud-transaction-detection-prevention-and-predective-model
A binary classification problem regarding the Karnataka bank's fraud ATM transactions. 

## Table of Contents
- Project Overview
- Problem Statement
- Data
- Challenge
- Approach
- Results

## Project Overview
- The objective of this project is to build a predictive model for fraud detection and prevention in ATM transactions for Karnataka banking client. 
- The goal is to reduce and potentially eliminate fraudulent transactions by creating a real-time predictive model that can identify and decline such transactions.
- The Project Notebook is available at https://github.com/Shinde-Siddhant/Australian-banking-fraud-ATM-transaction-detection-model/blob/main/Project%20Notebook/Final_Project_ATM_Transaction_Fraud_Detection.ipynb

## Problem Statement
- The Karnataka banking client's profitability and reputation are being hit by fraudulent ATM transactions. Your job as Data Scientist is to build this fraud detection & prevention predictive model in the first step. If successful, in the 2nd step you will have to present your solutions and explain how it works to the client.
- The challenging part of the problem is that the data contains very few fraud instances in comparison to the overall population. To give more edge to the solution they have also collected data regarding location [geo_scores] of the transactions, their own proprietary index [Lambda_wts], on network turn around times [Qset_tats] and vulnerability qualification score [instance_scores]. As of now you don't need to understand what they mean.
- Training data contains masked variables pertaining to each transaction id . Your prediction target here is 'Target'.
  1: Fraudulent transactions
  0: Clean transactions
- The problem statement ia available at https://github.com/Shinde-Siddhant/Australian-banking-fraud-ATM-transaction-detection-model/tree/main/Problem%20Statement

## Data
- The training data consists of masked variables related to each transaction ID. The prediction target is 'Target,' where:
  1: Represents fraudulent transactions
  0: Represents clean transactions
- Additional data features include location (geo_scores), proprietary index (Lambda_wts), network turn around times (Qset_tats), and vulnerability qualification score (instance_scores).
- All the datasets are available at https://github.com/Shinde-Siddhant/Australian-banking-fraud-ATM-transaction-detection-model/tree/main/Datasets

## Challenge
- One of the primary challenges in this project is the highly imbalanced nature of the data, with a limited number of instances of fraudulent transactions compared to the overall dataset. Addressing this imbalance is crucial for building an effective fraud detection model.

## Approach
- To tackle the imbalanced data, we employed technique such as Oversampling method.
- Algorithmic approaches like Logistic Regression, Decision Tree, Random Forest, XGBoost etc.
- Feature engineering to enhance the model's ability to discern fraud instances.
- The project follows a systematic approach involving data exploration, preprocessing, model training, and evaluation to build a robust fraud detection and prevention model.

## Results
- Our predictive model demonstrated promising results in detecting and preventing fraudulent transactions. 
- Performance metrics including precision, recall, and F1-score, showcase the effectiveness of the model in real-time scenarios.





