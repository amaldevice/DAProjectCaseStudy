# Laporan Proyek Machine Learning - Amalan Fadil Gaib

## Domain Proyek

Menurut Organisasi Kesehatan Dunia (WHO), stroke merupakan penyebab kematian nomor dua di dunia, yang bertanggung jawab atas sekitar 11% dari total kematian.

### Dampak stroke secara lokal di Jakarta

Berdasarkan data dari Dinas Kesehatan Provinsi DKI Jakarta (Dinkes DKI Jakarta), prevalensi stroke di Jakarta pada tahun 2022 adalah 12,2%. Hal ini berarti, dari setiap 1.000 orang di Jakarta, terdapat 122 orang yang berisiko terkena stroke.

Prevalensi stroke di Jakarta lebih tinggi dibandingkan dengan prevalensi stroke secara nasional. Hal ini dapat disebabkan oleh beberapa faktor, antara lain:

#### Faktor demografi
Jakarta merupakan kota metropolitan dengan tingkat urbanisasi yang tinggi. Urbanisasi dapat meningkatkan risiko stroke karena beberapa faktor, seperti stres, pola makan yang tidak sehat, dan kurang aktivitas fisik.

#### Faktor lingkungan
Kualitas udara di Jakarta yang buruk juga dapat meningkatkan risiko stroke. Polusi udara dapat menyebabkan kerusakan pembuluh darah, yang dapat meningkatkan risiko stroke.

#### Faktor ekonomi
Jakarta merupakan kota dengan tingkat ekonomi yang tinggi. Namun, tingkat ekonomi yang tinggi tidak selalu diikuti dengan gaya hidup yang sehat. Gaya hidup yang tidak sehat, seperti merokok dan konsumsi alkohol berlebihan, dapat meningkatkan risiko stroke.

### Dampak stroke secara nasional

Stroke merupakan salah satu penyebab kematian dan kecacatan terbesar di Indonesia. Menurut data Kemenkes RI, pada tahun 2022, stroke menjadi penyebab kematian ke-4 di Indonesia. Sekitar 7% kematian di Indonesia disebabkan oleh stroke.

Selain menyebabkan kematian, stroke juga dapat menyebabkan berbagai macam kecacatan, seperti:

- Kelumpuhan
- Gangguan bicara
- Gangguan penglihatan
- Gangguan ingatan
- Gangguan emosi

Kecacatan akibat stroke dapat berdampak signifikan pada kehidupan penderita dan keluarganya. Penderita stroke yang mengalami kecacatan berat seringkali membutuhkan bantuan orang lain untuk melakukan aktivitas sehari-hari. Hal ini dapat menimbulkan beban ekonomi dan psikologis bagi keluarga.

Berdasarkan data dari BPJS Kesehatan, pada tahun 2022, biaya pelayanan kesehatan untuk stroke mencapai Rp2,7 triliun. Biaya ini ditanggung oleh pemerintah melalui program Jaminan Kesehatan Nasional (JKN).

#### Upaya pencegahan dan pengendalian stroke

Ada beberapa hal yang dapat dilakukan untuk mencegah dan mengendalikan stroke, antara lain:

* Menjaga tekanan darah, gula darah, dan kolesterol dalam batas normal
Tekanan darah tinggi, diabetes, dan kolesterol tinggi merupakan faktor risiko utama stroke. Oleh karena itu, penting untuk menjaga ketiga faktor risiko ini dalam batas normal.

* Menghentikan merokok
Merokok merupakan faktor risiko utama stroke. Oleh karena itu, penting untuk berhenti merokok jika Anda ingin mencegah stroke.

* Mengurangi konsumsi alkohol
Konsumsi alkohol berlebihan merupakan faktor risiko stroke. Oleh karena itu, penting untuk membatasi konsumsi alkohol.

* Melakukan aktivitas fisik secara teratur
Aktivitas fisik secara teratur dapat membantu menurunkan tekanan darah, gula darah, dan kolesterol. Selain itu, aktivitas fisik juga dapat membantu menjaga berat badan ideal.

* Menjaga berat badan ideal
Obesitas merupakan faktor risiko stroke. Oleh karena itu, penting untuk menjaga berat badan ideal.

