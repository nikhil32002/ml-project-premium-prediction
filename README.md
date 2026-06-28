# 🏥 Healthcare Premium Prediction using Machine Learning

## 📌 Project Overview

Healthcare insurance companies calculate premium amounts based on various customer attributes such as age, Body Mass Index (BMI), smoking habits, medical history, gender, lifestyle, and other health-related factors. Manual premium estimation is often time-consuming, inconsistent, and prone to human error.

This project presents an end-to-end **Machine Learning Regression** solution that predicts healthcare insurance premiums using historical customer data. The project includes data preprocessing, exploratory data analysis (EDA), model development, hyperparameter tuning, model evaluation, deployment, and an interactive Streamlit web application that allows users to estimate insurance premiums instantly.

The primary goal is to build a highly accurate regression model that helps insurance companies automate premium estimation while ensuring consistency, efficiency, and scalability.

---

# 🎯 Problem Statement

Develop a machine learning regression model capable of predicting healthcare insurance premiums based on customer demographic, lifestyle, and medical information.

The model should achieve:

- Prediction accuracy greater than **97%**
- Less than **10% prediction error** for at least **95% of all predictions**
- Real-time prediction through an interactive Streamlit application

---

# 📊 Dataset Description

The dataset consists of customer demographic, medical, and lifestyle information used to predict healthcare insurance premiums.

| Feature | Description |
|----------|-------------|
| Age | Customer age |
| Gender | Male/Female |
| Region | Residential region |
| Marital Status | Marital Status like Married, Unmarried|
| Dependents | Number of Dependents |
| BMI Category | Body Mass Index |
| Smoking Status | Smoker / Non-Smoker |
| Employement Status | Salaried / Self-Employed |
| Income Level | Salary in LPA  |
| Medical History | Existing medical conditions |
| Blood Pressure | Blood pressure level |
| Diabetes Status | Diabetic / Non-Diabetic |


**Target Variable:** Premium Amount

---

# 🛠️ Technology Stack

| Category | Tools & Technologies |
|-----------|----------------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn, XGBoost |
| Model Serialization | Joblib, Pickle |
| Web Framework | Streamlit |
| Version Control | Git & GitHub |
| Deployment | Streamlit Community Cloud |

---

# 📊 Project Workflow

```text
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Data Preprocessing
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Best Model Selection
        │
        ▼
Model Serialization
        │
        ▼
Streamlit Application
```

---

# 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Healthcare-Premium-Prediction.git
```

### Navigate to Project Directory

```bash
cd Healthcare-Premium-Prediction
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Streamlit Application

```bash
streamlit run app.py
```

---


# 🎓 Learning Outcomes

This project demonstrates practical implementation of:

- Data collection And Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Feature Scaling
- Regression Algorithms
- Ensemble Learning
- Hyperparameter Tuning
- Model Evaluation
- Model Deployment
- Streamlit Development
- End-to-End Machine Learning Pipeline building.

---

# ✅ Conclusion

This project successfully develops a complete machine learning solution for predicting healthcare insurance premiums. By leveraging customer demographic, medical, and lifestyle information, the model accurately estimates insurance premiums while satisfying the required performance criteria.

The integration of a Streamlit application enables users to interact with the model in real time, making the solution practical, scalable, and suitable for real-world insurance applications.

---
