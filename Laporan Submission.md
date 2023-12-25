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

Kelumpuhan
Gangguan bicara
Gangguan penglihatan
Gangguan ingatan
Gangguan emosi
Kecacatan akibat stroke dapat berdampak signifikan pada kehidupan penderita dan keluarganya. Penderita stroke yang mengalami kecacatan berat seringkali membutuhkan bantuan orang lain untuk melakukan aktivitas sehari-hari. Hal ini dapat menimbulkan beban ekonomi dan psikologis bagi keluarga.

Berdasarkan data dari BPJS Kesehatan, pada tahun 2022, biaya pelayanan kesehatan untuk stroke mencapai Rp2,7 triliun. Biaya ini ditanggung oleh pemerintah melalui program Jaminan Kesehatan Nasional (JKN).

Upaya pencegahan dan pengendalian stroke

Ada beberapa hal yang dapat dilakukan untuk mencegah dan mengendalikan stroke, antara lain:

#### Menjaga tekanan darah, gula darah, dan kolesterol dalam batas normal
Tekanan darah tinggi, diabetes, dan kolesterol tinggi merupakan faktor risiko utama stroke. Oleh karena itu, penting untuk menjaga ketiga faktor risiko ini dalam batas normal.

#### Menghentikan merokok
Merokok merupakan faktor risiko utama stroke. Oleh karena itu, penting untuk berhenti merokok jika Anda ingin mencegah stroke.

#### Mengurangi konsumsi alkohol
Konsumsi alkohol berlebihan merupakan faktor risiko stroke. Oleh karena itu, penting untuk membatasi konsumsi alkohol.

#### Melakukan aktivitas fisik secara teratur
Aktivitas fisik secara teratur dapat membantu menurunkan tekanan darah, gula darah, dan kolesterol. Selain itu, aktivitas fisik juga dapat membantu menjaga berat badan ideal.

#### Menjaga berat badan ideal
Obesitas merupakan faktor risiko stroke. Oleh karena itu, penting untuk menjaga berat badan ideal.

#### Mengonsumsi makanan yang sehat dan bergizi
Konsumsi makanan yang sehat dan bergizi dapat membantu menurunkan tekanan darah, gula darah, dan kolesterol.

Selain itu, penting juga untuk melakukan pemeriksaan kesehatan secara rutin, terutama bagi orang yang memiliki faktor risiko stroke. Pemeriksaan kesehatan dapat membantu mendeteksi stroke secara dini sehingga dapat dilakukan penanganan yang tepat.


## Business Understanding

Berikut adalah beberapa statistik yang mendukung pentingnya memprediksi risiko stroke:

#### Menurut data dari Kementerian Kesehatan Republik Indonesia (Kemenkes RI), prevalensi stroke di Indonesia pada tahun 2022 adalah 1,7%. Hal ini berarti, dari setiap 1.000 orang di Indonesia, terdapat 17 orang yang berisiko terkena stroke.

#### Stroke merupakan salah satu penyebab kematian dan kecacatan terbesar di Indonesia. Menurut data Kemenkes RI, pada tahun 2022, stroke menjadi penyebab kematian ke-4 di Indonesia. Sekitar 7% kematian di Indonesia disebabkan oleh stroke.

#### Berdasarkan data dari Badan Penyelenggara Jaminan Sosial (BPJS) Kesehatan, pada tahun 2022, biaya pelayanan kesehatan untuk stroke mencapai Rp2,7 triliun. Biaya ini ditanggung oleh pemerintah melalui program Jaminan Kesehatan Nasional (JKN).

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

![download (1)](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/09dab5d8-c462-49d9-9780-efa026191b5a)

![download (2)](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/70ea9cc9-a853-467b-be59-f76dab753a8a)
                                            
![download (3)](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/98d805bc-efd2-4380-99e7-dab154f812fd)

### Categorical Variable

![smokingstatus](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/78828a82-deef-4e76-a123-653fe542358b)

![residence](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/b1f02239-9312-4a19-80cf-f40cc3c222ec)

![worktype](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/fb839e19-4c63-4648-9e95-fdc6ab725ce0)

