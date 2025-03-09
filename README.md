<div align="center">

# 📊 Proyek Analisis Data: Dicoding Collection Dashboard

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)

_Dashboard analisis data komprehensif untuk fashion brand DiCo_

<img src="https://i.imgur.com/PLACEHOLDER_IMAGE.png" alt="Dashboard Preview" width="600px">

</div>

---

## 📑 Daftar Isi

- [✨ Pendahuluan](#-pendahuluan)
- [📁 Dataset](#-dataset)
- [🔄 Alur Kerja](#-alur-kerja)
- [❓ Pertanyaan Bisnis](#-pertanyaan-bisnis)
- [📈 Hasil Analisis](#-hasil-analisis)
- [⚙️ Cara Instalasi](#️-cara-instalasi)
- [🚀 Cara Menjalankan Dashboard](#-cara-menjalankan-dashboard)
- [🎮 Fitur Dashboard](#-fitur-dashboard)
- [📸 Tangkapan Layar](#-tangkapan-layar)

---

## ✨ Pendahuluan

Dicoding Collection (DiCo) adalah perusahaan yang bergerak di bidang fashion yang memproduksi berbagai item fashion dan menjualnya melalui platform online. Proyek ini bertujuan untuk menganalisis data penjualan DiCo untuk membantu perusahaan:

- 📊 Mengevaluasi performa penjualan
- 🔍 Memahami item fashion yang paling diminati pelanggan
- 👥 Mendapatkan wawasan tentang demografi pelanggan
- 📱 Mengembangkan strategi pemasaran yang lebih efisien

---

## 📁 Dataset

Dataset yang digunakan adalah **Dicoding Collection** yang merupakan modifikasi dari dataset _Shopping Cart Database_ dari Kaggle. Dataset terdiri dari empat tabel utama:

| Tabel         | Deskripsi           | Kolom Utama                                          |
| ------------- | ------------------- | ---------------------------------------------------- |
| **Customers** | Informasi pelanggan | customer_id, name, gender, age, address, dll         |
| **Orders**    | Informasi pesanan   | order_id, customer_id, order_date, delivery_date     |
| **Products**  | Detail produk       | product_id, type, name, size, color, price, dll      |
| **Sales**     | Detail transaksi    | sales_id, order_id, product_id, price, quantity, dll |

---

## 🔄 Alur Kerja

Proyek ini terdiri dari beberapa tahapan:

### 1️⃣ Data Wrangling

- Mengumpulkan data dari keempat tabel
- Menilai kualitas data (mengidentifikasi missing values, duplikasi, dan nilai yang tidak akurat)
- Membersihkan data (mengatasi missing values, menghapus duplikasi, dan memperbaiki nilai yang tidak akurat)

### 2️⃣ Exploratory Data Analysis (EDA)

- Mengeksplorasi data customers untuk memahami demografi pelanggan
- Mengeksplorasi data orders untuk memahami pola pembelian
- Mengeksplorasi data products dan sales untuk mengidentifikasi produk yang paling laris
- Melakukan analisis RFM (Recency, Frequency, Monetary) untuk mengidentifikasi pelanggan terbaik

### 3️⃣ Visualisasi Data

- Membuat visualisasi performa penjualan dan pendapatan per bulan
- Membuat visualisasi produk dengan performa terbaik dan terburuk
- Membuat visualisasi demografi pelanggan berdasarkan gender, usia, dan negara bagian
- Membuat visualisasi hasil analisis RFM

### 4️⃣ Pembuatan Dashboard

- Mengembangkan dashboard interaktif menggunakan Streamlit
- Menambahkan filter rentang waktu
- Menambahkan visualisasi performa penjualan, produk terlaris, demografi pelanggan, dan analisis RFM

---

## ❓ Pertanyaan Bisnis

Pertanyaan bisnis yang ingin dijawab dalam proyek ini:

1. Bagaimana performa penjualan dan revenue perusahaan dalam beberapa bulan terakhir?
2. Produk apa yang paling banyak dan paling sedikit terjual?
3. Bagaimana demografi pelanggan yang dimiliki perusahaan?
4. Kapan terakhir pelanggan melakukan transaksi?
5. Seberapa sering seorang pelanggan melakukan pembelian dalam beberapa bulan terakhir?
6. Berapa banyak uang yang dihabiskan pelanggan dalam beberapa bulan terakhir?

---

## 📈 Hasil Analisis

Berdasarkan analisis yang dilakukan, berikut adalah beberapa temuan utama:

### 📉 Performa Penjualan

Terdapat fluktuasi penjualan dengan penurunan signifikan pada bulan Februari, April, Mei, dan Oktober.

### 👕 Produk Terlaris

- **Paling Laris**: Denim
- **Paling Sedikit**: Mandarin Collar

### 👥 Demografi Pelanggan

- **Gender**: Kebanyakan pelanggan memilih "Prefer not to say"
- **Usia**: Didominasi oleh kelompok usia dewasa (Adults)
- **Lokasi**: Pelanggan paling banyak berasal dari negara bagian South Australia

### 🏆 Analisis RFM

Berhasil mengidentifikasi pelanggan terbaik berdasarkan parameter recency, frequency, dan monetary.

---

## ⚙️ Cara Instalasi

<details>
<summary>Klik untuk melihat langkah-langkah instalasi</summary>

### Prasyarat

- Python 3.7 atau lebih tinggi
- pip (Python package manager)
- Git (opsional, untuk mengkloning repositori)

### Langkah 1: Menyiapkan Lingkungan Python

**Menggunakan Anaconda (Direkomendasikan)**

1. Unduh dan instal Anaconda dari [situs resmi](https://www.anaconda.com/products/distribution)
2. Buka Anaconda Prompt atau terminal dan buat lingkungan baru:

```bash
conda create -n dico-dashboard python=3.9
conda activate dico-dashboard
```

**Menggunakan venv**

1. Buka terminal atau command prompt
2. Buat lingkungan virtual:

```bash
# Untuk Windows
python -m venv dico-env
dico-env\Scripts\activate

# Untuk macOS/Linux
python -m venv dico-env
source dico-env/bin/activate
```

### Langkah 2: Mendapatkan File Proyek

**Mengkloning dengan Git (jika tersedia)**

```bash
git clone [url-repositori]
cd proyek_analisis_data
```

**Unduh Manual**

1. Unduh file zip proyek
2. Ekstrak kontennya
3. Navigasi ke folder yang diekstrak di terminal Anda

### Langkah 3: Menginstal Paket yang Diperlukan

Navigasikan ke direktori proyek dan instal paket yang diperlukan:

```bash
pip install -r requirements.txt
```

Atau jika Anda lebih suka menginstal paket satu per satu:

```bash
pip install pandas
pip install matplotlib
pip install seaborn
pip install streamlit
pip install babel
```

### Langkah 4: Verifikasi File Data

Pastikan file `all_data.csv` berada di direktori `dashboard`. Jika tidak ada, Anda perlu menjalankan langkah-langkah persiapan data di notebook terlebih dahulu:

1. Buka dan jalankan `notebook.ipynb` menggunakan Jupyter Notebook atau JupyterLab
2. Jalankan semua sel di notebook
3. Sel terakhir akan menghasilkan file `all_data.csv`
4. Pindahkan file ini ke direktori `dashboard`

</details>

---

## 🚀 Cara Menjalankan Dashboard

1. Buka terminal atau command prompt
2. Arahkan ke direktori proyek
3. Aktifkan lingkungan Python Anda jika belum diaktifkan
4. Jalankan perintah berikut:

```bash
cd dashboard
streamlit run dashboard.py
```

5. Browser web Anda akan otomatis terbuka dengan dashboard. Jika tidak, navigasikan ke URL yang ditampilkan di terminal (biasanya http://localhost:8501)

---

## 🎮 Fitur Dashboard

Dashboard yang dikembangkan memiliki beberapa fitur utama:

| Fitur                           | Deskripsi                                                                                     |
| ------------------------------- | --------------------------------------------------------------------------------------------- |
| **🗓️ Filter Rentang Waktu**     | Memungkinkan pengguna untuk memilih periode waktu tertentu untuk analisis                     |
| **📋 Ringkasan Pesanan Harian** | Menampilkan jumlah pesanan dan pendapatan total untuk periode yang dipilih                    |
| **📊 Analisis Performa Produk** | Membandingkan produk dengan performa terbaik dan terburuk                                     |
| **👥 Demografi Pelanggan**      | Menganalisis distribusi pelanggan berdasarkan jenis kelamin, kelompok usia, dan negara bagian |
| **🏆 Analisis RFM**             | Mengidentifikasi pelanggan terbaik berdasarkan metrik Recency, Frequency, dan Monetary        |

---

## 📸 Tangkapan Layar

Dashboard terdiri dari beberapa bagian utama:

### 1️⃣ Filter Tanggal dan Informasi Umum

- Filter rentang waktu untuk analisis
- Metrik total pesanan dan pendapatan

### 2️⃣ Visualisasi Pesanan Harian

- Grafik garis yang menunjukkan jumlah pesanan per hari

### 3️⃣ Performa Produk

- Diagram batang yang membandingkan 5 produk terlaris dan 5 produk dengan penjualan terendah

### 4️⃣ Demografi Pelanggan

- Diagram batang yang menunjukkan distribusi pelanggan berdasarkan gender
- Diagram batang yang menunjukkan distribusi pelanggan berdasarkan kelompok usia
- Diagram batang yang menunjukkan distribusi pelanggan berdasarkan negara bagian

### 5️⃣ Analisis RFM

- Metrik rata-rata untuk Recency, Frequency, dan Monetary
- Diagram batang yang menampilkan 5 pelanggan terbaik berdasarkan parameter RFM

---

## ⚠️ Pemecahan Masalah Umum

<details>
<summary>Klik untuk melihat solusi masalah umum</summary>

Jika Anda mengalami masalah saat menyiapkan atau menjalankan dashboard, coba solusi berikut:

1. **Kesalahan dependensi paket**: Perbarui pip sebelum menginstal paket

   ```bash
   pip install --upgrade pip
   ```

2. **Streamlit tidak ditemukan**: Pastikan lingkungan virtual Anda diaktifkan dan streamlit diinstal

   ```bash
   pip show streamlit
   ```

3. **File data tidak ditemukan**: Periksa apakah `all_data.csv` berada di direktori yang benar

   ```bash
   # Di direktori dashboard
   ls -la  # Untuk Linux/MacOS
   dir     # Untuk Windows
   ```

4. **Port sudah digunakan**: Jika port 8501 sudah digunakan, Streamlit akan secara otomatis mencoba port lain

5. **Visualisasi tidak muncul**: Pastikan matplotlib dan seaborn terinstal dengan benar
   ```bash
   pip install --upgrade matplotlib seaborn
   ```
   </details>

---

<div align="center">

### 📊 Dibuat dengan ❤️ oleh Aditya Pratama

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aditypraa)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aditypraa)

© 2025

</div>
