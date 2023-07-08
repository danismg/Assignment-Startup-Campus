# Heart Disease FE
![image](https://github.com/danismg/Assignment-Startup-Campus/blob/main/Img.jpg)
**Description Database :**<br>
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

**Download Dataset:**<br>
[Klik Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset )

## 1. Define Business Problems, Petrics, Goals

**Business Problems  :**<br>
    Masalah bisnis yang mungkin terjadi adalah mengembangkan model untuk memprediksi apakah seorang pasien memiliki penyakit jantung dari berbagai macam faktor yang ada.<br>
    <br>
**Metrics            :** <br>
    Akurasi, presisi, daya ingat, skor F1, dan skor AUC-ROC.<br>
    **Akurasi** : Jumlah data yang diprediksi secara benar terhadap jumlah keseluruhan data. Misal : berapa persen data age = 30 dari jumlah data age atau seperti persen missing<br>
    **ROC AUC** : Dapat mengevaluasi kemampuan model klasifikasi dalam membedakan antara kelas positif dan negatif. Semakin besar nilai AUC, semakin baik kemampuan model dalam membedakan kelas positif dan negatif. Sebaliknya, semakin kecil nilai AUC, semakin buruk kemampuan model tersebut.<br>
    <br>
    **Business Problems  :**<br>
    Memabangun sebuah model yang akurat yang dapat memprediksi seorang pasien menderita penyakit jantung atau tidak guna untuk membantu para profesional medis mendiagnosis dan merawat pasien lebih awal dan lebih efektif.


## 2. Define the Workflow

1. Muat dataset ke lingkungan seperti python.
2. Pahami atribut dan signifikansinya dalam memprediksi penyakit jantung. seperti umur, tekanan darah(trstbps) dan lainnya
3. Periksa kualitas kumpulan data untuk nilai yang hilang, duplikat, outlier, dan ketidakseimbangan data.
4. Periksa statistik deskriptif dari kumpulan data, termasuk rata-rata, distribusi, dll.
5. Periksa korelasi antara fitur untuk mengidentifikasi hubungan yang kuat atau lemah.
6. Visualisasikan statistik deskriptif dan hasil korelasi untuk mendapatkan lebih banyak wawasan.
7. Tentukan kemungkinan feature engineering untuk meningkatkan kinerja model prediktif.
8. Mengotomatiskan EDA melalui alat seperti Dataprep, Autovis, dan Dtale untuk menghemat waktu dan tenaga dalam proses analisis data eksplorasi.

# Files in Heart Disease FE
There are several files that explain each stage of CRISP - DM, as follows:<br>
| Exercise | Deskripsi |
| --- | --- |
|[Exercise 2](https://github.com/danismg/Assignment-Startup-Campus/blob/main/Assignment_2_026_Daniel_Andres_Simangunsong.ipynb) | Data Preprocessing|
|[Exercise 3](https://github.com/danismg/Assignment-Startup-Campus/blob/main/DS04026_Daniel_Andres_Simangunsong_Assignment_3_Heart_disease_FE.ipynb) | Machine Learning|
|[Exercise 4](https://github.com/danismg/Assignment-Startup-Campus/blob/main/026_Daniel_Andres_Simangunsong_Assignment_4_Heart_Disease_.ipynb) | Model Performance Analytics|
|[Exercise 5](https://lookerstudio.google.com/reporting/78d298c0-ea09-400d-9cff-235912e56fbb/page/p0rOD) | Dashboard|
