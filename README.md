# Klasifikasi Social Network Ads Menggunakan Logistic Regression

## 📌 Deskripsi Proyek
Proyek ini mengimplementasikan algoritma **Logistic Regression** untuk mengklasifikasikan apakah seorang pelanggan akan membeli produk berdasarkan data iklan media sosial (*social network ads*).

Dataset yang digunakan terdiri dari beberapa informasi pelanggan, yaitu:

- **Age** → usia pelanggan
- **EstimatedSalary** → estimasi gaji pelanggan
- **Purchased** → status pembelian produk

Model Machine Learning dibangun untuk memprediksi perilaku pembelian pelanggan berdasarkan usia dan estimasi gaji.

---

## 🎯 Tujuan Proyek
- Menganalisis hubungan antara usia, gaji, dan keputusan pembelian pelanggan.
- Mengidentifikasi pelanggan yang berpotensi membeli produk.
- Membangun model klasifikasi menggunakan algoritma Logistic Regression.
- Mengevaluasi performa model menggunakan metrik klasifikasi.

---

## 📂 Informasi Dataset

| Kolom | Deskripsi |
|---|---|
| Age | Usia pelanggan |
| EstimatedSalary | Estimasi gaji tahunan pelanggan |
| Purchased | Status pembelian (0 = Tidak membeli, 1 = Membeli) |

---

## 🛠️ Teknologi yang Digunakan
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Alur Machine Learning

### 1. Import Library
Project menggunakan beberapa library Python untuk:
- Manipulasi data
- Visualisasi data
- Pembangunan model Machine Learning

### 2. Data Preprocessing
Tahapan preprocessing meliputi:
- Pemilihan variabel independen dan dependen
- Pembagian dataset menjadi data training dan testing
- Feature scaling menggunakan `StandardScaler`

### 3. Training Model
Model yang digunakan:
- Logistic Regression

### 4. Prediksi
Model digunakan untuk memprediksi apakah pelanggan akan membeli produk berdasarkan:
- Usia
- Estimasi gaji

### 5. Evaluasi Model
Evaluasi model dilakukan menggunakan:
- Confusion Matrix
- Accuracy Score

### 6. Visualisasi
Project menampilkan:
- Visualisasi hasil training set
- Visualisasi hasil test set
- Decision boundary klasifikasi

---

## 📈 Insight yang Diharapkan
Project ini memberikan beberapa insight seperti:
- Pelanggan pada rentang usia tertentu memiliki kemungkinan lebih tinggi untuk membeli produk.
- Tingkat gaji memengaruhi keputusan pembelian pelanggan.
- Logistic Regression dapat digunakan secara efektif untuk mengklasifikasikan calon pembeli potensial.
