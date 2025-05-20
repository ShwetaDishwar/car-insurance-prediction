# 🚗 Vehicle Insurance Claim Prediction

This project aims to predict whether a vehicle insurance policyholder is likely to file a claim in the upcoming year, using real-world structured data. It's an end-to-end machine learning project that covers everything from data preprocessing to model evaluation.

---

## 📌 Problem Statement

Given the details of customers, their vehicles, and insurance policies, predict whether a customer will file an insurance claim. This helps insurance companies identify high-risk profiles and take proactive measures.

---

## 🗂️ Dataset

- 📄 **Source**: [Kaggle - Car Insurance Claim Prediction](https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification)
- 🧾 **Records**: 58,000+ policyholders
- 🧠 **Target Variable**: `is_claim` (1 = claim filed, 0 = no claim)

---

## 🔧 Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualization
- **Scikit-learn** – Model building and evaluation
- **SMOTE** – For handling class imbalance

---

## 📊 Project Workflow

### 1. Data Exploration & Cleaning
- Removed irrelevant ID columns
- Handled categorical features (Label Encoding, One-Hot Encoding)
- Checked skewness and correlation

### 2. Exploratory Data Analysis (EDA)
- Visualized feature distributions and claim rates
- Checked for imbalance in target variable

### 3. Handling Class Imbalance
- Applied **SMOTE** to oversample the minority class

### 4. Model Building
- Trained multiple models:  
  - Logistic Regression  
  - Random Forest  
  - XGBoost
- Tuned hyperparameters using GridSearchCV

### 5. Model Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC curve

---

## 🚀 Results

| Model              | Accuracy | F1-Score | ROC-AUC |
|-------------------|----------|----------|---------|
| Random Forest      | XX%      | XX%      | XX%     |
| XGBoost            | XX%      | XX%      | XX%     |
| Logistic Regression| XX%      | XX%      | XX%     |

> (*Replace `XX` with your actual results*)
