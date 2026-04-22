# 🏠 House Price Prediction using Regression Models

## 📌 Project Overview
This project demonstrates an end-to-end regression analysis pipeline to predict housing prices using multiple machine learning models.

The goal is to understand how different features affect house prices and evaluate model performance using standard regression metrics.

---

## 🎯 Objectives
- Build and understand Linear Regression models
- Apply Multiple Linear Regression on real-world datasets
- Compare Ridge and Lasso regression techniques
- Analyze residuals to validate model performance
- Improve results using feature engineering

---

## 📊 Dataset
- California Housing Dataset (Scikit-learn)

Features include:
- Median Income
- House Age
- Average Rooms
- Population
- Location-based variables

---

## ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🧠 Models Implemented
- Linear Regression
- Ridge Regression
- Lasso Regression

---

## 📈 Model Evaluation

| Model | MSE | R² Score |
|------|-----|----------|
| ## 📈 Model Evaluation Results

| Model | MSE | R² Score |
|------|-----|----------|
| Linear Regression | 0.52 | 0.61 |
| Ridge Regression | 0.50 | 0.63 |
| Lasso Regression | 0.51 | 0.62 |
## 🔍 Observation

Ridge Regression performed slightly better due to regularization, which reduced overfitting and improved generalization.

---

## 🔍 Key Insights
- Median income showed the strongest positive correlation with house prices
- Regularization (Ridge/Lasso) helped reduce overfitting
- Polynomial features slightly improved model performance

---

## 📉 Residual Analysis
Residual plots showed a mostly random distribution, indicating a good model fit with minimal bias.

---

## 🚀 Feature Engineering
- Applied Polynomial Features (degree=2)
- Improved model performance and captured non-linear relationships

---
## 📊 Visual Results

### 1. Actual vs Predicted
![Actual vs Predicted](./Actual%20vs%20predicted.png)

### 2. Residual Plot
![Residual Plot](./Residual%20plot.png)

### 3. Median Income vs Price
![Median Income](./Medinc%20vs%20House%20price.png)

### 4. House Age vs Price
![House Age](./Houseage%20vs%20price.png)

### 5. Rooms vs Price
![Rooms](./Averooms%20vs%20price.png)

### 6. Simple Linear Regression
![Simple Regression](./Simple%20linear%20regression.png)

---

## 📌 Conclusion
Ridge Regression performed best due to its ability to handle multicollinearity and reduce overfitting.

This project highlights how regression models can be applied to real-world prediction problems.

---

## 🔗 Author
Ali Abdal
