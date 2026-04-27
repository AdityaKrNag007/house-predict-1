# 🏠 House Price Prediction (ML Project)

## 📌 Overview

Built a machine learning model to predict house prices using regression techniques. Focus was on full ML workflow: preprocessing, feature engineering, model training, and evaluation.

---

## 🧠 Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor (final model)

---

## ⚙️ Workflow

* Data cleaning & preprocessing
* Feature engineering (e.g., `HouseAge`, `TotalSF`, `Qual_GrLiv`)
* Train / Validation / Test split
* Model training and tuning

---

## 📊 Evaluation

Metric: **Mean Absolute Error (MAE)**

* Train MAE: ~183k
* Validation MAE: ~179k
* Test MAE: ~175k

---

## 🔍 Key Learnings

* Overfitting control using tree constraints
* Importance of feature engineering over model tuning
* Strong feature dominance (`OverallQual`)
* Skewed target distribution affects regression performance
* Log transformation improves stability

---

## 🚀 Future Improvements

* Try Gradient Boosting (XGBoost / LightGBM)
* Improve extreme value prediction (luxury houses)
* Advanced feature engineering

---

## 🛠 Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib
