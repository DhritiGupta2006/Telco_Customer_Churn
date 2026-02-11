# 📊 Telco Customer Churn Prediction

## 🎯 Project Goal

Predict whether a telecom customer will **churn (Yes/No)** using supervised machine learning on tabular data.

---

## 📂 Dataset

**WA_Fn-UseC_-Telco-Customer-Churn.csv** Source: **IBM** Telco Customer Churn Dataset

---

## 🔀 Train / Validation Split

- **Method:** `train_test_split` from Scikit-learn
- **Split Ratio:** 80% Train / 20% Test
- **Strategy:** `stratify=y` (preserves churn ratio)
- **Random State:** `42`

---

## 🧠 Models Used

- **Baseline Model:** Logistic Regression
- **Improved Model:** Random Forest Classifier

---

## 📏 Evaluation Metrics

The following metrics are reported:

- **Accuracy**
- ****ROC**-**AUC** Score**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**
- **Classification Report**

---

## 🏆 Best Results

### 🔹 Baseline Model — Logistic Regression

- **Accuracy:** `0.**7991**`
- ****ROC**-**AUC**:** `0.**8403**`

**Classification Summary:**

- Churn Recall: `0.55`
- Churn F1-score: `0.59`

---

### 🔹 Improved Model — Random Forest (Selected Model)

- **Accuracy:** `0.**7999**`
- ****ROC**-**AUC**:** `0.**8317**`

**Classification Summary:**

- Churn Precision: `0.65`
- Churn Recall: `0.52`
- Churn F1-score: `0.58`

---

## ✅ Final Model Selection

**Selected Model:** Random Forest

### 📌 Reason:

- Better **non-linear pattern learning**
- Strong **feature interaction modeling**
- Better **business interpretability**
- More robust for real-world deployment

---

## 📈 Pipeline Stages

## Data Loading

## Data Cleaning ## Feature Encoding ## Exploratory Data Analysis (EDA) ## Feature Engineering ## Train/Test Split ## Feature Scaling ## Baseline Model Training ## Advanced Model Training ## Evaluation ## Error Analysis ## Explainability (Feature Importance)

---

## 🧩 Business Value

- Identifies **high-risk churn customers**
- Helps in **customer retention strategy**
- Enables **targeted marketing & offers**
- Reduces **revenue loss**

---

## 🚀 Project Type

- Academic ML Project
- Industry-grade ML Pipeline
- Hackathon-ready
- Deployment-ready architecture

---

## 📌 Track

**Tabular Machine Learning**

---

### 🏁 Status

**Project Completed Successfully ✅**

---

> This project follows a full ML lifecycle: **EDA** → Modeling → Evaluation → Explainability → Business Interpretation
