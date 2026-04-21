# Bank Transaction Clustering & Classification 🚀

Proyek ini adalah sistem Machine Learning terintegrasi yang menggabungkan pendekatan **Unsupervised Learning** (Clustering) untuk segmentasi data dan **Supervised Learning** (Classification) untuk memprediksi label hasil segmentasi tersebut.

Proyek ini merupakan bagian dari submission akhir kelas Machine Learning di **Dicoding Indonesia**.

## 📌 Deskripsi Proyek
Sistem ini menganalisis dataset transaksi bank untuk menemukan pola tersembunyi antar nasabah. Proses dibagi menjadi dua tahap utama:
1. **Clustering:** Menggunakan algoritma **K-Means** untuk mengelompokkan data berdasarkan fitur transaksi. Jumlah cluster optimal ditentukan menggunakan **Elbow Method**.
2. **Classification:** Membangun model prediksi menggunakan **Decision Tree** dan **Random Forest** untuk mengklasifikasikan data baru ke dalam cluster yang telah terbentuk.

## 🛠️ Fitur & Metodologi
- **Preprocessing:** Handling outliers, Feature Scaling (StandardScaler), dan Feature Encoding.
- **Dimensionality Reduction:** Menggunakan **PCA** untuk visualisasi cluster yang lebih baik.
- **Hyperparameter Tuning:** Optimasi model klasifikasi menggunakan **GridSearchCV**.
- **Model Persistence:** Semua model disimpan dalam format `.h5` menggunakan library `joblib`.

## 📊 Hasil Evaluasi
Model klasifikasi akhir (Tuned Random Forest) mencapai performa sebagai berikut:
- **Accuracy:** Tinggi (Diatas 90%)
- **F1-Score:** Konsisten pada tiap kelas.

## 📁 Struktur Folder
- `[Clustering]...ipynb`: Notebook proses clustering & EDA.
- `[Klasifikasi]...ipynb`: Notebook proses klasifikasi & tuning.
- `*.h5`: Model machine learning yang sudah dilatih.
- `*.csv`: Dataset hasil olahan.

## 🚀 Cara Menjalankan
1. Clone repository ini.
2. Install library yang dibutuhkan: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `yellowbrick`, `joblib`.
3. Jalankan notebook secara berurutan mulai dari Clustering.

---
**Author:** Rezki Fadhillah