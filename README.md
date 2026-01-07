# ❤️ Heart Disease Prediction using Machine Learning

This project is an end-to-end **Machine Learning application** that predicts the risk of heart disease based on patient health parameters.  
The model is trained using Python and deployed as an interactive web application using **Streamlit**.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help in timely medical intervention.  
This project uses **Logistic Regression** to classify whether a person is likely to have heart disease or not based on medical attributes.

---

## 🚀 Features

- Data preprocessing and exploratory data analysis (EDA)
- Feature scaling using StandardScaler
- Machine Learning model using Logistic Regression
- Model evaluation using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- Cross-validation for robust performance
- Deployment using Streamlit
- User-friendly interface with risk level and confidence score

---

## 🧠 Machine Learning Workflow

1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)
3. Feature-target separation
4. Train-test split with stratification
5. Feature scaling
6. Model training (Logistic Regression)
7. Model evaluation
8. Model and scaler persistence using Joblib
9. Deployment with Streamlit

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  
  - Joblib  
- **Deployment:** Streamlit  
- **Visualization:** Seaborn, Matplotlib, Plotly  

---

## 📊 Dataset

- Heart Disease Dataset
- Target Variable:
  - `0` → Healthy
  - `1` → Heart Disease
- Includes medical attributes such as:
  - Age
  - Sex
  - Chest pain type
  - Cholesterol
  - Blood pressure
  - Maximum heart rate
  - Exercise-induced angina
  - ST depression, etc.

---

## 📈 Model Performance

- Accuracy: ~85%
- Evaluated using 5-fold cross-validation
- Balanced class distribution ensured using stratified split

---

## 🖥️ Web Application (Streamlit)

The Streamlit app allows users to:
- Enter patient health details
- Get heart disease prediction
- View prediction confidence
- Understand risk level (Low / Medium / High)
- Visualize prediction probabilities

---



## ▶️ How to Run the Project

### 1️⃣ Install dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn streamlit joblib plotly
```

<img width="1912" height="897" alt="image" src="https://github.com/user-attachments/assets/57152e53-b8ea-4662-8cbe-75941f69b7fe" />
<img width="1918" height="923" alt="image" src="https://github.com/user-attachments/assets/c8626902-33ec-4ac8-9f56-dbb8b3efd5fd" />
<img width="1918" height="922" alt="image" src="https://github.com/user-attachments/assets/ac5d6269-30da-4db6-b268-7cbc5d7a86ec" />


🔗 Live App: https://heart-disease-prediction03.streamlit.app/



