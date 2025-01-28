# Credit Fraud Detection: Dealing with Imbalanced Datasets

This repository contains a Jupyter Notebook that addresses the challenge of detecting credit fraud using machine learning techniques. The focus is on dealing with the problem of imbalanced datasets, which is common in fraud detection tasks.

## Overview

Fraud detection is a critical task in finance and e-commerce industries. However, the datasets involved are typically highly imbalanced, with fraudulent transactions being significantly outnumbered by legitimate ones. This project explores various techniques to handle this imbalance and improve model performance.

### Key Features
- **Exploratory Data Analysis (EDA):** Insights into dataset structure and fraud patterns.
- **Preprocessing:** Data cleaning, normalization, and handling of missing values.
- **Imbalance Handling:** Techniques such as undersampling, oversampling (SMOTE, ADASYN), and cost-sensitive learning.
- **Modeling:** Comparison of various machine learning models like Logistic Regression, Random Forest, XGBoost, and Neural Networks.
- **Evaluation:** Metrics beyond accuracy, such as Precision, Recall, F1 Score, and AUC-ROC curve, to ensure fair evaluation of imbalanced datasets.


### Dataset
The dataset used for this project is publicly available [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Download it and place it in the `data/` directory before running the notebook.


## Results
The project demonstrates effective handling of imbalanced datasets through various methods. Below is a summary of key findings:
- Oversampling methods like SMOTE improve recall significantly.
- Cost-sensitive learning enhances model robustness without altering the dataset.
- Random Forest and XGBoost models perform well with tuned hyperparameters.

