# LR_Classification_task5
Binary classifier using Logistic Regression
# 🔍 Logistic Regression - Binary Classification (Breast Cancer Detection)

This project implements **Logistic Regression** for binary classification using the **Breast Cancer Wisconsin Diagnostic Dataset**.

It was created as part of **AI & ML Internship - Task 4**.

---

## 📌 Project Overview
- **Goal:** Build a binary classifier using Logistic Regression.
- **Tools:**  
  - Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
  - Google Colab for execution
  - Google Drive for dataset storage

---

## 📂 Dataset
Dataset used: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

**Target Variable:** `diagnosis` (M = Malignant, B = Benign)  
**Example Features:** radius_mean, texture_mean, area_mean, etc.

---

## ⚙️ Steps Performed
1. **Load dataset** from Google Drive.
2. **Data Preprocessing:**
   - Dropped unnecessary columns (`id`, `Unnamed: 32`).
   - Converted target variable to numeric (M=1, B=0).
3. **Split dataset** into train (80%) and test (20%) sets.
4. **Standardize features** using `StandardScaler`.
5. **Train Logistic Regression Model** (`sklearn.linear_model.LogisticRegression`).
6. **Evaluate model** using:
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC Score
7. **Plot:**
   - ROC Curve
   - Sigmoid Function
8. **Tune decision threshold** and compare performance.