![evermarid](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/1f9204cb-22f2-4441-a9d7-83fc4c8aac8b)

![gender](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/da3f8105-dea3-4a08-b78f-d3fdf461a369)
                              
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
Simpel dan Cepat:

Metode ini sangat mudah diimplementasikan dan tidak memerlukan banyak perhitungan rumit. Hanya perlu menghitung rata-rata dari data yang ada.
Memelihara Total:

Jika jumlah total data dan jumlah nilai yang diketahui cukup besar, penggantian dengan rata-rata memungkinkan untuk memelihara total keseluruhan. Hal ini terutama berguna ketika perbedaan antara nilai yang hilang dan rata-rata tidak signifikan.
Tidak Memperkenalkan Bias Besar:

Metode ini cenderung tidak memperkenalkan bias besar ke dalam data karena hanya menggunakan nilai yang sudah ada.
Cocok untuk Data Numerik:

Cocok digunakan pada data numerik, seperti data berbentuk angka, karena rata-rata dapat dengan mudah dihitung.
### Keterbatasan:
Rentan terhadap Outliers:

Jika data memiliki pencilan (outliers), penggunaan nilai rata-rata dapat menjadi kurang akurat karena rata-rata dipengaruhi oleh nilai yang ekstrem.
Potensi Mengurangi Variabilitas:

Menggantikan nilai yang hilang dengan rata-rata dapat mengurangi variabilitas data, membuat distribusi tampak lebih homogen daripada seharusnya.
Tidak Cocok untuk Data Kategorikal:

Metode ini tidak cocok untuk data kategorikal atau kualitatif karena tidak masuk akal untuk menggantikan nilai kategorikal dengan nilai rata-rata.
Tidak Mengambil Konteks:

Penggunaan nilai rata-rata tidak mempertimbangkan konteks atau pola yang mungkin ada dalam data. Ini dapat menyebabkan penyimpangan dari pola sebenarnya jika ada tren atau hubungan yang lebih kompleks dalam data.
- Menghapus nilai outlier
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
    
### RandomForest
RandomForest adalah algoritma pembelajaran mesin supervised yang digunakan untuk klasifikasi dan regresi. Algoritma ini bekerja dengan membangun beberapa pohon keputusan secara independen.
Untuk memprediksi kelas atau nilai suatu data, algoritma RandomForest akan mengambil suara dari pohon-pohon keputusan yang telah dibangun. Kelas atau nilai yang paling banyak dipilih oleh pohon-pohon keputusan tersebut akan menjadi prediksi algoritma.
RandomForest dapat meningkatkan akurasi prediksi dibandingkan dengan DecisionTree dengan cara mengurangi overfitting. Overfitting adalah suatu kondisi di mana model terlalu cocok dengan data pelatihan, sehingga model tidak dapat memprediksi data baru dengan baik.

### LogisticRegression
LogisticRegression adalah algoritma pembelajaran mesin supervised yang digunakan untuk klasifikasi biner. Algoritma ini bekerja dengan membangun model regresi logistik.
Regresi logistik adalah suatu model regresi yang digunakan untuk memprediksi probabilitas terjadinya suatu peristiwa. Dalam kasus klasifikasi biner, peristiwa yang dimaksud adalah peristiwa positif atau negatif.
Contoh:
Misalkan kita ingin membangun model yang dapat memprediksi apakah seseorang itu lulus ujian atau tidak.
Algoritma LogisticRegression akan membangun model regresi logistik yang dapat memprediksi probabilitas lulus ujian seseorang. Model ini akan menggunakan atribut-atribut data, seperti nilai ujian, nilai kehadiran, dan nilai portofolio, untuk memprediksi probabilitas lulus ujian seseorang.

