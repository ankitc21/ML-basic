# 📊 Logistic Regression – Binary Classification

This project demonstrates binary classification using **Logistic Regression** in Python. It covers the full cycle of model development — from data analysis and preprocessing to training, evaluation, and visualization — using `scikit-learn`.

---

## 📌 Objectives

- Understand and apply logistic regression for binary classification.
- Analyze relationships between features using correlation.
- Train and test the model with accuracy evaluation.
- Use confusion matrix and classification report for detailed performance insight.

---

## 🧠 What’s Inside?

### 1. Data Handling
- Imported a dataset ('iris') suitable for binary classification.
- Explored data structure and class distribution.
- Analyzed **feature correlation** using a heatmap and `.corr()` function.

### 2. Preprocessing
- Split the dataset into training and testing sets (e.g., 75/25).
- Standardized features using `StandardScaler`.

### 3. Logistic Regression Model
- Fitted a model using `LogisticRegression` from `sklearn.linear_model`.
- Made predictions on test data.
- Evaluated model performance using:
  - ✅ **Accuracy Score**
  - ✅ **Classification Report** (Precision, Recall, F1-score)
  - ✅ **Confusion Matrix**

### 4. Visualization & Insights
- Correlation heatmap for feature understanding.
- Confusion matrix visualization using `seaborn`.
- Histogram and KDE plots for predicted vs actual comparison.

---

## 🛠️ Tech Stack

- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

