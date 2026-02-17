# 💰 Salary Prediction using Linear Regression

## 📌 Project Overview

This project predicts employee salary using machine learning regression techniques.
The objective is to build an interpretable and statistically sound linear regression model
and compare it with regularized models (Ridge and Lasso).

---

## 🎯 Business Problem

Organizations need salary benchmarking tools for:
- HR compensation planning
- Workforce budgeting
- Market comparison

This model predicts salary based on experience, job role, company size, and location.

---

## 📊 Dataset

Source: Kaggle Data Science Salaries Dataset

Target Variable:
- salary_in_usd

Features:
- Experience Level
- Job Title
- Company Size
- Company Location
- Employment Type
- Remote Ratio

---

## 🔎 Exploratory Data Analysis

- Checked missing values and duplicates
- Analyzed salary distribution
- Applied log transformation to reduce skewness
- Outlier detection

---

## 🧠 Feature Engineering

- One-Hot Encoding for categorical variables
- Standardized numerical features

---

## 📈 Model Building

Models Used:
- Linear Regression
- Ridge Regression
- Lasso Regression

Evaluation Metrics:
- R²
- Adjusted R²
- RMSE
- MAE

---

## 📊 Model Performance

| Model  | R² Score | RMSE |
|--------|----------|------|
| Linear | 0.71     | 0.44 |
| Ridge  | 0.72     | 0.43 |
| Lasso  | 0.73     | 0.43 |

Best Model: Lasso Regression

---

## 📌 Assumption Checks

- Residual vs Predicted Plot
- Normality of Residuals

---

## 💡 Key Insights

- Each additional year of experience increases salary by ~X%.
- Large companies pay significantly higher salaries.
- Certain job roles command premium compensation.
- Remote roles show salary variation across regions.

---

## 🚀 Deployment

Model saved using joblib.
Can be deployed using Streamlit or Flask.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---


## 👨‍💻Author - Vijaya Kumar Kanipakam

This project is part of my portfolio, showcasing the Machine Learning(ML) skills essential for data scientist roles. If you have any questions, feedback, or would like to collaborate, feel free to get in touch!

### Stay Updated and Join the Community

For more content on SQL, data analysis, and other data-related topics, make sure to follow me on social media and join our community:

- **LinkedIn**: [Connect with me professionally](https://www.linkedin.com/in/vijay-kumar-2705m/)

Thank you for your support, and I look forward to connecting with you!
