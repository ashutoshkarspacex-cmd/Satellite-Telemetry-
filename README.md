# 🛰️ Satellite Telemetry Anomaly Detection

> Detecting anomalies in satellite communication signals using Machine Learning.

---

## 📌 Overview
This project analyzes **satellite telemetry data** to predict whether there is an **anomaly or error in signal communication**.

The raw satellite data is noisy and unstructured, so the pipeline focuses on:
- 🧹 Data cleaning  
- 📏 Feature scaling  
- 🤖 Model implementation (from scratch + library)  
- 📊 Performance comparison  

---

## 🎯 Objectives
- Clean and preprocess raw telemetry data  
- Standardize features for stable learning  
- Build Logistic Regression models  
- Detect anomalies in communication signals  
- Compare model performances  

---

## 🛠️ Tech Stack
- 🐍 Python  
- 📦 NumPy  
- 🐼 Pandas  
- 📊 Matplotlib  
- 🤖 Scikit-learn  

---

## 📂 Dataset
- Satellite telemetry dataset  
- Split into:
  - Training set  
  - Testing set  

---

## 🔍 Project Workflow

### 🧹 Data Cleaning
- Removed inconsistencies from raw telemetry data  
- Handled noise and irregular values  
- Prepared structured dataset for modeling  

---

### 📏 Feature Scaling (Standardization)
Due to high fluctuations in telemetry signals, **StandardScaler** was applied.

Each feature is transformed using the Z-score: Y = (X - μ) / σ

✔ Mean = 0  
✔ Standard Deviation = 1  

---

## 🤖 Model Implementation

### 1️⃣ Logistic Regression (From Scratch)
- Implemented using **NumPy**  
- Includes:
  - Sigmoid function  
  - Gradient descent optimization  
  - L2 Regularization (penalizes large weights)  

---

### 2️⃣ Logistic Regression (Scikit-learn)
- Implemented using **Scikit-learn**  
- Built-in optimization and regularization  

---

## 📉 Loss Function
- **Binary Cross-Entropy Loss**
- Equivalent to maximizing **log-likelihood**

---

## 📊 Model Evaluation

Models are compared using:

- ✔ Accuracy  
- ✔ Confusion Matrix  

### 📌 Confusion Matrix Format
[ True Negatives False Positives
False Negatives True Positives]



---

## 💡 Key Highlights
✔ End-to-end ML pipeline  
✔ Handles noisy real-world telemetry data  
✔ Custom implementation of Logistic Regression  
✔ Regularization to prevent overfitting  
✔ Model comparison (from-scratch vs library)  

---

## 🚀 Future Improvements
- 🔧 Hyperparameter tuning  
- ⚡ Try advanced models (Random Forest, XGBoost)  
- 📡 Real-time anomaly detection system  
- 🌐 Deployment as monitoring dashboard  

---


