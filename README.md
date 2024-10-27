# Segmentasi Pelanggan 📊 - ![KMeans Clustering](https://img.shields.io/badge/KMeans%20Clustering-FF9C00?style=for-the-badge&logo=google&logoColor=white)

Repositori ini berisi proyek segmentasi pelanggan menggunakan algoritma K-Means Clustering. Proyek ini bertujuan untuk mengelompokkan pelanggan berdasarkan perilaku dan karakteristik mereka, sehingga memungkinkan perusahaan untuk merumuskan strategi pemasaran yang lebih efektif. Repositori ini mencakup file Jupyter Notebook yang menjelaskan proses secara menyeluruh, mulai dari eksplorasi data hingga penerapan model clustering.

## Daftar Isi 🗒️
1. [Project Overview](#project-overview-)
2. [Metode yang Digunakan](#metode-yang-digunakan-)
3. [File yang Tersedia](#file-yang-tersedia-)
4. [Cara Menggunakan Project Ini](#cara-menggunakan-project-ini-)
5. [Dependencies](#dependencies-)
6. [Libraries](#libraries-)
7. [Author](#author-)

## Project Overview 📝

Dalam proyek ini, saya menggunakan algoritma K-Means Clustering untuk mengelompokkan pelanggan berdasarkan data historis mereka. Beberapa langkah utama yang dicakup dalam proyek ini adalah:

1. **Import Libraries dan Eksplorasi Data**:
    - Memuat dataset dan melakukan eksplorasi awal untuk memahami struktur dan karakteristik data.

2. **Preprocessing Data**:
    - Melakukan pembersihan dan persiapan data, termasuk penanganan missing values dan normalisasi data.

3. **Pengembangan Model**:
    - Membangun dan melatih model K-Means Clustering untuk mengelompokkan pelanggan.

4. **Evaluasi Model**:
    - Menggunakan metrik evaluasi untuk menilai kinerja model.

5. **Visualisasi Hasil**:
    - Menggambarkan hasil segmentasi dengan visualisasi yang mudah dipahami.

6. **Analisa Karakteristik per Cluster**:
    - Melakukan analisa karakteristik setiap cluster.

7. **Rekomendasi Bisnis per Cluster**:
    - Memberikan rekomendasi bisnis sesuai dengan karakteristik masing-masing cluster

## Latar Belakang Masalah

Perusahaan Bank ABC ingin meningkatkan efektivitas strategi marketing dengan menyegmentasi nasabah berdasarkan pola penggunaan kartu kredit selama 6 bulan terakhir. Dengan Customer Segmentation, tim marketing dapat lebih tepat menargetkan nasabah sesuai preferensi mereka, meningkatkan loyalitas, dan profitabilitas. Untuk itu, customer segmentation perlu dilakukan untuk membentuk kelompok nasabah yang karakteristik penggunaan kartu kreditnya mirip dan memberikan rekomendasi bisnis yang sesuai untuk setiap segmen.

## Problem Statement √

**Specific**: Mengelompokkan nasabah berdasarkan pola penggunaan kartu kredit.

**Measurable**: Minimal 3 cluster customer terbentuk.

**Achievable**: Menggunakan model clustering KMeans untuk segmentasi.

**Relevant**: Menggunakan model KMeans sangat relevan untuk mendapatkan minimal 3 cluster dan memberikan rekomendasi bisnis ke setiap cluster secara tepat sesuai karakteristik setiap cluster yang terbentuk.

**Time-bound**: Pembentukan segmentasi customer dilaksanakan dalam 1 minggu.

**Problem Statement:** Mengelompokkan nasabah kartu kredit Bank ABC menggunakan model clustering KMeans berdasarkan pola penggunaan kartu kredit selama 6 bulan terakhir, dengan tujuan untuk mengidentifikasi minimal 3 cluster customer dan untuk memberikan rekomendasi bisnis ke setiap segment secara tepat sesuai karakteristik setiap segment berdasarkan cluster yang terbentuk dalam kurun waktu 1 minggu.

## Metode yang Digunakan 🛠️

- Statistik Deskriptif
- Machine Learning
- K-Means Clustering
- Visualisasi Data

## Analisa Karakter per Cluster 🧠

**Cluster 0:**
- Credit limit tergolong high, karena tidak ada fitur data pekerjaan dan penghasilan maka asumsinya pemilik kartu kredit ini adalah pengusaha atau pekerja yang memiliki pendapatan besar
- Balance kartu kredit besar, karena memiliki pendapatan yang besar, para pemilik kartu ini jarang menggunakan kartu kredit dan lebih memilih melakukan pembelian menggunakan tunai atau debit
- Jarang melakukan transaksi
- Nominal transaksi kecil
- Lebih sering melakukan full payment
- Jarang menggunakan installment meskipun ada yang memilih layanan tenure hingga 12
- Jumlah nasabah yang ada di cluster ini paling sedikit, sebanyak 797 nasabah dengan porsi 17.8% dari keseluruhan nasabah

**Cluster 1:**
- Credit limit tergolong medium to low, karena tidak ada fitur data pekerjaan dan penghasilan maka asumsinya pemilik kartu kredit ini adalah karyawan swasta yang baru mendapatkan fasilitas kartu kredit karena limitnya tidak besar seperti cluster 0
- Balance kartu kredit cukup kecil, artinya dari limit credit yang diberikan di cluster ini sering bertransaksi menggunakan kartu kredit
- Cukup sering melakukan transaksi
- Nominal transaksi cukup besar
- Ada yang jarang melakukan full payment
- Beberapa ada yang menggunakan installment dan tenur yang dipilih banyak yang 12
- Jumlah nasabah yang ada di cluster ini paling banyak, sebanyak 1944 nasabah dengan porsi 43.4% dari keseluruhan nasabah

**Cluster 2:**
- Credit limit lebih banyak digolongkan medium to low, tetapi ada yang medium to high, karena tidak ada fitur data pekerjaan dan penghasilan maka asumsinya pemilik kartu kredit ini adalah karyawan swasta yang sudah lumayan lama menggunakan kartu kredit
- Balance kartu kredit cukup kecil, artinya dari limit credit yang diberikan di cluster ini sering bertransaksi menggunakan kartu kredit
- Sering melakukan transaksi
- Nominal transaksi besar
- Cukup sering melakukan full payment
- Banyak yang menggunakan installment dan pilihan tenurenya adalah 12, artinya di cluster ini memiliki kecenderungan sifat konsumtif
- Jumlah nasabah yang ada di cluster hampir mirip dengan cluster 1, yaitu sebanyak 1734 nasabah dengan porsi 38.7% dari keseluruhan nasabah

## Rekomendasi 📌

Fokus utamanya adalah meningkatkan transaksi dan mempertahankan transaksi dari nasabah yang masuk kedalam cluster 1 dan cluster 2, tetapi tidak juga melupakan cluster 0. Cluster 1 dan cluster 2 menjadi fokus utama karena nasabah yang sering menggunakan kartu kredit ada pada cluster ini.

**Cluster 0:**
- Memberikan penawaran untuk pembelian barang elektronik rumah dengan promo cicilan bunga 0% di tenor 12 bulan untuk mempertahankan nasabah di cluster ini tetap menggunakan kartu kredit
- Memberikan edukasi penggunaan kartu kredit dan memberikan penawaran dengan menggunakan sistem cold-calling dan email marketing
- Memberikan poin loyalti disetiap transaksi dan pembayaran tagihan kartu kredit, lalu poin tersebut bisa ditukarkan dengan voucher diskon ditransaksi selanjutnya atau menjadi poin yang bisa dikonversi sebagai potongan harga secara langsung saat bertransaksi menggunakan kartu kredit

**Cluster 1:**
- Meningkatkan credit limit nasabah yang kolektabilitasnya bagus
- Memberikan promo diskon potongan tenure 1 bulan jika pembelian menggunakan installment tenure 12 untuk pembelanjaan kategori elektronik menggunakan kartu kredit
- Memberikan promo payday buy 1 get 1 disetiap akhir bulan setiap bertransaksi menggunakan kartu kredit
- Menurunkan minimal nominal transaksi untuk menggunakan layanan installment kartu kredit
- Menambah jangka waktu tenure misalnya menjadi 15 dan 18 bulan untuk minimal nominal transaksi diatas 5.000.000
- Memberikan poin loyalti disetiap transaksi dan pembayaran tagihan kartu kredit, lalu poin tersebut bisa ditukarkan dengan voucher diskon ditransaksi selanjutnya atau menjadi poin yang bisa dikonversi sebagai potongan harga secara langsung saat bertransaksi menggunakan kartu kredit

**Cluster 2:**
- Meningkatkan credit limit nasabah yang kolektabilitasnya bagus
- Memberikan promo promo cicilan bunga 0% di tenor 12 bulan untuk kategori apa saja
- Memberikan promo payday buy 1 get 1 disetiap akhir bulan setiap bertransaksi menggunakan kartu kredit
- Menurunkan minimal nominal transaksi untuk menggunakan layanan installment kartu kredit
- Menambah jangka waktu tenure misalnya menjadi 18 bulan untuk minimal nominal transaksi diatas 5.000.000
- Memberikan poin loyalti disetiap transaksi dan pembayaran tagihan kartu kredit, lalu poin tersebut bisa ditukarkan dengan voucher diskon ditransaksi selanjutnya atau menjadi poin yang bisa dikonversi sebagai potongan harga secara langsung saat bertransaksi menggunakan kartu kredit

## File yang Tersedia 📂

- `customer_segmentation_clustering.ipynb`: Jupyter Notebook yang berisi langkah-langkah analisis data, pengembangan model K-Means, evaluasi model, dan wawasan yang diperoleh dari analisis.
- `trx_data.csv`: Dataset yang digunakan dalam analisis. Diambil dari google bigquery menggunakan syntax SQL melalui google collab.
- `data_inference.ipynb`: Jupyter Notebook yang berisi prediksi unseen data menggunakan model yang sudah dibuat sebelumnya
- `kmeans.pkl, list_num_col.txt, pca.pkl, scaler.pkl`: Hasil penyimpanan model dan preprocessing
  
## Cara Menggunakan Project Ini 💻

1. Clone repositori ini ke dalam lokal Anda:
    ```bash
    git clone https://github.com/ciputrawangsa/Customer_Segmentation-KMeansClustering.git
    ```

2. Jalankan Jupyter Notebook untuk mengikuti alur analisis data:
    ```bash
    jupyter notebook customer_segmentation_clustering.ipynb
    ```

## Dependencies ⚙️

- ![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 3.10.14

## Libraries 📚
- Pandas
- NumPy
- Scikit-learn
- Plotly
- Matplotlib
- Seaborn
- JSON
- Pickle

## Author ✍️
**Ciputra Wangsa**

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ciputra-wangsa/)