# 📊 Dokumentasi Proyek Analisis Data

## 📝 Deskripsi Proyek

Proyek ini berisi analisis data untuk mengidentifikasi preferensi produk berdasarkan demografi pelanggan, seperti gender dan kelompok usia. Analisis ini bermanfaat untuk memahami pola pembelian dan strategi pemasaran yang lebih efektif menggunakan dataset DicodingCollection yang merupakan modifikasi dari dataset Shopping Cart Database.

## 🗂️ Struktur Proyek

```markdown
proyek_analisis_data/
│
├── notebook.ipynb # Notebook utama yang berisi analisis data
├── Pipfile # File konfigurasi dependensi
├── Pipfile.lock # Lock file untuk versioning dependensi
├── .gitignore # File untuk mengabaikan file tertentu dari git
└── README.md # Dokumentasi proyek
```

## 🔧 Persyaratan Sistem

- Python 3.13
- pipenv

## ⚙️ Cara Mengkloning dan Menjalankan Proyek

1. **Kloning Repositori**

   ```bash
   git clone [URL_REPOSITORI]
   cd proyek_analisis_data
   ```

2. **Membuat dan Mengaktifkan Lingkungan Virtual**

   ```bash
   pipenv shell
   ```

3. **Instalasi Dependensi**

   ```bash
   pipenv install
   ```

   Instal paket-paket yang diperlukan untuk menjalankan analisis.

4. **Menjalankan Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Setelah browser terbuka, buka file `notebook.ipynb` untuk melihat dan menjalankan analisis.

---

## 📁 Dataset

Dataset yang digunakan dalam proyek ini berisi informasi mengenai:

- **Preferensi produk pelanggan**
- **Data demografi pelanggan** (gender dan usia)
- **Data pembelian**

> **Catatan:** Pastikan dataset berada di lokasi yang benar sebelum menjalankan notebook.

## 📈 Analisis yang Dilakukan

### 1. 🔍 Eksplorasi Data Awal

<details>
<summary>Expand untuk detail</summary>

- **Struktur Data**: Pemeriksaan kolom, tipe data, dan relasi antar variabel
- **Statistik Deskriptif**: Analisis mean, median, dan distribusi data
- **Penanganan Missing Values**: Identifikasi dan strategi penanganan data yang hilang
</details>

### 2. 👥 Analisis Demografi

<details>
<summary>Expand untuk detail</summary>

| Analisis        | Deskripsi                                   |
| --------------- | ------------------------------------------- |
| **Gender**      | Preferensi produk berdasarkan gender        |
| **Usia**        | Preferensi produk berdasarkan kelompok usia |
| **Pivot Table** | Tabulasi silang untuk visualisasi pola      |

</details>

### 3. 📊 Visualisasi Data

<details>
<summary>Expand untuk detail</summary>

- **Distribusi Preferensi**:

  ```
  Grafik batang dan pie chart menampilkan distribusi preferensi produk
  ```

- **Perbandingan Demografi**:

  ```
  Visualisasi perbandingan preferensi antar kelompok demografi
  ```

- **Pola Pembelian**:
  ```
  Trend dan pola pembelian dalam bentuk grafik deret waktu
  ```
  </details>

---

## 🔍 Hasil Analisis

Analisis ini menghasilkan wawasan terkait selera tipe produk pelanggan berdasarkan gender dan kelompok usia. Informasi ini dapat digunakan untuk:

- Strategi pemasaran yang lebih ditargetkan
- Pengembangan produk sesuai preferensi kelompok tertentu
- Optimalisasi inventaris berdasarkan demografi pelanggan

## 👥 Kontributor

Aditya Pratama