* Mengonsumsi makanan yang sehat dan bergizi
Konsumsi makanan yang sehat dan bergizi dapat membantu menurunkan tekanan darah, gula darah, dan kolesterol.

Selain itu, penting juga untuk melakukan pemeriksaan kesehatan secara rutin, terutama bagi orang yang memiliki faktor risiko stroke. Pemeriksaan kesehatan dapat membantu mendeteksi stroke secara dini sehingga dapat dilakukan penanganan yang tepat.


## Business Understanding

Berikut adalah beberapa statistik yang mendukung pentingnya memprediksi risiko stroke:

- Menurut data dari Kementerian Kesehatan Republik Indonesia (Kemenkes RI), prevalensi stroke di Indonesia pada tahun 2022 adalah 1,7%. Hal ini berarti, dari     setiap 1.000 orang di Indonesia, terdapat 17 orang yang berisiko terkena stroke.

- Stroke merupakan salah satu penyebab kematian dan kecacatan terbesar di Indonesia. Menurut data Kemenkes RI, pada tahun 2022, stroke menjadi penyebab           kematian ke-4 di Indonesia. Sekitar 7% kematian di Indonesia disebabkan oleh stroke.

- Berdasarkan data dari Badan Penyelenggara Jaminan Sosial (BPJS) Kesehatan, pada tahun 2022, biaya pelayanan kesehatan untuk stroke mencapai Rp2,7 triliun.      Biaya ini ditanggung oleh pemerintah melalui program Jaminan Kesehatan Nasional (JKN).

Dari contoh konkret dan statistik di atas, dapat disimpulkan bahwa memprediksi risiko stroke sangat penting untuk mencegah terjadinya stroke, mengurangi angka kematian dan kecacatan akibat stroke, serta mengurangi beban ekonomi bagi penderita dan keluarganya.



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

### Numerical Variable
![download](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/c8f84f01-4812-4db2-ac70-434a1db39d84)
Gambar diatas merupakan boxplot dari kolom id yang dimana tidak terdeteksi outlier

![download (1)](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/09dab5d8-c462-49d9-9780-efa026191b5a)
Gambar diatas merupakan boxplot dari kolom age yang dimana tidak terdeteksi  outlier

![download (2)](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/70ea9cc9-a853-467b-be59-f76dab753a8a)
Gambar diatas merupakan boxplot dari kolom avg_glucose_level yang dimana terdeteksi beberapa outlier
                                            
![download (3)](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/98d805bc-efd2-4380-99e7-dab154f812fd)
Gambar diatas merupakan boxplot dari kolom bmi yang dimana terdeteksi beberapa outlier

### Categorical Variable

![smokingstatus](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/78828a82-deef-4e76-a123-653fe542358b)

Berdasarkan grafik tersebut, berikut adalah beberapa analisis yang dapat diambil:

Orang yang tidak pernah merokok memiliki risiko stroke terendah: Jumlah orang yang tidak pernah merokok dan tidak mengalami stroke adalah yang tertinggi di antara semua kategori. Selain itu, mereka yang tidak pernah merokok juga memiliki jumlah orang yang paling sedikit yang mengalami stroke.

Merokok dapat meningkatkan risiko stroke: Meskipun jumlah orang yang merokok dan mengalami stroke tidak sebanyak orang yang tidak pernah merokok, namun jika kita melihat proporsi antara mereka yang merokok dan mengalami stroke dengan mereka yang merokok dan tidak mengalami stroke, kita bisa melihat bahwa merokok tampaknya meningkatkan risiko stroke.

![residence](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/b1f02239-9312-4a19-80cf-f40cc3c222ec)

Grafik ini menunjukkan perbandingan antara jumlah orang dengan dan tanpa stroke di area urban dan rural. Berikut adalah beberapa analisis yang dapat diambil:

Jumlah Kasus Stroke Rendah: Jumlah orang yang mengalami stroke sangat rendah dibandingkan dengan mereka yang tidak, baik di area perkotaan maupun pedesaan. Ini menunjukkan bahwa stroke mungkin bukan penyakit yang umum di populasi ini.

