# 💳 Credit Card Fraud Detection
**Machine Learning | Classification | Imbalanced Data**

## 📌 The Challenge
Detecting fraudulent transactions is a "needle in a haystack" problem. In this dataset, fraud represents less than 1% of the data. The goal was to build a model that doesn't just look for accuracy, but specifically focuses on **Recall** (finding all fraud).

## 🛠️ Technical Approach
* **Data Balancing:** Used **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the classes.
* **Feature Engineering:** Analyzed the V1-V28 PCA components to find the most significant indicators of fraud.
* **Model:** Evaluated Random Forest and Logistic Regression.

## 📊 Key Results
* **Recall:** [e.g., 92%] — Ensuring we catch the majority of fraudulent attempts.
* **Precision:** [e.g., 85%] — Minimizing "false alarms" for legitimate customers.

## 📊 Data Source
The dataset used in this project is the **Credit Card Fraud Detection** dataset. 
Due to GitHub's file size limitations, the raw `.csv` file is not included in this repository. 

You can download the dataset here: **https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud**
