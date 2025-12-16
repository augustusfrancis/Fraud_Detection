# 🏦 Fraud Detection in Bank Transactions using Machine Learning

This project builds a **fraud detection system for bank transactions** using a **Logistic Regression** machine learning model.  
It follows a complete end-to-end ML workflow — from **Exploratory Data Analysis (EDA)** to **model deployment as a web application using Streamlit**.
The built here is performed at approximate 94% accuracy.

In this project:
- Exploratory Data Analysis (EDA) is performed to understand data distributions, patterns, and class imbalance.
- A preprocessing pipeline is built using **OneHotEncoder** for categorical features and **StandardScaler** for numerical features.
- A **Logistic Regression** model is trained using a **scikit-learn Pipeline**.
- The trained pipeline is **serialized using joblib** and later **loaded for inference**.
- The model is deployed as an **interactive Streamlit web application**.

---

## 🔍 Key Features

- Exploratory Data Analysis (EDA) before model building  
- Feature preprocessing using:
  - OneHotEncoder (categorical variables)
  - StandardScaler (numerical variables)
- End-to-end ML pipeline using `sklearn.pipeline`
- Binary classification using Logistic Regression
- Model persistence using `joblib`
- Interactive web interface built with Streamlit

---

## 🧠 Machine Learning Pipeline

The pipeline consists of:
1. **ColumnTransformer**
   - Numerical features → StandardScaler
   - Categorical features → OneHotEncoder
2. **Logistic Regression classifier**
3. Unified pipeline for training and prediction

---

## 🖥️ Web Application (Streamlit)

The Streamlit app allows users to:
- Select transaction type
- Enter transaction amount and balance details
- Predict whether the transaction is **fraudulent or not**

The app loads the trained model using `joblib` and performs real-time predictions.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Joblib  
  - Streamlit
  - Matplotlib
  - Seaborn

---

## Dataset used 

https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download
