# 🟣 DBSCAN Clustering – Unsupervised Learning

This notebook demonstrates how to use **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** from Scikit-learn to identify clusters of varying density and shape. DBSCAN is effective in detecting outliers and handling non-linear cluster boundaries.

---

## 🎯 Objectives

- Understand density-based clustering using DBSCAN.
- Apply the algorithm to real-world data to identify clusters and noise points.
- Visualize clusters in two-dimensional feature space.
- Tune hyperparameters `eps` and `min_samples` for optimal clustering.

---

## 🧠 What's Inside?

### 1. Data Exploration
- Loaded a dataset suitable for density-based clustering.
- Explored feature distributions and correlations.
- Visualized data using scatter plots and correlation heatmaps.

### 2. Preprocessing
- Standardized features using `StandardScaler` to normalize distances.
- Prepared data for distance-based clustering.

### 3. DBSCAN Model
- Used `DBSCAN` from `sklearn.cluster`.
- Tuned parameters:
  - `eps`: Neighborhood radius
  - `min_samples`: Minimum points to form a dense region
- Identified clusters and labeled noise points (`-1` label).

### 4. Visualization & Evaluation
- ✅ Scatter plots of clustered points colored by cluster label.
- ✅ Highlighted noise points in visualizations.
- ✅ Explained the difference between dense clusters and outliers.

---

## 🛠️ Tech Stack

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

