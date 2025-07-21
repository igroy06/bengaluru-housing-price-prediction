# 🏡 House Price Prediction using Linear Regression

This project focuses on predicting house prices using a **Linear Regression** model. The workflow involves comprehensive **data cleaning**, **feature engineering**, **outlier detection**, **dimensionality reduction**, and **K-Fold cross-validation** for robust model evaluation.

---


## 🧠 Problem Statement

Given a dataset of houses with various features (e.g., area, number of rooms, year built), predict the **sale price** of a house. The dataset contains both numerical and categorical features.

---

## ✅ Workflow Overview

### 1. 🔍 Data Cleaning
- Handle missing values using appropriate strategies (mean, mode, or custom imputation).
- Remove duplicate entries.
- Convert data types as needed (e.g., categorical to object/string).

### 2. 🛠️ Feature Engineering
- Transform categorical variables using One-Hot Encoding or Label Encoding.
- Create new features (e.g., price per square foot).
- Normalize or scale numerical variables.

### 3. 📉 Outlier Detection
- Use visualization (box plots, scatter plots) and statistical methods (IQR, Z-score) to identify outliers.
- Remove or cap extreme values to reduce skewness and improve model performance.

### 4. 📐 Dimensionality Reduction
- Reduce feature space while retaining most of the variance.
- Helps in avoiding overfitting and improving training speed.

### 5. 🔁 Model Training with K-Fold Cross-Validation
- Use **K-Fold Cross Validation (e.g., K=5 or 10)** to evaluate model performance more reliably.
- Helps detect variance and bias by testing the model on multiple folds of the data.

---

## 📊 Model Used

- **Linear Regression** (from `scikit-learn`)
- Regularization (optional): Ridge or Lasso to handle multicollinearity and overfitting.

---

## ⚙️ Dependencies

```bash
scikit-learn
pandas
numpy
matplotlib
seaborn
jupyter



