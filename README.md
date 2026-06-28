# Implementasi Sistem Deteksi Keaslian Uang Kertas Berbasis Big Data

## Latar Belakang & Masalah
Peredaran uang palsu menjadi ancaman serius bagi stabilitas ekonomi. Proyek ini bertujuan untuk membangun sistem klasifikasi otomatis yang dapat membedakan uang kertas asli dan palsu berdasarkan fitur statistik tekstur gambar (variasi, kemiringan, ketajaman, keacakan).

## Metodologi & Alur Kerja
Proyek ini dikembangkan dengan siklus Data Science lengkap:
1. **Exploratory Data Analysis (EDA):** Analisis distribusi kelas target dan visualisasi fitur kontinu menggunakan Boxplot.
2. **Data Preprocessing:** Pemeriksaan missing values dan penanganan outliers menggunakan batas IQR.
3. **Feature Engineering:** Skalasi fitur menggunakan `StandardScaler` dan encoding label.
4. **Modeling:** Implementasi algoritma `RandomForestClassifier` dengan optimasi kedalaman pohon (`max_depth=5`).
5. **Deployment:** Integrasi model ke dalam aplikasi web interaktif menggunakan framework Flask.

## Hasil dan Evaluasi Model
Model Random Forest berhasil mencapai tingkat performa yang sangat tinggi:
* **Akurasi Pengujian:** 98.18%
* **F1-Score:** 0.98 untuk kelas Asli dan Palsu
* **Confusion Matrix:** Menunjukkan minimalisasi tingkat *False Positive* dan *False Negative* secara signifikan.

## Kontribusi Tim (Kelompok 2)
* **Elsya Armelya N. H. (F52124006):** Berfokus pada Data Preprocessing, Evaluasi Model (Confusion Matrix & Classification Report), serta Integrasi Dashboard Flask Deployment.
* **Samuel (F52124005):** Pengembangan Model & Feature Engineering.
* **Herdiawan (F52124016):** Eksplorasi Dataset & Visualisasi Heatmap.
* **Risky (F52124027):** Analisis Outlier & Dokumen Laporan.
