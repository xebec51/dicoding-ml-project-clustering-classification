# 🏦 Bank Transaction Analysis using Clustering & Classification

## 📌 Project Overview

This project is part of my final submission for the **Dicoding Machine Learning Path**.
It demonstrates an end-to-end machine learning workflow by combining:

* **Unsupervised Learning (Clustering)** → to generate labels
* **Supervised Learning (Classification)** → to predict those labels

🔗 **Certificate:** https://www.dicoding.com/certificates/07Z67V952PQR

---

## 🎯 Objectives

* Perform customer segmentation based on transaction behavior
* Interpret each cluster into meaningful business insights
* Build classification models to predict customer segments

---

## 📊 Dataset

The dataset represents **bank transaction activity** including:

* Transaction amount
* Customer age
* Transaction duration
* Account balance
* Transaction channel & location
* Customer occupation

Dataset is adapted from:

> Bank Transaction Dataset for Fraud Detection (modified by Dicoding)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Handling missing values & duplicates
* Dropping ID, IP, and date-related columns
* Label Encoding for categorical features
* Outlier removal using IQR
* Feature scaling using StandardScaler
* Feature engineering (AgeGroup binning)

---

### 2. Clustering (Unsupervised Learning)

* Algorithm: **K-Means**
* Optimal cluster selection: **Elbow Method (Silhouette)**
* Silhouette Score: **0.57**
* PCA used for visualization

---

### 3. Classification (Supervised Learning)

Models used:

* Decision Tree
* Random Forest
* Hyperparameter Tuning (GridSearchCV)

---

## 📈 Results

### Clustering

* Optimal cluster: **2**
* Silhouette Score: **0.572**

### Classification Performance

All models achieved:

* Accuracy: **100%**
* Precision: **100%**
* Recall: **100%**
* F1-score: **100%**

---

## 👥 Customer Segmentation Insights

### 🔹 Cluster 0 — Conservative Customers

* Slightly older customers
* Higher account balance
* Slower transaction duration
* Lower transaction activity

📌 Insight:
Suitable for **investment products, deposits, and low-risk financial services**

---

### 🔹 Cluster 1 — Active Customers

* Slightly younger customers
* Faster transactions
* More active usage behavior
* Slightly lower account balance

📌 Insight:
Potential targets for **cashback, promotions, and digital banking engagement**

---

## 🧠 Key Takeaways

* Combining clustering and classification enables **label generation + prediction**
* Customer segmentation can directly support **business decision-making**
* Even simple models can perform extremely well with proper preprocessing

---

## 📂 Project Structure

```
.
├── notebooks/
│   ├── clustering.ipynb
│   └── classification.ipynb
├── models/
│   ├── model_clustering.h5
│   ├── decision_tree_model.h5
│   ├── explore_randomforest_classification.h5
│   └── tuning_classification.h5
├── data/
│   ├── data_clustering.csv
│   └── data_clustering_inverse.csv
├── README.md
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

Run notebooks in order:

1. Clustering
2. Classification

---

## ✨ Author

**Muh. Rinaldi Ruslan**
Information Systems Student
Hasanuddin University
