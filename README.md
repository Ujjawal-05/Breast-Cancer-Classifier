# 🧠 Breast Cancer Classification Using Machine Learning

This project uses machine learning techniques to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer Wisconsin dataset available in `scikit-learn`.

---

## 📊 Project Summary

This notebook includes:

- Data exploration and preprocessing
- Feature scaling using `StandardScaler`
- Training and evaluation of multiple ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Performance comparison using accuracy, precision, recall, and F1 score
- Hyperparameter tuning using `GridSearchCV` and `RandomizedSearchCV`

---

## 📂 Dataset

- Source: `sklearn.datasets.load_breast_cancer()`
- Samples: 569
- Features: 30 numeric features related to tumor cell nuclei
- Target:
  - `0`: Malignant
  - `1`: Benign

---

## 🔧 Libraries Used

```bash
pandas
numpy
scikit-learn
