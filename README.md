# 🤖 Dasar Machine Learning & Klasifikasi Menggunakan K-Nearest Neighbors (KNN)

Modul praktikum pertama ini berfokus pada pemahaman alur kerja dasar *Machine Learning* menggunakan bahasa pemrograman Python. Studi kasus utama yang digunakan adalah klasifikasi spesies bunga **Iris** dengan mengimplementasikan algoritma **K-Nearest Neighbors (KNN)**.

---

## 📂 Struktur & Materi Pembelajaran

1. **Import Library:** Mengimpor pustaka esensial seperti `NumPy`, `Pandas`, `Matplotlib`, `Seaborn`, dan modul dari `Scikit-Learn`.
2. **Memuat Dataset:** Memuat dataset bawaan Scikit-Learn (`load_iris()`), memisahkan fitur ($X$) dan label target ($y$).
3. **Eksplorasi Data (EDA):** Menggunakan `df.head()`, `df.describe()`, dan visualisasi `sns.pairplot()` untuk melihat sebaran data antar fitur (ditemukan bahwa *petal length* dan *petal width* adalah pembeda terkuat).
4. **Data Splitting:** Membagi data menjadi *training set* (70%) dan *testing set* (30%) menggunakan `train_test_split`.
5. **Model Training & Evaluation:** Melatih model KNN ($k=3$), melakukan prediksi, serta mengukur performa menggunakan Akurasi (mencapai 100%), *Confusion Matrix*, dan *Classification Report*.
6. **Eksperimen & Tugas Tambahan:**
   * **Variasi Parameter $k$:** Menguji nilai $k = 1, 3, 5, 7$ untuk melihat sensitivitas model terhadap tetangga terdekat.
   * **Algoritma Alternatif:** Mengganti model KNN dengan *Decision Tree*.
   * **Uji Coba Dataset Lain:** Menguji alur klasifikasi pada `load_wine()` dan regresi pada `load_diabetes()` (menggunakan metrik MSE/$R^2$ Score).
   * **Analisis Korelasi:** Memeriksa hubungan antar fitur menggunakan matriks korelasi (`df.corr()`).

---

## 🛠️ Tech Stack
* **Python**
* **Scikit-Learn** (KNN, Decision Tree, Metrics)
* **Pandas & NumPy** (Manipulasi & Komputasi Data)
* **Matplotlib & Seaborn** (Visualisasi Data)

---

## 🚀 Cara Menjalankan
1. Clone atau unduh folder ini.
2. Buka berkas berformat `.ipynb` menggunakan **Jupyter Notebook** atau **Google Colab**.
3. Jalankan sel kode secara berurutan dari atas ke bawah.