Distribusi Kasus Stroke: Distribusi kasus stroke antara area perkotaan dan pedesaan tampaknya hampir sama. Ini menunjukkan bahwa tempat tinggal (urban atau rural) mungkin tidak memiliki pengaruh besar terhadap risiko stroke.

Perbandingan antara Urban dan Rural: Meskipun ada sedikit lebih banyak orang yang tinggal di area perkotaan yang mengalami stroke dibandingkan dengan mereka yang tinggal di area pedesaan, perbedaannya tidak signifikan.

![worktype](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/fb839e19-4c63-4648-9e95-fdc6ab725ce0)

Grafik ini menunjukkan perbandingan antara jumlah orang dengan dan tanpa stroke berdasarkan jenis pekerjaan mereka. Berikut adalah beberapa analisis yang dapat diambil:

Sektor Swasta memiliki Insiden Stroke Tertinggi: Orang yang bekerja di sektor swasta memiliki insiden stroke tertinggi dibandingkan dengan jenis pekerjaan lainnya. Ini mungkin karena faktor-faktor seperti stres kerja atau gaya hidup yang tidak sehat.

Insiden Stroke Rendah di Kalangan yang Belum Pernah Bekerja: Mereka yang belum pernah bekerja memiliki insiden stroke terendah. Ini mungkin karena kelompok ini sebagian besar terdiri dari anak-anak atau orang muda yang umumnya memiliki risiko stroke yang lebih rendah.

Jumlah Kasus Stroke Rendah: Secara umum, jumlah kasus stroke sangat rendah dibandingkan dengan mereka yang tidak mengalami stroke di semua jenis pekerjaan. Ini menunjukkan bahwa stroke mungkin bukan penyakit yang umum di populasi ini.

![evermarid](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/1f9204cb-22f2-4441-a9d7-83fc4c8aac8b)

Grafik ini menunjukkan perbandingan antara jumlah orang dengan dan tanpa stroke berdasarkan status perkawinan mereka. Berikut adalah beberapa analisis yang dapat diambil:

Orang yang Pernah Menikah memiliki Insiden Stroke yang Lebih Rendah: Orang yang pernah menikah memiliki insiden stroke yang lebih rendah dibandingkan dengan mereka yang belum pernah menikah. Ini terlihat dari jumlah orang tanpa stroke (ditandai dengan warna biru) yang lebih tinggi pada kelompok yang pernah menikah.

Jumlah Kasus Stroke Rendah: Secara umum, jumlah kasus stroke sangat rendah dibandingkan dengan mereka yang tidak mengalami stroke di kedua kategori. Ini menunjukkan bahwa stroke mungkin bukan penyakit yang umum di populasi ini.

![gender](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/da3f8105-dea3-4a08-b78f-d3fdf461a369)

Grafik ini menunjukkan perbandingan kasus stroke berdasarkan jenis kelamin. Berikut adalah beberapa analisis yang dapat diambil:

Distribusi Kasus Stroke Berdasarkan Jenis Kelamin: Terlihat bahwa jumlah wanita yang tidak mengalami stroke lebih banyak dibandingkan pria, namun jumlah pria dan wanita yang mengalami stroke relatif sama. Ini menunjukkan bahwa stroke mungkin mempengaruhi pria dan wanita dengan cara yang hampir sama.

Jumlah Kasus Stroke Rendah: Secara umum, jumlah kasus stroke sangat rendah dibandingkan dengan mereka yang tidak mengalami stroke di semua jenis kelamin. Ini menunjukkan bahwa stroke mungkin bukan penyakit yang umum di populasi ini.
                              
### Variabel-variabel pada Stroke dataset adalah sebagai berikut:
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
- Pengecekan statistika deskriptif dataframe 
- Pengecekan outlier di kolom numerik
- Perbandingan kolom fitur string/object dengan variabel target(stroke)
- Pengecekan unique per kolom
- Pengecekan nilai kosong(null)
- Mengganti nilai kosong dengan nilai rata rata (mean)
### Keuntungan:

* Simpel dan Cepat:
Metode ini sangat mudah diimplementasikan dan tidak memerlukan banyak perhitungan rumit. Hanya perlu menghitung rata-rata dari data yang ada.

