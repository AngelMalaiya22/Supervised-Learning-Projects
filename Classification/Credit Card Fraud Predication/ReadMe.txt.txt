# 💳 Credit Card Fraud Detection

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It is a binary classification problem where the objective is to classify transactions as either legitimate (0) or fraudulent (1).

The dataset is highly imbalanced, making this a real-world problem where traditional evaluation metrics like accuracy are not sufficient.

---

## 📂 Dataset Description

The dataset contains transactions made by European cardholders over two days in September 2013.

* Total Transactions: 284,807
* Fraudulent Transactions: 492 (0.172%)
* Features:

  * V1–V28: PCA-transformed numerical features
  * Time: Seconds elapsed between transactions
  * Amount: Transaction amount
  * Class: Target variable (0 = Normal, 1 = Fraud)

Due to PCA transformation, the original feature meanings are not available.

---

## 📂 Dataset

Due to file size limitations, the dataset is not included in this repository.

You can download it from:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


## ⚠️ Problem Statement

The dataset is highly imbalanced, which creates challenges:

* High accuracy does not indicate good performance
* Models tend to bias towards the majority class
* Detecting fraud (minority class) becomes difficult

---

## 🔄 Workflow

### 1. Data Preprocessing

* Checked for missing values
* Dropped the 'Time' feature
* Scaled the 'Amount' feature
* Separated features and target variable

### 2. Train-Test Split

* Data split into training and testing sets
* Used stratification to maintain class distribution

### 3. Model Training (Before SMOTE)

The following models were trained on the imbalanced dataset:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

### 4. Handling Class Imbalance

* Applied **SMOTE (Synthetic Minority Over-sampling Technique)**
* Generated synthetic samples of the fraud class
* Balanced the training dataset

### 5. Model Training (After SMOTE)

* Retrained all models on balanced data
* Evaluated performance improvements

---

## 📊 Evaluation Metrics

Due to class imbalance, the following metrics were used:

* Precision
* Recall ⭐ (most important)
* F1-score
* Confusion Matrix

> Accuracy was not considered reliable for this problem.

---

## 📈 Results & Analysis

### 🔹 Before SMOTE

* High accuracy (~99%)
* Lower recall for fraud class
* Models missed several fraudulent transactions

### 🔹 After SMOTE

* Significant improvement in recall
* Models detected most fraud cases
* Precision decreased due to more false positives

---

## 🏆 Best Model

**Random Forest (after SMOTE)** performed the best:

* Precision ≈ 0.84
* Recall ≈ 0.87
* Balanced performance

This indicates that Random Forest effectively handles complex patterns and imbalanced data.

---

## 📊 Visualizations

* Class distribution before and after SMOTE
* Recall comparison across models
* Confusion matrix for best-performing model

---

## 🧠 Key Insights

* Accuracy is misleading for imbalanced datasets
* Recall is critical in fraud detection
* SMOTE significantly improves fraud detection capability
* There is a trade-off between precision and recall
* Ensemble methods like Random Forest are more robust

---

## 🚀 Future Improvements

* Hyperparameter tuning for better performance
* Use of advanced models like XGBoost
* Real-time fraud detection system
* Model deployment using Streamlit or Flask

---

## 🏁 Conclusion

This project demonstrates the importance of handling class imbalance in machine learning. By applying SMOTE, the models were able to significantly improve their ability to detect fraudulent transactions.

The results highlight that in real-world problems like fraud detection, evaluation metrics such as recall are more important than accuracy, and model selection should focus on balancing detection capability and reliability.

--