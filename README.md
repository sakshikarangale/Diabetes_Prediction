
# 🚀 Diabetes Prediction using Machine Learning

This project builds and evaluates machine learning models to predict whether a patient has diabetes, using the PIMA Indian Diabetes dataset.

---

## 🔍 Dataset
- **PIMA Indians Diabetes Dataset** from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- 768 samples with 8 medical features and 1 target label.

---

## 🚀 Project Workflow
- Data loading & exploration (pandas, seaborn)
- Preprocessing: feature scaling using StandardScaler
- Model training with:
  - Logistic Regression
  - Random Forest Classifier
- Evaluation using accuracy, precision, recall, F1-score & confusion matrix
- Saving trained models with joblib
- Loading & predicting new samples

---

## 🛠️ Tech Stack
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Google Colab

---

## 📈 Results
| Model              | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | ~0.76    | ~0.71     | ~0.60  | ~0.65    |
| Random Forest       | ~0.81    | ~0.78     | ~0.67  | ~0.72    |

*(Metrics may vary slightly due to random state.)*

---

## ✅ Future Work
- Build a Flask or Streamlit web app for user-friendly predictions.
- Deploy on Render or Heroku.

---