* Memelihara Total:
Jika jumlah total data dan jumlah nilai yang diketahui cukup besar, penggantian dengan rata-rata memungkinkan untuk memelihara total keseluruhan. Hal ini terutama berguna ketika perbedaan antara nilai yang hilang dan rata-rata tidak signifikan.

* Tidak Memperkenalkan Bias Besar:
Metode ini cenderung tidak memperkenalkan bias besar ke dalam data karena hanya menggunakan nilai yang sudah ada.

* Cocok untuk Data Numerik:
Cocok digunakan pada data numerik, seperti data berbentuk angka, karena rata-rata dapat dengan mudah dihitung.

### Keterbatasan:
* Rentan terhadap Outliers:
Jika data memiliki pencilan (outliers), penggunaan nilai rata-rata dapat menjadi kurang akurat karena rata-rata dipengaruhi oleh nilai yang ekstrem.

* Potensi Mengurangi Variabilitas:
Menggantikan nilai yang hilang dengan rata-rata dapat mengurangi variabilitas data, membuat distribusi tampak lebih homogen daripada seharusnya.

* Tidak Cocok untuk Data Kategorikal:
Metode ini tidak cocok untuk data kategorikal atau kualitatif karena tidak masuk akal untuk menggantikan nilai kategorikal dengan nilai rata-rata.

* Tidak Mengambil Konteks:
Penggunaan nilai rata-rata tidak mempertimbangkan konteks atau pola yang mungkin ada dalam data. Ini dapat menyebabkan penyimpangan dari pola sebenarnya jika ada tren atau hubungan yang lebih kompleks dalam data.

- Menghapus nilai outlier
  Metode yang digunakan untuk menghapus adalah IQR
  IQR (Interquartile Range) adalah sebuah ukuran statistik yang mengukur sebaran data dalam suatu himpunan. IQR menggambarkan rentang antara kuartil pertama 
  (Q1) dan kuartil ketiga (Q3) dari suatu distribusi data. Kuartil adalah nilai-nilai yang membagi data menjadi empat bagian sama besar.
- Mengubah kolom non numeric (string) menjadi kategorical 
- Pengecekan korelasi kolom fitur dengan kolom target (stroke)


## Modeling
- Membagi data fitur(x) dan target (y)
- Membagi dataset menjadi 80:20 (80% train & 20% test)
- Normalisasi data dengan MinMaxScaler
- Mengimport library algoritma (_LogisticRegression_, _DecisionTree_, _RandomForest_, _XGBoost_) dan metrics (_accuracy_, _precision_, _recall_, _f1 score_)
  
### DecisionTree
DecisionTree adalah algoritma pembelajaran mesin supervised yang digunakan untuk klasifikasi dan regresi. Algoritma ini bekerja dengan membangun pohon keputusan, yang merupakan struktur pohon dengan cabang dan daun. Setiap cabang mewakili suatu keputusan, dan setiap daun mewakili suatu kelas atau nilai.
Untuk membangun pohon keputusan, algoritma DecisionTree akan membagi data menjadi beberapa kelompok berdasarkan atribut yang paling berpengaruh. Pembagian ini akan dilakukan berulang kali hingga tidak ada lagi atribut yang dapat membagi data menjadi kelompok-kelompok yang lebih kecil.
Pada akhirnya, setiap daun di pohon keputusan akan mewakili suatu kelas atau nilai. Kelas atau nilai ini adalah yang paling sering muncul di kelompok data yang terkait dengan daun tersebut.
Contoh:
Misalkan kita memiliki data tentang tinggi badan dan berat badan seseorang. Kita ingin membangun model yang dapat memprediksi apakah seseorang itu kurus, normal, atau gemuk.
Algoritma DecisionTree akan membagi data menjadi beberapa kelompok berdasarkan atribut tinggi badan. Misalnya, data akan dibagi menjadi dua kelompok, yaitu kelompok tinggi badan < 160 cm dan kelompok tinggi badan >= 160 cm.
Kemudian, algoritma akan membagi kelompok pertama berdasarkan atribut berat badan. Misalnya, kelompok pertama akan dibagi menjadi dua kelompok, yaitu kelompok berat badan < 50 kg dan kelompok berat badan >= 50 kg.
Proses ini akan terus berlanjut hingga tidak ada lagi atribut yang dapat membagi data menjadi kelompok-kelompok yang lebih kecil.
Pada akhirnya, kita akan mendapatkan pohon keputusan seperti berikut:

