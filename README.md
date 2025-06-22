# 🩺 Prediksi Penyakit Ginjal Kronis (CKD) Menggunakan PySpark dan Random Forest

Proyek ini bertujuan untuk membangun sistem deteksi dini penyakit ginjal kronis (Chronic Kidney Disease/CKD) menggunakan algoritma **Random Forest** berbasis **PySpark**. Sistem ini dirancang untuk menganalisis data rekam medis pasien dan memprediksi apakah pasien menderita CKD atau tidak.

## 📌 Deskripsi Singkat

- 🔍 **Pendekatan**: Machine Learning dengan Random Forest
- ⚙️ **Platform**: Apache Spark (PySpark)
- 🧼 **Tahapan Proyek**:
  - Preprocessing dan pembersihan data
  - Pembuatan pipeline ML dengan Spark MLlib
  - Evaluasi model menggunakan akurasi dan AUC
  - Visualisasi hasil menggunakan ROC Curve dan Confusion Matrix

## 📁 Dataset

- **Nama**: Chronic Kidney Disease Dataset
- **Sumber**: UCI Machine Learning Repository
- **Link**: [UCI CKD Dataset](https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease)
- **Jumlah Data**: 400 baris, 25 atribut (numerik & kategorikal)

## 🛠️ Teknologi dan Library

- Python
- PySpark
- Apache Spark 3.x
- Matplotlib
- Seaborn
- Scikit-learn
- Pandas

## 📊 Hasil Evaluasi

- **Akurasi Model**: 100%
- **Area Under Curve (AUC)**: 1.000
- **Visualisasi**:
  - ROC Curve menunjukkan performa sempurna
  - Confusion Matrix tanpa kesalahan klasifikasi

## 🚀 Cara Menjalankan Proyek

1. **Install Library** (jika belum tersedia):
   ```bash
   pip install pyspark matplotlib scikit-learn seaborn pandas
2. Jalankan Notebook atau Script Python yang telah disediakan (CKD_Prediction.ipynb).

3. Pastikan Dataset kidney_disease.csv tersedia di direktori kerja.

**🧠 Algoritma yang Digunakan**
Random Forest Classifier
- Ensemble Learning berbasis Decision Tree
- Tuning parameter dengan TrainValidationSplit

**👩‍💻 Kontributor**
Desi Dwi Purwasih – Telkom University (PJJ Informatika)
Proyek Tugas Besar – AI & Big Data untuk Kesehatan
