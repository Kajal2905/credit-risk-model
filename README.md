# credit-risk-model
End to end credit risk modeling using ML
# Credit Risk Modeling & Score Prediction

## 📌 Overview

Built an end-to-end credit risk prediction model to classify customers into Poor, Standard, and Good categories using machine learning.

---

## 🚀 Problem Statement

Predict customer creditworthiness using financial, behavioral, and credit-related features to support lending decisions.

---

## ⚙️ Approach

### 1. Data Preprocessing

* Handled missing values and outliers
* Encoded categorical variables (Credit Mix, Payment Behaviour)
* Feature scaling for linear models

### 2. Feature Engineering

* Debt-to-Income Ratio (DTI)
* Credit Utilization per Loan
* Inquiry per Loan
* Behavioral features (delays, payment patterns)

### 3. Model Building

* Logistic Regression (Baseline ~62%)
* Random Forest (~74%)
* XGBoost (~74.3%) → Final Model

---

## 📊 Model Performance

* Improved accuracy from **62% → 74%**
* Balanced performance across all credit segments
* Strong detection of high-risk customers

---

## 🔍 Key Insights

* Higher interest rates indicate higher risk borrowers
* High DTI reflects financial stress
* Payment delays strongly predict default risk
* Frequent credit inquiries indicate risky behavior
* Credit mix plays a critical role in risk assessment

---

## 🛠 Tech Stack

* Python (Pandas, NumPy)
* Scikit-learn
* XGBoost

---

## 📁 Output

* Predictions generated in `credit_score_predictions.csv`

---

## 💡 Business Impact

* Enables better credit decisioning
* Helps reduce default risk
* Identifies high-risk customers early