tinggi badan < 160 cm
    |
    berat badan < 50 kg: kurus
    |
    berat badan >= 50 kg: normal
tinggi badan >= 160 cm
    |
    berat badan < 60 kg: normal
    |
    berat badan >= 60 kg: gemuk
Parameter : 
Criterion:
Menentukan fungsi pengukuran kualitas split, seperti "gini" untuk Gini impurity atau "entropy" untuk Entropy.
Max Depth:
Batasan kedalaman pohon untuk menghindari overfitting.
Min Samples Split:
Jumlah minimum sampel yang diperlukan untuk memecah node internal.
Min Samples Leaf:
Jumlah minimum sampel yang diperlukan untuk menjadi daun (leaf) dari pohon.
    
### RandomForest
RandomForest adalah algoritma pembelajaran mesin supervised yang digunakan untuk klasifikasi dan regresi. Algoritma ini bekerja dengan membangun beberapa pohon keputusan secara independen.
Untuk memprediksi kelas atau nilai suatu data, algoritma RandomForest akan mengambil suara dari pohon-pohon keputusan yang telah dibangun. Kelas atau nilai yang paling banyak dipilih oleh pohon-pohon keputusan tersebut akan menjadi prediksi algoritma.
RandomForest dapat meningkatkan akurasi prediksi dibandingkan dengan DecisionTree dengan cara mengurangi overfitting. Overfitting adalah suatu kondisi di mana model terlalu cocok dengan data pelatihan, sehingga model tidak dapat memprediksi data baru dengan baik.

Parameter ini mencakup parameter Decision Tree, serta beberapa parameter tambahan:
N_estimators:
Jumlah pohon dalam ensemble (jumlah Decision Trees).
Max Features:
Jumlah maksimum fitur yang dipertimbangkan untuk split pada setiap pohon.
Bootstrap:
Menentukan apakah sampel dibangun dengan penggantian (bootstrap sampling).

### LogisticRegression
LogisticRegression adalah algoritma pembelajaran mesin supervised yang digunakan untuk klasifikasi biner. Algoritma ini bekerja dengan membangun model regresi logistik.
Regresi logistik adalah suatu model regresi yang digunakan untuk memprediksi probabilitas terjadinya suatu peristiwa. Dalam kasus klasifikasi biner, peristiwa yang dimaksud adalah peristiwa positif atau negatif.
Contoh:
Misalkan kita ingin membangun model yang dapat memprediksi apakah seseorang itu lulus ujian atau tidak.
Algoritma LogisticRegression akan membangun model regresi logistik yang dapat memprediksi probabilitas lulus ujian seseorang. Model ini akan menggunakan atribut-atribut data, seperti nilai ujian, nilai kehadiran, dan nilai portofolio, untuk memprediksi probabilitas lulus ujian seseorang.
Parameter : 
C:
Parameter regularisasi yang mengontrol penalti untuk kompleksitas model.
Solver:
Algoritma untuk mendapatkan solusi, seperti "lbfgs", "liblinear", atau "sag".
Max Iter:
Jumlah iterasi maksimum untuk konvergensi.

### XGBoost
XGBoost adalah algoritma pembelajaran mesin supervised yang digunakan untuk klasifikasi dan regresi. Algoritma ini bekerja dengan membangun pohon keputusan secara bertahap.
Pada setiap tahap, algoritma XGBoost akan membangun pohon keputusan yang dapat meningkatkan akurasi prediksi model. Algoritma ini akan melakukan hal ini dengan cara memaksimalkan gain Gini dari pohon keputusan yang dibangun.
Gain Gini adalah suatu ukuran kinerja pohon keputusan. Gain Gini yang lebih tinggi menunjukkan bahwa pohon keputusan tersebut dapat meningkatkan akurasi prediksi model.
XGBoost dapat meningkatkan akurasi prediksi dibandingkan dengan algoritma lain, seperti DecisionTree dan RandomForest, dengan cara mengurangi overfitting dan meningkatkan kecepatan pelatihan model.

