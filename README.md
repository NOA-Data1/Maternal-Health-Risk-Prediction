# Maternal Health Risk Prediction

## Overview

This project analyzes maternal health data to predict risk levels during pregnancy using a combination of **Big Data processing (PySpark)**, **SQL-based analysis**, and **Machine Learning (Neural Networks)**.

The goal is to identify high-risk cases and support data-driven decision-making in healthcare.

---

## 📊 Dataset Description

* Source: UCI Machine Learning Repository
* Link: https://archive.ics.uci.edu/dataset/863/maternal+health+risk
* License: CC BY 4.0

### Features:

* Age
* SystolicBP
* DiastolicBP
* BS (Blood Glucose)
* BodyTemp
* HeartRate
* RiskLevel (target variable)

---

## Technologies

* Python
* PySpark (Big Data processing)
* Spark SQL (data querying)
* Pandas
* Scikit-learn
* TensorFlow / Keras (MLP)
* Matplotlib & Seaborn
* Jupyter Notebook

---

## ⚙️ Methodology

### Data Processing (PySpark & SQL)

* Data ingestion using Spark
* SQL queries for analysis

### Data Preparation

* No missing values
* Label encoding
* Feature scaling

### Modeling

* Train/test split
* Neural Network (MLP)

---

## 📈 Key Insights

* Blood glucose strongly impacts risk
* Blood pressure variables are correlated
* Heart rate has low influence

---

## How to Run

```bash
git clone https://github.com/NOA-Data1/Maternal-Health-Risk-Prediction.git
cd Maternal-Health-Risk-Prediction
pip install -r requirements.txt
jupyter notebook
```

---

## 👩‍💻 Author

Nayane Oliveira

## Date
**Current Date and Time (UTC):** 2026-03-22 01:59:50
