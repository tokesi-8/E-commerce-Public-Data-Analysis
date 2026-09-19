# E-Commerce Public Dataset Dashboard ✨

## Deskripsi Proyek
Proyek ini merupakan tugas akhir dari kelas "Belajar Analisis Data dengan Python" di Dicoding. Dataset yang digunakan adalah E-Commerce Public Dataset yang berasal dari Olist, sebuah platform e-commerce terkemuka di Brazil.
Proyek ini mencakup seluruh siklus analisis data, mulai dari pengumpulan data (Gathering Data), penilaian (Assessing Data), pembersihan (Cleaning Data), Exploratory Data Analysis (EDA), Visualisasi Data, hingga pembuatan Dashboard interaktif menggunakan Streamlit. Selain itu, proyek ini juga menerapkan teknik analisis lanjutan berupa RFM Analysis (Recency, Frequency, Monetary) untuk melakukan segmentasi pelanggan berdasarkan perilaku belanja mereka.

# Pertanyaan Bisnis (SMART)
Analisis dalam proyek ini difokuskan untuk menjawab dua pertanyaan bisnis utama berikut:
- Bagaimana segmentasi pelanggan berdasarkan Recency, Frequency, dan Monetary (RFM) pada periode 2017–2018, dan berapa persentase kontribusi segmen pelanggan terbaik terhadap total revenue pada periode tersebut? (Fokus pada strategi segmentasi pelanggan bernilai tinggi untuk efisiensi budget marketing).
- Negara bagian (state) mana yang menghasilkan revenue tertinggi, dan bagaimana rata-rata waktu pengiriman (delivery time) pada masing-masing state selama tahun 2018? (Fokus pada distribusi pendapatan geografis dan efisiensi logistik pengiriman).
  
# Struktur Direktori
- /data : Berisi dataset mentah (format CSV) dari E-Commerce Public Dataset yang digunakan dalam analisis.
- /dashboard : Berisi script utama dashboard.py yang dibangun menggunakan Streamlit, beserta dataset bersih main_data.csv yang digunakan untuk visualisasi.
- notebook.ipynb : File Jupyter Notebook yang memuat dokumentasi langkah demi langkah dari keseluruhan proses analisis data.
- requirements.txt : Daftar lengkap pustaka (library) Python yang dibutuhkan untuk menjalankan proyek ini.
- url.txt : Tautan/URL akses untuk dashboard.

## Setup Environment - Anaconda

**Buat environment dengan Python 3.11.0 :**

```
conda create --name main-ds python=3.11.0
```

**Aktifkan environment:**

```
conda activate main-ds
```

**Install library yang dibutuhkan:**

```
pip install -r requirements.txt
```

## Run Streamlit App

```
cd .\dashboard
streamlit run dashboard.py
```