Parameter :
Learning Rate (Eta):
Menentukan seberapa besar langkah pembelajaran yang diambil pada setiap iterasi saat menyesuaikan bobot.
Max Depth:
Maksimum kedalaman pohon.
Min Child Weight:
Jumlah minimum sampel yang diperlukan pada node anak.
Subsample:
Fraksi dari total sampel yang digunakan dalam setiap iterasi.
Colsample Bytree:
Fraksi dari fitur yang digunakan dalam setiap iterasi.
N_estimators:
Jumlah iterasi (pohon) dalam boosting.
Objective:
Tujuan fungsi yang akan dioptimalkan, misalnya, "binary:logistic" untuk klasifikasi biner.

- Mengfit model dengan dataset



## Evaluasi

Metrik yang digunakan untuk mengevaluasi kinerja model adalah :

* Accuracy (Akurasi):

    - Definisi: Akurasi mengukur sejauh mana model klasifikasi berhasil mengidentifikasi dan mengklasifikasikan data dengan benar dibandingkan dengan total           data yang dievaluasi.
    - Formula:
    (Jumlah Prediksi Benar) / (Jumlah Prediksi Benar + Jumlah Prediksi Salah)

 
* Precision (Presisi):

    - Definisi: Presisi mengukur sejauh mana prediksi positif dari model adalah benar. Ini memberikan indikasi tentang berapa banyak dari instans positif yang        diprediksi oleh model sebenarnya positif.
    - Formula:
      (True Positives) / (True Positives + False Positives)

 
* Recall (Recall atau Sensitivitas):

    - Definisi: Recall mengukur sejauh mana model mampu mengidentifikasi semua instance positif yang sebenarnya. Ini memberikan indikasi tentang sejauh mana    model "ingat" untuk mendeteksi kasus positif.
    - Formula:
(True Positives) / (True Positives + False Negatives)

​
 
* F1 Score:

    - Definisi: F1 Score adalah harmonic mean dari precision dan recall. Ini memberikan keseimbangan antara presisi dan recall, dan sangat berguna ketika terdapat ketidakseimbangan dalam distribusi kelas.
    - Formula:
 2 * (Presisi * Recall) / (Presisi + Recall)

 
* Cross-Validation Mean (Rata-rata Cross-Validation):

    - Definisi: Cross-validation adalah teknik evaluasi model yang melibatkan pembagian dataset menjadi beberapa subset (lipatan/fold), melatih model pada beberapa subset dan menguji pada subset yang tidak terlatih. Cross-Validation Mean mengacu pada rata-rata performa model di semua lipatan tersebut.
    - Formula: Rata-rata performa model pada setiap lipatan.

#### Perbandingan beberapa model

| Model         | Train Accuracy | Test Accuracy |  Accuracy | Precision | Recall | F1 Score | CV Mean |
|---------------|-----------------|----------|---------------|--------|-----------|----------|---------|
| Logistic Regression | 0.96 | 0.95 | 0.95 | 0.47 | 0.5 | 0.48 | 0.96 |
| Random Forest | 0.99 | 0.95 | 0.95 | 0.47 | 0.49 | 0.48 | 0.96|
| Decision Tree | 1.0 | 0.93 | 0.93 | 0.57 | 0.56 | 0.57 | 0.92 |
| XGBoost | 1.0 | 0.95 | 0.95 | 0.71 | 0.57 | 0.61 | 0.95 |


![conf](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/55021763-07c9-4dbf-9737-2cdcee1c69d6)

Dalam matriks ini:

841 instans benar-benar diprediksi sebagai kelas 0 (True Negative).
36 instans salah diprediksi sebagai kelas 0, padahal sebenarnya adalah kelas 1 (False Negative).
Tidak ada instans yang diprediksi sebagai kelas 1 (False Positive dan True Positive keduanya 0).
Dengan kata lain, model ini memiliki tingkat akurasi yang baik dalam memprediksi kelas 0, dengan 841 prediksi benar dan tidak ada kesalahan positif. Namun, model tersebut tidak dapat mengidentifikasi kelas 1 sama sekali, dengan 36 kesalahan negatif. Ini menunjukkan bahwa model ini mungkin perlu ditingkatkan lagi untuk dapat memprediksi kelas 1 dengan lebih baik.

