Dokumentasi Project Data Mining - Klasifikasi Kanker Payudara

Judul/Topik Project dan Identitas Lengkap

Judul: Klasifikasi Kanker Payudara Menggunakan Oversampling dan Normalisasi


Identitas:

Nama : R Bagus Ario Arlianda Dwiputa

NIM : A11.2020.12796

Program Studi Teknik Informatika



Ringkasan

Proyek ini bertujuan untuk membangun model klasifikasi kanker payudara menggunakan dataset dari UCI Machine Learning Repository. Algoritma K-Nearest Neighbors (KNN) digunakan untuk memprediksi apakah menderita kanker bersifat ganas (M) atau jinak (B).
Permasalahan Project

Kanker payudara merupakan salah satu jenis kanker paling umum pada wanita di seluruh dunia. Diagnosis dini sangat penting untuk meningkatkan tingkat kesembuhan. Tantangan utama dalam klasifikasi kanker payudara adalah memisahkan sel-sel ganas dari sel-sel jinak dengan akurasi tinggi untuk menghasilkan diagnosis yang tepat.
Tujuan yang Akan Dicapai

    Membangun model klasifikasi berbasis algoritma KNN untuk memprediksi jenis kanker payudara (ganas atau jinak).
    Mengoptimalkan parameter KNN untuk mendapatkan model dengan performa terbaik.
    Mengevaluasi performa model menggunakan metrik akurasi, presisi, recall, dan F1-score.
    Memberikan kontribusi dalam meningkatkan akurasi diagnosis dini kanker payudara menggunakan data klinis dan teknik machine learning.


Model Penyelesaian
Mulai -> Load Data -> EDA -> Cleaning Data -> Data Construction -> Data Splitting -> Modelling -> Evaluasi Model -> Selesai


Dataset

Dataset diambil dari UCI Machine Learning Repository dan terdiri dari 569 sampel dengan 32 kolom. Diagnosis terdiri dari dua kelas: 'M' untuk ganas dan 'B' untuk jinak. Berikut adalah deskripsi kolom dataset:

    ID: Nomor identifikasi pasien
    Diagnosis: Jenis kanker ('M' untuk ganas, 'B' untuk jinak)
    Fitur-fitur:
        radius1, texture1, perimeter1, area1, smoothness1, compactness1, concavity1, concave_points1, symmetry1, fractal_dimension1
        radius2, texture2, perimeter2, area2, smoothness2, compactness2, concavity2, concave_points2, symmetry2, fractal_dimension2
        radius3, texture3, perimeter3, area3, smoothness3, compactness3, concavity3, concave_points3, symmetry3, fractal_dimension3

Eksplorasi Data dan Analisis (EDA)

EDA dilakukan untuk memahami distribusi data, mengidentifikasi outlier, dan melihat hubungan antar fitur. Teknik oversampling digunakan untuk menangani ketidakseimbangan kelas pada diagnosis.
Proses Features Dataset

    Oversampling: Teknik oversampling diterapkan untuk menyeimbangkan jumlah sampel pada kelas 'M' dan 'B'.
    Normalisasi: Fitur dinormalisasi untuk memastikan skala yang sama, yang penting untuk algoritma KNN.

Proses Learning/Modeling

    Data dibagi menjadi data latih dan data uji.
    Algoritma KNN diterapkan dengan variasi parameter k untuk menemukan nilai terbaik.
Performa Model

Performa model diukur menggunakan metrik berikut:

    Akurasi
    Presisi
    Recall
    F1-score

Hasil evaluasi menunjukkan bahwa model KNN dengan oversampling dan normalisasi memberikan performa yang optimal.


Diskusi Hasil dan Kesimpulan
Diskusi Hasil

Model klasifikasi berbasis KNN menunjukkan performa yang baik dalam membedakan antara sel kanker ganas dan jinak. Teknik oversampling dan normalisasi berperan penting dalam meningkatkan akurasi dan stabilitas model.

Kesimpulan

    Model KNN berhasil mengklasifikasikan kanker payudara dengan akurasi yang baik.
    Teknik machine learning dapat digunakan sebagai alat bantu dalam diagnosis dini kanker payudara.
    Oversampling dan normalisasi meningkatkan performa model secara signifikan.

Referensi

    UCI Machine Learning Repository: Breast Cancer Dataset
    Scikit-learn Documentation for K-Nearest Neighbors (KNN)




