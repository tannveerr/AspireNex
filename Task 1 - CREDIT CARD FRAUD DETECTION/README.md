# Task 1 - Credit Card Fraud Detection

This repository contains the Credit Card Fraud Detection project developed as part of the Data Science Internship at `AspireNex`

## Overview

The objective of this project is to detect fraudulent credit card transactions using a machine learning model. Due to the highly imbalanced nature of the <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">`dataset`</a>, with fraudulent transactions being significantly less frequent than legitimate ones, special techniques were used to ensure accurate and reliable detection.


## Key Observations

- **Data Imbalance**: The dataset is highly imbalanced, with a much smaller number of fraudulent transactions compared to legitimate ones.
- **Transaction Amounts**: The mean transaction amount is higher in fraud cases than in legitimate ones.

## Methodology

1. **Data Preprocessing**: Handled missing values, normalized transaction amounts, and performed under-sampling to balance the dataset.
2. **Modeling**: Used a logistic regression model to classify transactions as fraudulent or legitimate.
3. **Evaluation**: Assessed model performance using accuracy, precision, recall, and F1-score.

## Results

- **Training Accuracy**: 92.86%
- **Test Accuracy**: 90.0%
- **Classification Metrics**:
  - Precision, Recall, F1-Score for both classes: ~0.90

## Contact Information
For any inquiries or feedback regarding this project, please contact:
- Email: tanveer22971@gmail.com
