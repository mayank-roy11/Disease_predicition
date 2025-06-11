# 🧠 Disease Prediction using Machine Learning

This project leverages machine learning models to predict the presence of **Diabetes**, **Heart Disease**, and **Parkinson’s Disease** using publicly available datasets. It includes data preprocessing, model training (Random Forest and KNN), evaluation, visualization, and sample predictions.

---

## 📁 Datasets Used

1. **Diabetes Dataset**
   - Target column: `Outcome`
   - Binary classification (0 = No diabetes, 1 = Diabetes)

2. **Heart Disease Dataset**
   - Target column: `HeartDisease`
   - Binary classification (0 = No disease, 1 = Disease)
   - Contains categorical and numerical features

3. **Parkinson's Disease Dataset**
   - Target column: `status`
   - Binary classification (0 = Healthy, 1 = Parkinson's)

---

## 🛠 Technologies & Libraries

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (RandomForest, KNN, Pipelines, ColumnTransformer)
- Jupyter Notebook or Python script (.py)

---

## 📊 Features

- Automated data preprocessing (standardization, encoding)
- Model comparison between Random Forest and KNN
- Accuracy evaluation with:
  - Confusion Matrices
  - Classification Reports
  - Feature Importance (for Random Forest)
- Visualization of:
  - Target distribution
  - Feature importance
  - Final accuracy comparison

---

## 🧪 Model Accuracy Summary

Each dataset is evaluated with both Random Forest and KNN classifiers. Example output:

