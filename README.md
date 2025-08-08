# 🫀 Heart Disease Classification using Machine Learning

This project predicts the **presence of heart disease** using patient data from the **UCI Cleveland dataset**.  
It covers **end-to-end machine learning workflow** — from data exploration to final model deployment-ready evaluation.  
The goal is to create a **reliable, explainable, and accurate model** for potential medical use cases.

---

## 🎯 Objective
Predict whether a patient is likely to have heart disease based on:
- Age, sex, blood pressure, cholesterol
- ECG results, heart rate, exercise-induced angina
- And other clinical features

---

## 📊 Tools & Technologies
- **Languages/Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, CatBoost  
- **Environment:** Jupyter Notebook

---

## 📚 Dataset
- **Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Description:** Contains **clinical attributes** of patients and a binary target variable indicating the presence of heart disease.

---

## 🧠 Models Implemented
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Naive Bayes  
- Support Vector Machine (SVM)  
- XGBoost  
- CatBoost  

---

## 🏆 Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall (focus for medical sensitivity)  
- F1-Score  
- Confusion Matrix  
- ROC-AUC Curve  

---

## 🔧 Model Tuning
- Manual tuning
- **RandomizedSearchCV**
- **GridSearchCV**

---

## 📈 Final Results
- **Best Model:** Logistic Regression  
- **Accuracy:** ~84.5%  
- **Recall:** ~92.1% *(prioritized for detecting more positive cases)*  
- **F1-Score:** ~86.7%

---



## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
