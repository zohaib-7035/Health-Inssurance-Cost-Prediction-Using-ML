# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using **Logistic Regression**. The dataset contains transactions labeled as legitimate or fraudulent, and the model is trained to classify transactions accordingly.

## Dataset
- The dataset used is **data.csv**.
- It contains transaction details such as **amount, time, and anonymized features**.
- The target variable is `Class`, where:
  - `0` represents **legitimate transactions**.
  - `1` represents **fraudulent transactions**.

## Steps Performed
1. **Data Preprocessing**
   - Load dataset
   - Check for missing values
   - Explore data distribution
   - Balance the dataset by sampling legitimate transactions

2. **Feature Selection & Splitting**
   - Define features (`X`) and target (`Y`)
   - Split data into **training (80%)** and **testing (20%)** sets

3. **Model Training**
   - Use **Logistic Regression** to train the model
   - Fit the model on the training data

4. **Model Evaluation**
   - Predict on training and test data
   - Calculate **accuracy score** for both sets

## Results
- The model outputs accuracy scores for both **training and test datasets**.
- Helps in identifying fraudulent transactions with high accuracy.