![comf2](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/45a519f3-dfdd-4393-b84a-6e5b54e59eb7)

Dalam matriks ini:

841 instans benar-benar diprediksi sebagai kelas 0 (True Negative).
36 instans salah diprediksi sebagai kelas 0, padahal sebenarnya adalah kelas 1 (False Negative).
Tidak ada instans yang diprediksi sebagai kelas 1 (False Positive dan True Positive keduanya 0).
Dengan kata lain, model ini memiliki tingkat akurasi yang baik dalam memprediksi kelas 0, dengan 841 prediksi benar dan tidak ada kesalahan positif. Namun, model tersebut tidak dapat mengidentifikasi kelas 1 sama sekali, dengan 36 kesalahan negatif. Ini menunjukkan bahwa model ini mungkin perlu ditingkatkan lagi untuk dapat memprediksi kelas 1 dengan lebih baik.

![conf3](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/bb017c0a-eaff-4f9b-bed7-5e451da76343)

Dalam matriks ini:

814 instans benar-benar diprediksi sebagai kelas 0 (True Negative).
27 instans salah diprediksi sebagai kelas 1, padahal sebenarnya adalah kelas 0 (False Positive).
30 instans salah diprediksi sebagai kelas 0, padahal sebenarnya adalah kelas 1 (False Negative).
6 instans benar-benar diprediksi sebagai kelas 1 (True Positive).
Dengan kata lain, model ini memiliki tingkat akurasi yang baik dalam memprediksi kelas 0, dengan 814 prediksi benar dan 27 kesalahan positif. Namun, model tersebut tampaknya kurang baik dalam memprediksi kelas 1, dengan 30 kesalahan negatif dan hanya 6 prediksi benar. Ini menunjukkan bahwa model ini mungkin perlu ditingkatkan lagi untuk dapat memprediksi kelas 1 dengan lebih baik.

![conf4](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/82c12ce1-078d-4c1b-8eea-df1baa02904e)

Dalam matriks ini:

834 instans benar-benar diprediksi sebagai kelas 0 (True Negative).
7 instans salah diprediksi sebagai kelas 1, padahal sebenarnya adalah kelas 0 (False Positive).
30 instans salah diprediksi sebagai kelas 0, padahal sebenarnya adalah kelas 1 (False Negative).
6 instans benar-benar diprediksi sebagai kelas 1 (True Positive).
Dengan kata lain, model ini memiliki tingkat akurasi yang baik dalam memprediksi kelas 0, dengan 834 prediksi benar dan 7 kesalahan positif. Namun, model tersebut tampaknya kurang baik dalam memprediksi kelas 1, dengan 30 kesalahan negatif dan hanya 6 prediksi benar. Ini menunjukkan bahwa model ini mungkin perlu ditingkatkan lagi untuk dapat memprediksi kelas 1 dengan lebih baik.

#### Berdasarkan evaluasi hasil modelling diatas

Model XGBoost tampaknya menjadi model terbaik di antara yang lain. Berikut adalah beberapa alasan mengapa:

Akurasi Pelatihan dan Pengujian: XGBoost memiliki akurasi pelatihan sempurna (1.0), dan akurasi pengujian yang tinggi (0.95). Ini menunjukkan bahwa model ini mampu belajar dengan baik dari data pelatihan dan juga generalisasi dengan baik ke data yang tidak dilihat sebelumnya.

Presisi dan Skor F1: XGBoost memiliki presisi tertinggi (0.71) dan skor F1 tertinggi (0.61) dibandingkan dengan model lain. Presisi tinggi berarti model ini lebih dapat diandalkan dalam mengidentifikasi kelas positif, dan skor F1 yang tinggi menunjukkan kinerja klasifikasi yang seimbang antara presisi dan recall.

CV Mean: Meski CV Mean XGBoost (0.95) sedikit lebih rendah dibandingkan Logistic Regression dan Random Forest (0.96), namun perbedaannya tidak signifikan dan masih dalam rentang yang sangat baik.

Oleh karena itu, berdasarkan metrik ini, XGBoost tampaknya menjadi model terbaik.
















