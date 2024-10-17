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

## Metode yang Digunakan 🛠️

- Statistik Deskriptif
- Machine Learning
- K-Means Clustering
- Visualisasi Data

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