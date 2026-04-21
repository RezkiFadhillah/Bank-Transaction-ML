# 🏦 Bank Transaction Analyzer: Hybrid ML Approach
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Dicoding](https://img.shields.io/badge/Credential-Dicoding%20Final%20Project-red)](https://www.dicoding.com/)

Proyek ini menerapkan pendekatan **Hybrid Machine Learning** dengan menggabungkan teknik *Unsupervised Learning* untuk segmentasi nasabah dan *Supervised Learning* untuk klasifikasi otomatis transaksi perbankan.

---

## 🚀 Overview Proyek
Mengubah data transaksi bank yang tidak berlabel menjadi wawasan bisnis yang berharga. Proyek ini mendemonstrasikan bagaimana pola tersembunyi dalam data transaksi dapat diekstraksi dan digunakan untuk membangun model klasifikasi yang akurat.

### 🧠 Workflow Analisis
1. **EDA & Preprocessing:** Pembersihan data, penanganan outlier, dan penskalaan fitur.
2. **Clustering (K-Means):** Segmentasi data transaksi menjadi kelompok-kelompok homogen menggunakan *Elbow Method*.
3. **Dimensionality Reduction (PCA):** Visualisasi data kompleks ke dalam ruang 2D/3D untuk interpretasi cluster.
4. **Classification:** Pelatihan model **Decision Tree** & **Random Forest** untuk memprediksi kategori transaksi berdasarkan hasil clustering.
5. **Hyperparameter Tuning:** Optimasi model menggunakan *GridSearchCV* untuk mencapai akurasi maksimal.

---

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Yellowbrick
- **Tools:** VS Code, Git, Jupyter Notebook, Joblib

---

## 📁 Struktur Proyek
📂 **BMLP_Rezki-Fadhillah**
├── 📂 **data/**          # Dataset original & hasil clustering
├── 📂 **models/**        # Model ML yang sudah dilatih (.h5)
├── 📂 **notebooks/**     # Dokumentasi langkah demi langkah (Clustering & Klasifikasi)
├── 📄 **.gitignore**     # File yang diabaikan oleh Git
└── 📄 **README.md**      # Dokumentasi Utama

---

## 📊 Hasil Utama
- **Clustering:** Berhasil mengidentifikasi segmen nasabah berdasarkan perilaku transaksi.
- **Visualisasi PCA:** Menunjukkan separasi cluster yang jelas.
- **Model Classification:** Model Random Forest yang telah di-tuning mencapai akurasi **>90%**, memberikan performa yang sangat handal untuk klasifikasi transaksi baru.

---

## 👨‍💻 Author
**Rezki Fadhillah**
- LinkedIn: [Rezki Fadhillah](https://linkedin.com/in/rezkifadhillah) 
- GitHub: [@RezkiFadhillah](https://github.com/RezkiFadhillah)

---
*Proyek ini diselesaikan sebagai bagian dari persyaratan kelulusan kelas Machine Learning di Dicoding Indonesia.*