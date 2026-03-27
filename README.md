# **Customer Segmentation & Classification (Machine Learning Project)**

<p align="center">
  <a href="https://github.com/xebec51">
    <img src="https://img.shields.io/badge/GitHub-xebec51-blue?logo=github" />
  </a>
  <a href="https://www.instagram.com/rinaldiruslan/">
    <img src="https://img.shields.io/badge/Instagram-rinaldiruslan-E4405F?logo=instagram" />
  </a>
  <a href="https://www.tiktok.com/@rinaldiruslan">
    <img src="https://img.shields.io/badge/TikTok-rinaldiruslan-000000?logo=tiktok&logoColor=white" />
  </a>
  <br/>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" />
  </a>
  <img src="https://img.shields.io/badge/Machine%20Learning-Clustering%20%26%20Classification-orange" />
</p>

---

🌐 **Final Submission dari Kelas**:
[Belajar Machine Learning untuk Pemula - Dicoding](https://www.dicoding.com/academies/184)

🎓 **Sertifikat**:
https://www.dicoding.com/certificates/07Z67V952PQR

---

## **📌 Deskripsi Proyek**

Proyek ini merupakan implementasi **end-to-end machine learning pipeline** yang menggabungkan:

* **Unsupervised Learning (Clustering)** untuk membentuk label data
* **Supervised Learning (Classification)** untuk memprediksi label tersebut

Dataset yang digunakan merepresentasikan **aktivitas transaksi perbankan**, sehingga proyek ini relevan untuk:

* Customer segmentation
* Behavioral analysis
* Fraud/anomaly exploration

---

## 🚀 **Key Highlights**

* ✅ End-to-end ML pipeline (Clustering → Classification)
* ✅ Feature engineering & preprocessing lengkap
* ✅ Visualisasi clustering menggunakan PCA
* ✅ Silhouette Score sebagai evaluasi clustering
* ✅ Multiple classification models + hyperparameter tuning
* ✅ Interpretasi bisnis dari hasil clustering

---

## 📊 **Dataset Overview**

Dataset mencakup berbagai fitur penting seperti:

* Transaction Amount
* Customer Age
* Transaction Duration
* Account Balance
* Transaction Channel & Location
* Customer Occupation

Dataset telah melalui proses:

* Data cleaning
* Encoding
* Scaling
* Outlier handling

---

## ⚙️ **Metodologi**

### **1. Data Preprocessing**

* Handling missing values & duplicates
* Drop fitur ID, IP Address, dan Date
* Label Encoding untuk fitur kategorikal
* Outlier removal menggunakan IQR
* Feature scaling dengan StandardScaler
* Feature engineering (AgeGroup binning)

---

### **2. Clustering (Unsupervised Learning)**

* Algoritma: **K-Means**
* Penentuan cluster: **Elbow Method + Silhouette Score**
* Jumlah cluster optimal: **2**
* Silhouette Score: **0.57**
* Visualisasi menggunakan **PCA**

---

### **3. Classification (Supervised Learning)**

Model yang digunakan:

* Decision Tree
* Random Forest
* Hyperparameter tuning (GridSearchCV)

---

## 📈 **Hasil Model**

### 🔹 Clustering

* Jumlah cluster: **2**
* Silhouette Score: **0.572**

### 🔹 Classification

Semua model menghasilkan performa:

* Accuracy: **100%**
* Precision: **100%**
* Recall: **100%**
* F1-score: **100%**

---

## 👥 **Insight Segmentasi Nasabah**

### 🔹 Cluster 0 — Nasabah Stabil & Konservatif

* Usia sedikit lebih tua
* Saldo lebih tinggi
* Durasi transaksi lebih lama
* Aktivitas transaksi lebih rendah

📌 **Rekomendasi:**
Cocok untuk produk:

* Deposito
* Tabungan berjangka
* Investasi risiko rendah

---

### 🔹 Cluster 1 — Nasabah Aktif & Digital

* Usia lebih muda
* Transaksi lebih cepat
* Aktivitas lebih tinggi
* Saldo relatif lebih rendah

📌 **Rekomendasi:**
Cocok untuk:

* Promo digital banking
* Cashback transaksi
* Loyalty program

---

## 📂 **Struktur Proyek**

```bash
.
├── [Clustering]_Submission_Akhir_BMLP.ipynb
├── [Klasifikasi]_Submission_Akhir_BMLP.ipynb
├── model_clustering.h5
├── PCA_model_clustering.h5
├── decision_tree_model.h5
├── explore_randomforest_classification.h5
├── tuning_classification.h5
├── data_clustering.csv
├── data_clustering_inverse.csv
├── README.md
```

---

## ▶️ **Cara Menjalankan**

### **Prasyarat**

* Python 3.x
* Jupyter Notebook / Google Colab

### **Langkah**

1. Clone repository:

```bash
git clone https://github.com/xebec51/<nama-repo-anda>.git
```

2. Masuk ke folder:

```bash
cd <nama-repo-anda>
```

3. Jalankan notebook secara berurutan:

* Clustering
* Klasifikasi

---

## 🧠 **Insight Utama**

* Clustering dapat digunakan untuk **membuat label dari data tanpa label**
* Classification dapat memanfaatkan hasil tersebut untuk **prediksi otomatis**
* Kombinasi ini sangat powerful dalam kasus nyata seperti:

  * Customer segmentation
  * Fraud detection
  * Behavioral analytics

---

## 🛠️ **Teknologi yang Digunakan**

* **Python**
* **Pandas & NumPy**
* **Scikit-learn**
* **Seaborn & Matplotlib**
* **Yellowbrick**

---

## 👤 **Author**

**Muh. Rinaldi Ruslan**

* 📧 Email: [rinaldi.ruslan51@gmail.com](mailto:rinaldi.ruslan51@gmail.com)
* 💻 GitHub: https://github.com/xebec51
* 📸 Instagram: https://www.instagram.com/rinaldiruslan/
* 🎵 TikTok: https://www.tiktok.com/@rinaldiruslan

---

## 📄 **Lisensi**

Proyek ini dilisensikan di bawah **MIT License**.
