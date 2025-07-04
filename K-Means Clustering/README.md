# 🔗 K-Means Clustering – Unsupervised Learning

This project demonstrates the implementation of the **K-Means Clustering** algorithm using Scikit-learn. It covers the complete process from data visualization and preprocessing to applying the clustering algorithm and evaluating the results.

---

## 🎯 Objectives

- Understand the concept of clustering using the K-Means algorithm.
- Apply K-Means to segment unlabeled datasets.
- Visualize the clusters formed and their centroids.
- Evaluate clustering performance using the Elbow Method and Silhouette Score.

---

## 🧠 What's Inside?

### 1. Data Exploration
- Loaded a dataset suitable for clustering (e.g., make_blobs.).
- Explored feature distribution and relationships through pair plots and correlation heatmaps.

### 2. Preprocessing
- Scaled features using `StandardScaler` for distance-based learning.
- Handled missing values and feature selection if required.

### 3. Model Building
- Implemented `KMeans` from `sklearn.cluster`.
- Chose optimal number of clusters using the **Elbow Method** (`inertia_`) and **Silhouette Score**.
- Fitted the model and predicted cluster labels.

### 4. Results & Visualization
- ✅ Scatter plots of clusters with centroids.
- ✅ Visualized the Elbow Curve to determine the best `k`.
- ✅ Plotted pairwise feature clustering.

---

## 🛠️ Tech Stack

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---
