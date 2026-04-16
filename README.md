# 💳 Financial Fraud Detection System

## 📌 Project Overview

This project focuses on detecting fraudulent financial transactions using Machine Learning techniques. It simulates real-world financial data and applies multiple ML models to identify fraud, predict loan defaults, detect anomalies, and segment customers.

---

## 🎯 Objectives

* Detect fraudulent credit card transactions
* Predict loan default risk
* Identify anomalous (unusual) transactions
* Perform customer segmentation using clustering

---

## 🧠 Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📊 Project Modules

### 1. Synthetic Data Generation

* Created realistic financial datasets using random distributions
* Features include:

  * Transaction amount
  * Merchant risk
  * Transaction time
  * Credit score
  * Loan details

---

### 2. Fraud Detection (Classification)

* Used **Logistic Regression**
* Predicts whether a transaction is fraud or not
* Handles class imbalance using `class_weight='balanced'`

---

### 3. Loan Default Prediction

* Predicts whether a customer will default on a loan
* Based on:

  * Income
  * Credit score
  * Debt-to-income ratio

---

### 4. Risk Scoring

* Converts prediction probabilities into **0–100 risk score**
* Helps in decision making

---

### 5. Anomaly Detection

* Used **Isolation Forest**
* Detects unusual transactions without labeled data

---

### 6. Customer Segmentation

* Used **KMeans Clustering**
* Groups customers based on spending behavior

---

## ⚙️ Machine Learning Techniques

* Supervised Learning (Logistic Regression)
* Unsupervised Learning (Isolation Forest, KMeans)
* Feature Scaling using StandardScaler
* Model Evaluation using:

  * ROC-AUC Score
  * Classification Report
  * Silhouette Score

---

## 📈 Output

* Fraud detection predictions
* Loan default predictions
* Customer risk scores
* Anomaly detection results
* Clustered customer groups

---

## 💡 Real-World Applications

* Banking systems
* Credit card fraud detection
* Loan approval systems
* Financial risk management

---

## 🚀 How to Run

1. Install required libraries:

   ```
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Run the notebook:

   ```
   jupyter notebook
   ```
3. Execute all cells

---

## 📌 Conclusion

This project demonstrates how Machine Learning can be effectively used to detect fraud, assess financial risk, and improve decision-making in real-world financial systems.

---

## 👨‍💻 Author

Abhishek Agnihotri
