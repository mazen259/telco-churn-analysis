# 📊 Customer Churn Prediction

A Machine Learning project to predict customer churn using advanced feature engineering and ensemble models.

---

## 🚀 Project Overview

This project analyzes customer data and predicts whether a customer will leave the service (churn).

---

## 📁 Dataset

* Telco Customer Churn Dataset
* 7,000+ customers
* Includes demographics, services, and billing data

---

## 🧹 Data Preprocessing

* Handled missing values
* Fixed `TotalCharges` data type
* Feature engineering (AvgCharges, Charge_Error, etc.)
* Encoding categorical variables

---

## 🧠 Model

* XGBoost Classifier
* Tuned hyperparameters
* Cross-validation used

---

## 📈 Results

* Accuracy: **85%+**
* Key features:

  * tenure
  * MonthlyCharges
  * Contract type
  * AvgCharges

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook task4.ipynb
```

---

## 📊 Future Improvements

* Stacking models
* Hyperparameter tuning
* Deployment (Flask / Streamlit)

---

## 👨‍💻 Author

Mazen Maher
