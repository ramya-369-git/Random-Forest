# Credit Card Fraud Detection using Random Forest

This project implements a machine learning model using the Random Forest algorithm to detect fraudulent transactions in a credit card dataset.

## 📌 Overview

Credit card fraud is a significant issue in financial systems. Detecting fraudulent transactions accurately and efficiently is essential to prevent financial loss. This project uses a Random Forest classifier to classify transactions as fraudulent or legitimate.

## 📂 Dataset

- The dataset used is a real-world anonymized credit card dataset.
- It contains **284,807** transactions with **30 features** and a target label:
  - `Class = 1`: Fraudulent
  - `Class = 0`: Legitimate
- Due to confidentiality, feature names are anonymized (`V1`, `V2`, ..., `V28`) except for `Time`, `Amount`, and `Class`.

> **Note:** The original dataset (`creditcard.csv`) is large (~150MB) and is not included in this repository. You can download it from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## 🧠 Model: Random Forest

- **Random Forest** is an ensemble learning method that builds multiple decision trees and merges their predictions.
- Pros:
  - Handles imbalanced datasets well.
  - Resistant to overfitting compared to a single decision tree.
- Implementation includes:
  - Data preprocessing
  - Train-test split
  - Training the Random Forest model
  - Evaluation using accuracy, precision, recall, F1-score, and confusion matrix

## 📈 Evaluation

Metrics used:
- **Accuracy**

The dataset is highly imbalanced (fraud cases ~0.17%), so metrics like recall and precision are more meaningful than plain accuracy.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- scikit-learn
- pandas, numpy

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ramya-369-git/Random-Forest.git
   cd Random-Forest
