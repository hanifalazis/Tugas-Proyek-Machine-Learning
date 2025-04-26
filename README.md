# Tugas Proyek Machine Learning

Repositori ini berisi proyek tugas akhir machine learning yang dilakukan oleh **Muhammad Hanif Al Azis**. Proyek ini terdiri dari dua tahap utama, yaitu *clustering* dan *klasifikasi*. Proyek ini dilakukan dengan menggunakan dataset yang memenuhi kriteria tertentu untuk analisis dan eksperimen.

## Daftar Isi
- [Tentang Proyek](#tentang-proyek)
- [Tahapan Proyek](#tahapan-proyek)
  - [Clustering](#clustering)
  - [Klasifikasi](#klasifikasi)
- [Struktur Direktori](#struktur-direktori)
- [Cara Menjalankan](#cara-menjalankan)
- [Sumber Dataset](#sumber-dataset)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)

## Tentang Proyek

Proyek ini bertujuan untuk:
1. Mengelompokkan data menggunakan metode *clustering* tanpa label (unsupervised learning).
2. Menggunakan hasil *clustering* untuk membangun model klasifikasi (supervised learning).

Dataset yang digunakan berasal dari data marketing sebuah institusi perbankan Portugis. Dataset terdiri dari kombinasi data numerik dan kategorikal yang telah diproses sebelumnya agar siap untuk analisis.

## Tahapan Proyek

### Clustering
Pada tahap *clustering*, dilakukan analisis data tanpa label untuk menemukan pola atau pengelompokan alami dalam dataset. Beberapa langkah utama:
- Mengimpor pustaka yang dibutuhkan seperti `pandas`, `matplotlib`, dan `sklearn`.
- Memuat dataset awal yang digunakan.
- Melakukan eksplorasi data (EDA) untuk memahami data.
- Menggunakan algoritma seperti **K-Means** dan **DBSCAN** untuk melakukan *clustering*.
- Evaluasi hasil *clustering* menggunakan metrik seperti *silhouette score*.

### Klasifikasi
Setelah tahap *clustering*, hasilnya digunakan untuk membangun model klasifikasi. Tahapan klasifikasi meliputi:
- Memuat dataset hasil *clustering*.
- Membagi dataset menjadi data latih dan data uji.
- Melatih model klasifikasi menggunakan algoritma seperti **Logistic Regression** dan **Decision Tree Classifier**.
- Mengevaluasi performa model menggunakan metrik seperti *accuracy score*, *precision*, *recall*, dan *F1 score*.

## Struktur Direktori

Berikut adalah struktur direktori proyek:
```
Tugas-Proyek-Machine-Learning/
│
├── Cluster/
│   ├── Submission_Akhir_BMLP_Muhammad_Hanif_Al_Azis.ipynb
│   └── ...
│
├── Klasifikasi/
│   ├── [Klasifikasi]_Submission_Akhir_BMLP_Muhammad_Hanif_Al_Azis.ipynb
│   └── ...
│
└── README.md
```

## Cara Menjalankan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/hanifalazis/Tugas-Proyek-Machine-Learning.git
   cd Tugas-Proyek-Machine-Learning
   ```

2. Pastikan Anda memiliki **Python 3** dan pustaka berikut terpasang:
   - `pandas`
   - `matplotlib`
   - `seaborn`
   - `scikit-learn`
   - `yellowbrick`

3. Jalankan setiap notebook sesuai tahapannya:
   - Jalankan notebook di folder `Cluster/` untuk tahap *clustering*.
   - Jalankan notebook di folder `Klasifikasi/` untuk tahap *klasifikasi*.

## Sumber Dataset

Dataset yang digunakan dapat ditemukan di Kaggle melalui tautan berikut:
[Bank Full CSV Dataset](https://www.kaggle.com/datasets/krantiswalke/bankfullcsv).

## Teknologi yang Digunakan

- **Bahasa Pemrograman**: Python
- **Framework/Library**:
  - *Data Manipulation*: `pandas`
  - *Visualization*: `matplotlib`, `seaborn`
  - *Machine Learning*: `scikit-learn`, `yellowbrick`
