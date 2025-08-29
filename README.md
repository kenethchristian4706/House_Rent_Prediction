# 🏠 House Rent Predictor

A machine learning project that predicts house rental prices based on property features such as size, number of bedrooms (BHK), bathrooms, furnishing status, city, and locality.

This project demonstrates **end-to-end ML workflow**: data cleaning, feature engineering, exploratory data analysis (EDA), model training, and evaluation.

---

## ✨ Features

* 📊 **Exploratory Data Analysis (EDA)** to understand rent distribution & outliers
* 🧹 **Data Preprocessing**: handling categorical variables, missing values, and outliers
* 🏘️ **Locality Target Encoding** to capture area-specific rent variations
* 📈 **Machine Learning Models**: Linear Regression (with R² and Adjusted R² evaluation)
* 📉 Outlier handling for better model accuracy
* 🧮 Achieved **85%+ accuracy (R² score)** with feature engineering

---

## 📂 Dataset

* Columns include: `BHK`, `Size`, `Floor`, `Area Type`, `Area Locality`, `City`, `Furnishing Status`, `Tenant Preferred`, `Bathroom`, etc.
* Target variable: **Rent**

---

## 🚀 Tech Stack

* Python 🐍
* Pandas, NumPy
* Scikit-learn (Linear Regression, metrics)
* Matplotlib, Seaborn (visualization)
* Jupyter Notebook

---

## 📊 Results

* Baseline Linear Regression: \~50% R²
* After Locality Target Encoding + Outlier Removal: **\~85% R²**
* Demonstrates importance of feature engineering in housing datasets

---

## 🔮 Future Improvements

* Try advanced ML models (Random Forest, XGBoost, LightGBM)
* Build a web app (Streamlit/Django/Flask) for user input & predictions
* Deploy on cloud (Heroku, AWS, or Hugging Face Spaces)

---

👉 You can paste this directly into your repo’s **README.md**.

Do you want me to also create a **short one-liner repo description** (like GitHub’s “About” section) for your project?
