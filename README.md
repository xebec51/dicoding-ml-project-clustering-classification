# 🏦 Bank Transaction Analysis using Clustering & Classification

## 📌 Overview

Proyek ini bertujuan untuk menganalisis perilaku transaksi nasabah menggunakan kombinasi **unsupervised learning (clustering)** dan **supervised learning (classification)**.

Pendekatan:

* Clustering → membentuk segmen nasabah
* Classification → memprediksi segmen tersebut

---

## 🎯 Objectives

* Mengelompokkan nasabah berdasarkan pola transaksi
* Menginterpretasikan karakteristik setiap cluster
* Membangun model klasifikasi untuk memprediksi cluster

---

## 🧠 Methods

### 1. Clustering (Unsupervised Learning)

* Algorithm: K-Means
* Evaluation: Elbow Method + Silhouette Score
* Dimensionality Reduction: PCA

### 2. Classification (Supervised Learning)

* Decision Tree
* Random Forest
* Hyperparameter Tuning (GridSearchCV)

---

## 📊 Key Results

### Clustering

* Optimal cluster: 2
* Silhouette Score: 0.57

### Classification

* Accuracy: 100%
* Precision: 100%
* Recall: 100%
* F1-score: 100%

---

## 👥 Customer Segmentation Insight

### Cluster 1 – Active Users

* Lebih sering bertransaksi
* Durasi transaksi lebih cepat
* Saldo relatif lebih rendah
  ➡️ Cocok untuk promo & loyalty program

### Cluster 2 – Conservative Users

* Transaksi lebih stabil
* Saldo lebih tinggi
* Cenderung berhati-hati
  ➡️ Cocok untuk produk investasi & deposito

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 📂 Project Structure

(Lihat folder structure di atas)

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

Jalankan notebook atau Streamlit app (opsional).

---

## ✨ Author

Muh. Rinaldi Ruslan