### XGBoost
XGBoost adalah algoritma pembelajaran mesin supervised yang digunakan untuk klasifikasi dan regresi. Algoritma ini bekerja dengan membangun pohon keputusan secara bertahap.
Pada setiap tahap, algoritma XGBoost akan membangun pohon keputusan yang dapat meningkatkan akurasi prediksi model. Algoritma ini akan melakukan hal ini dengan cara memaksimalkan gain Gini dari pohon keputusan yang dibangun.
Gain Gini adalah suatu ukuran kinerja pohon keputusan. Gain Gini yang lebih tinggi menunjukkan bahwa pohon keputusan tersebut dapat meningkatkan akurasi prediksi model.
XGBoost dapat meningkatkan akurasi prediksi dibandingkan dengan algoritma lain, seperti DecisionTree dan RandomForest, dengan cara mengurangi overfitting dan meningkatkan kecepatan pelatihan model.
- Mengfit model dengan dataset




## Evaluation
Berdasarkan hasil modelling diatas, model LogisticRegression lah yang memiliki  akurasi tertinggi dibandingkan model model yang lainnya

![conf](https://github.com/amaldevice/Data-Analytic-Portofolio/assets/99197713/55021763-07c9-4dbf-9737-2cdcee1c69d6)



### Train Acc : 1.0
Penjelasan: Akurasi pelatihan mengukur sejauh mana model dapat mengklasifikasikan data pelatihan dengan benar. Nilai 1.0 menunjukkan bahwa model berhasil mengklasifikasikan semua sampel pelatihan dengan benar.
Akurasi Testing (Testing Accuracy):

### Testing Acc : 0.9578107183580388
Penjelasan: Akurasi testing mengukur sejauh mana model dapat mengklasifikasikan data uji (testing) dengan benar. Nilai 0.9578107183580388 menunjukkan bahwa model berhasil mengklasifikasikan sekitar 95.78% dari data uji dengan benar.

### Accuracy Score : 0.9578107183580388
Penjelasan: Accuracy score adalah ukuran keseluruhan keberhasilan model dalam mengklasifikasikan data, dihitung sebagai jumlah prediksi benar dibagi dengan jumlah total prediksi.

### Precision Score : 0.7134081196581197
Penjelasan: Precision mengukur sejauh mana prediksi positif model akurat. Nilai 0.7134081196581197 menunjukkan bahwa sekitar 71.34% dari instansi yang diprediksi positif oleh model memang benar-benar positif.

### Recall Score: 0.5791716210860087
Penjelasan: Recall (atau Sensitivity) mengukur sejauh mana model dapat menemukan semua instansi positif yang sebenarnya. Nilai 0.5791716210860087 menunjukkan bahwa model berhasil menemukan sekitar 57.92% dari semua instansi positif.

### F1 Score: 0.6115985397091388
Penjelasan: F1 score adalah harmonic mean dari precision dan recall. Ini memberikan suatu metrik yang seimbang antara precision dan recall. Nilai 0.6115985397091388 menunjukkan keseimbangan antara akurasi prediksi positif dan kemampuan model untuk menemukan semua instansi positif yang sebenarnya.

### Cross-validation scores : [0.93447293, 0.92011412, 0.94008559, 0.92724679, 0.92154066]
Penjelasan: Cross-validation scores adalah hasil akurasi yang diperoleh dari setiap iterasi dalam proses cross-validation. Dalam contoh ini, model diuji menggunakan lima fold cross-validation, dan hasil akurasi dari setiap fold adalah [0.93447293, 0.92011412, 0.94008559, 0.92724679, 0.92154066].

### Mean CV accuracy : 0.9286920191342445
Penjelasan: Mean CV accuracy adalah rata-rata dari hasil cross-validation scores. Dalam contoh ini, rata-rata akurasi dari lima iterasi cross-validation adalah 0.9286920191342445. Metric ini memberikan gambaran umum tentang performa model secara keseluruhan selama proses cross-validation.
Proses cross-validation melibatkan pembagian dataset menjadi beberapa bagian (fold) dan melakukan beberapa iterasi pelatihan dan pengujian menggunakan subset berbeda untuk evaluasi model. Hal ini membantu menghindari overfitting atau hasil yang sangat dipengaruhi oleh pembagian khusus dataset. Dengan menggunakan mean CV accuracy, kita dapat mendapatkan estimasi yang lebih stabil tentang sejauh mana model dapat diharapkan untuk performa pada data yang belum pernah dilihat sebelumnya.











