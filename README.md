# ❤️ Heart Disease Prediction Dashboard (Tableau)

This project showcases a predictive dashboard for cardiovascular disease using Tableau, powered by a dataset containing key health indicators such as blood pressure, LDL cholesterol, adiposity, and more.

<p align="center">
  <img src="heart disease prediction dashboard.png" alt="Dashboard Preview" width="600"/>
</p>

---

## 📊 Project Overview

Cardiovascular disease remains one of the leading causes of death worldwide. This dashboard aims to:

- Predict the likelihood of coronary heart disease (CHD)
- Visualize key risk factors
- Help in early identification and awareness

---

## 🧠 Features & Analysis

- 📈 **Exploratory Data Analysis** with scatter plots and dynamic filters
- 🧮 **Logistic Regression prediction** integrated with Python using Tableau's Analytics Extension (TabPy)
- 📉 **Real-time probability scoring** for CHD based on user input
- 🧠 **Behavioral & physiological insights** (Type A Personality, Age, etc.)
- 📋 **Glossary of cardiovascular terms** with icons for better interpretation

---

## 🔗 Tableau Analytics Extension (Python - TabPy)

This dashboard integrates Python scripts using **Tableau's Analytics Extension**, allowing for advanced statistical calculations directly within Tableau:

- Model trained with `scikit-learn` logistic regression
- Prediction formula embedded in calculated fields using `SCRIPT_REAL`
- Real-time CHD risk scoring based on input features
- Allows interactive simulation for "What if" health scenarios

---

## 🧪 Dataset Fields

| Variable      | Description                          |
|---------------|--------------------------------------|
| `sbp`         | Systolic Blood Pressure (mm Hg)      |
| `ldl`         | LDL Cholesterol (mmol/L)             |
| `adiposity`   | Body fat index                       |
| `tobacco`     | Lifetime tobacco usage (kg)          |
| `alcohol`     | Alcohol consumption                  |
| `typeA`       | Type A behavior pattern              |
| `age`         | Age of the individual                |
| `famhist`     | Family history of heart disease      |
| `chd`         | Presence of coronary heart disease   |

---

## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/AryaHisma/Heart-Disease-Prediction-in-Tableau.git
