# 🏠 Boston Housing Price Prediction

A machine learning project to predict house prices in Boston using Linear, Ridge, and Lasso regression. This notebook explores model performance using cross-validation and regularization techniques.

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Model](https://img.shields.io/badge/Model-Linear%20Regression-orange)

---

## 📂 Project Structure


---

## 📌 Objectives

- Understand the Boston housing dataset.
- Apply linear regression for price prediction.
- Implement Ridge and Lasso regularization to improve model generalization.
- Use cross-validation and error analysis to evaluate performance.

---

## 🧠 What’s Inside?

### 1. Data Handling
- Loaded the dataset using `fetch_openml`.
- Explored feature names and statistics.
- Separated independent variables `X` and target `y`.

### 2. Preprocessing
- Performed train-test split (67/33).
- Standardized data using `StandardScaler`.

### 3. Linear Regression Model
- Fitted `LinearRegression` from `sklearn`.
- Evaluated using **cross-validation** with **negative mean squared error (MSE)**.
- Visualized error distribution with `seaborn`.
- Calculated **R² Score**.

### 4. Ridge Regression (L2 Regularization)
- Applied `Ridge()` with `GridSearchCV` to tune the `alpha` parameter.
- Predicted values and visualized error.
- Evaluated model using R² score.

### 5. Lasso Regression (L1 Regularization)
- Implemented `Lasso()` regression.
- Tuned hyperparameter using `GridSearchCV`.
- Visualized prediction error distribution.

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

---

## 🚀 Getting Started

