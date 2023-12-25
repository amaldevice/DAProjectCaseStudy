# Laporan Proyek Machine Learning - Amalan Fadil Gaib

## Domain Proyek

Menurut Organisasi Kesehatan Dunia (WHO), stroke merupakan penyebab kematian nomor dua di dunia, yang bertanggung jawab atas sekitar 11% dari total kematian.


## Business Understanding

Dataset ini digunakan untuk memprediksi apakah seorang pasien kemungkinan besar akan terkena stroke berdasarkan parameter input seperti jenis kelamin, usia, berbagai penyakit, dan status merokok. Setiap baris dalam data memberikan informasi yang relevan tentang pasien.



### Problem Statements

Menjelaskan pernyataan masalah latar belakang:
- Ingin membuat model yang dapat memprediksi seseorang beresiko mengidap stroke atau tidak


### Goals

Menjelaskan tujuan dari pernyataan masalah:
- Membuat model yang dapat memprediksi seseorang beresiko mengidap stroke atau tidak dengan akurat




    ### Solution statements
    - Menggunakan beberapa algoritma untuk mencari akurasi model yang terbaik serta melakukan hyperparameter tuning untuk menentukan algoritma mana yang memiliki akurasi tertinggi
    

## Data Understanding
Dataset ini digunakan untuk memprediksi apakah seorang pasien kemungkinan besar akan terkena stroke berdasarkan parameter input seperti jenis kelamin, usia, berbagai penyakit, dan status merokok. Setiap baris dalam data memberikan informasi yang relevan tentang pasien. https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

### Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
1) id: pengenal unik
2) jenis kelamin: "Pria", "Wanita" atau "Lainnya"
3) usia: usia pasien
4) hipertensi: 0 jika pasien tidak memiliki hipertensi, 1 jika pasien memiliki hipertensi
5) penyakit_jantung: 0 jika pasien tidak memiliki penyakit jantung, 1 jika pasien memiliki penyakit jantung
6) pernah_menikah: "Tidak" atau "Ya"
7) jenis_pekerjaan: "anak-anak", "PNS", "Tidak pernah bekerja", "Swasta" atau "Wiraswasta"
8) Jenis_Tempat_Tinggal: "Pedesaan" atau "Perkotaan"
9) avg_glucose_level: kadar glukosa rata-rata dalam darah
10) bmi: indeks massa tubuh
11) status_merokok: "pernah merokok", "tidak pernah merokok", "merokok" atau "Tidak diketahui "*
12) stroke: 1 jika pasien mengalami stroke atau 0 jika tidak


## Data Preparation
- Pengecekan data dengan df.describe()
- Pengecekan outlier di kolom numerik
- Perbandingan kolom fitur string/object dengan variabel target(stroke)
- Pengecekan unique per kolom
- Pengecekan nilai kosong(null)
- Mengganti nilai kosong dengan nilai rata rata (mean)
- Menghapus nilai outlier
- Mengubah kolom non numeric (string) menjadi kategorical dengan pd.get_dummies
- Pengecekan korelasi kolom fitur dengan kolom target (stroke)


## Modeling
- Membagi data fitur(x) dan target (y)
- Membagi dataset menjadi 80:20 (80% train & 20% test)
- Normalisasi data dengan MinMaxScaler
- Mengimport library algoritma (LogisticRegression, DecisionTree, RandomForest, XGBoost) dan metrics (accuracy, precision, recall, f1 score)
- Mengfit model dengan dataset
- Melakukan hyperparameter dengan algoritma yang ada untuk menentukan parameter terbaik dan mendapatkan akurasi tertinggi



## Evaluation
Berdasarkan hasil modelling diatas, model RandomForest lah yang memiliki  akurasi tertinggi dibandingkan model model yang lainnya




