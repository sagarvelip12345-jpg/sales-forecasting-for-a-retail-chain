# 📈 Sales Forecasting for a Retail Chain — Regression Modeling Project

![Python](https://img.shields.io/badge/Python-Data%20Science-blue?style=flat-square&logo=python)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-Retail-orange?style=flat-square)

A time-series regression project forecasting weekly retail sales, comparing five modeling approaches to identify the strongest predictor of future demand.

---

## 📌 Project Overview

This project builds an end-to-end sales forecasting pipeline for a retail chain. Weekly sales data was cleaned and transformed, time-series features were engineered (rolling averages, lag features, trend indices), and five regression approaches were trained and compared to identify the best-performing model for forecasting weekly sales.

---

## 🎯 Key Steps

1. Data cleaning and transformation of weekly retail sales data
2. Time-series feature engineering (rolling averages, lag features, trend indices)
3. Exploratory Data Analysis (EDA) to surface seasonal and regional trends
4. Model benchmarking across five regression approaches
5. Visualization of actual vs. predicted sales trends

---

## 🔍 Models Compared

| Model | R² Score |
|---|---|
| Linear Regression (baseline) | 0.530 |
| Ridge Regression | — |
| Lasso Regression | — |
| Random Forest Regression | 0.898 |
| **XGBoost Regression** | **0.942** |

XGBoost delivered the strongest fit, improving R² by ~78% relative to the Linear Regression baseline.

---

## 🛠️ Tools Used

- **Python** — core language
- **Pandas** — data cleaning and transformation
- **scikit-learn** — Linear, Ridge, Lasso, and Random Forest models
- **XGBoost** — gradient boosting regression model
- **Plotly** — actual vs. predicted sales visualizations

---

## 📈 Key Insight

Gradient boosting (XGBoost) meaningfully outperformed both the linear baseline and Random Forest on this dataset, suggesting the sales data contains non-linear seasonal and trend patterns that tree-based sequential correction captures more effectively than a single ensemble of independent trees.

---

## 👤 Author

**Sagar Velip**
🔗 https://www.linkedin.com/in/sagar-velip-7a289538b/

---

*Completed as part of the Data Science with Python Training Program — SmartED Innovations.*
