
# 💳 Credit Card Fraud Detection using Logistic Regression

## 🎯 Objective
To **detect fraudulent credit card transactions** using **Logistic Regression**, helping financial institutions reduce fraud and protect customers.

## 🩺 What We Do
 Preprocess transaction data (cleaning, scaling, handling imbalance).  
 Perform exploratory data analysis (EDA) to understand feature distributions.  
 Train and evaluate Logistic Regression for fraud detection.  
 Visualize confusion matrix, ROC curve, and important metrics.

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Pandas, Numpy
- Matplotlib, Seaborn

## 📂 Dataset
We use the **[Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)** containing transactions made by European cardholders in September 2013:
- 284,807 transactions
- 492 frauds (~0.172% fraud cases)
- Features are PCA-transformed for confidentiality except `Time` and `Amount`.

## ⚙️ Approach
1️⃣ **Data Preprocessing:**
- Scale `Amount` using `StandardScaler`.
- Handle class imbalance using undersampling or class weights.

2️⃣ **Model Training:**
- Train Logistic Regression on preprocessed data.
- Use `class_weight='balanced'` to handle imbalance.

3️⃣ **Evaluation:**
- Confusion Matrix
- ROC-AUC Score
- Precision, Recall, F1-Score

## 📊 Results
 Successfully detected fraudulent transactions with high recall and AUC.  
 Model interpretable for baseline deployment in financial systems.  
 Ready for comparison with advanced methods like Random Forest and XGBoost.

