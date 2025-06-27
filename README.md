# 🏥 Insurance Premium Prediction

This project predicts **insurance premium costs** using machine learning based on features like **age**, **BMI**, **smoking habits**, and more.  
Inspired by the [Codebasics ML Course](https://www.youtube.com/@codebasics), this project walks through data cleaning, exploratory data analysis (EDA), regression modeling, and evaluation using real-world datasets.

---

## 🧭 Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Dataset](#dataset)  
4. [ML Models Used](#ml-models-used)  
5. [Evaluation Metrics](#evaluation-metrics)  
6. [Tech Stack](#tech-stack)  

---

## 📌 Overview

This machine learning project predicts **health insurance charges** based on individual attributes.  
It covers the full ML pipeline:

- Exploratory Data Analysis (EDA)  
- Preprocessing (encoding, scaling)  
- Regression model building and selection  
- Performance evaluation  

---

## ✅ Features

- 📊 **Exploratory Data Analysis (EDA)**:  
  - Correlation heatmaps  
  - Pairplots for relationships between features and charges  
  - Distribution plots (e.g., smoker vs. non-smoker)

- 🧹 **Data Preprocessing**:
  - Handle missing values (if any)
  - Encode categorical columns (e.g., region, sex, smoker)
  - Scale numerical features

- 🧠 **Machine Learning Models**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Ridge & Lasso Regression

- 📈 **Model Evaluation**:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared Score (R²)

---

## 📦 Dataset

- Source: `insurance.csv` (from Codebasics course)
- Total records: 1,338 rows
- Columns:

| Feature      | Type         | Description                             |
|--------------|--------------|-----------------------------------------|
| `age`        | Numerical     | Age of individual                       |
| `sex`        | Categorical   | Male/Female                             |
| `bmi`        | Numerical     | Body Mass Index                         |
| `children`   | Numerical     | No. of dependent children               |
| `smoker`     | Categorical   | Smoker status                           |
| `region`     | Categorical   | Area of residence                       |
| `charges`    | Target        | Insurance premium to be predicted       |

---

## 🧠 ML Models Used

The following regression algorithms were implemented and compared:

- 📈 Linear Regression  
- 🌳 Decision Tree Regressor  
- 🌲 Random Forest Regressor  
- ➕ Ridge Regression  
- ➖ Lasso Regression  

---

## 📏 Evaluation Metrics

| Metric        | Description                                  |
|---------------|----------------------------------------------|
| MSE           | Measures average squared difference          |
| RMSE          | Square root of MSE (scale-sensitive)         |
| R-squared (R²)| Measures % of variance explained by model    |

---

## 🧱 Tech Stack

- **Language**: Python  
- **Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn  
- **Model Export**: pickle or joblib  
- **Optional Deployment**: Flask / Streamlit

---
