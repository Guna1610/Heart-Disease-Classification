# 🫀 Heart Disease Classification using Machine Learning

This project predicts the presence of heart disease using clinical data from the UCI Cleveland dataset. It explores multiple ML models and applies advanced evaluation to ensure medical accuracy.

## 📁 Project Structure
- **Notebook:** End-to-end Jupyter notebook (`.ipynb`) with EDA, model training, evaluation, and hyperparameter tuning.
- **Models Used:** Logistic Regression, KNN, Decision Tree, Random Forest, Naive Bayes, SVM, XGBoost, CatBoost.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC Curve.
- **Tuning:** Manual tuning, `RandomizedSearchCV`, and `GridSearchCV`.

## 📊 Results
- Final model: **Logistic Regression**
- Accuracy: ~84.5%
- Recall: ~92.1%
- F1-Score: ~86.7%

## 🛠 Tech Stack
Python, Scikit-learn, XGBoost, CatBoost, Pandas, NumPy, Matplotlib, Seaborn

## 📚 Dataset
UCI Heart Disease dataset  
[🔗 Kaggle Link](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
