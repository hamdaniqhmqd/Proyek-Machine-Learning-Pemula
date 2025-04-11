# Proyek Machine Learning Pemula - Dicoding

Repositori ini berisi dua proyek akhir dari kelas **Machine Learning Pemula** Dicoding oleh **Ahmad Hamdani**:

1. 📊 Clustering pada dataset `clustering_superstore.csv`
2. 🤖 Klasifikasi data menggunakan model machine learning dasar

---

## 📁 Daftar File

### 1. `[Clustering] Submission Akhir BMLP_Ahmad Hamdani.ipynb`

Notebook ini berfokus pada analisis segmentasi pelanggan dengan pendekatan **unsupervised learning** menggunakan metode **KMeans Clustering**. Dataset yang digunakan adalah `clustering_superstore.csv`.

#### 🔍 Langkah-langkah Analisis:

- **Eksplorasi Data**: Memeriksa informasi awal dan ringkasan statistik dataset.
- **Preprocessing**:
  - Encoding variabel kategorikal
  - Normalisasi fitur dengan `MinMaxScaler`
  - Seleksi fitur dengan `VarianceThreshold`
  - Reduksi dimensi menggunakan PCA
- **Clustering**:
  - Menentukan jumlah klaster optimal dengan `KElbowVisualizer`
  - Evaluasi klaster dengan **Silhouette Score**
  - Visualisasi hasil clustering
- **Insight**: Menemukan pola klaster berdasarkan variabel seperti profit, sales, segment, dan lainnya.

---

### 2. `[Klasifikasi] Submission Akhir BMLP_Ahmad Hamdani.ipynb`

Notebook ini menunjukkan bagaimana melakukan klasifikasi data menggunakan algoritma supervised learning. (Silakan lihat notebook untuk rincian lebih lanjut).

---

## 🧪 Instalasi dan Persiapan Lingkungan

### 1. Clone Repository (opsional)

```bash
git clone https://github.com/hamdaniqhmqd/Proyek-Machine-Learning-Pemula.git
cd Proyek-Machine-Learning-Pemula
```

### 2. Buat dan Aktifkan Virtual Environment

**Windows:**

```bash
python -m venv env
env\Scripts\activate
```

**Mac/Linux:**

```bash
python3 -m venv env
source env/bin/activate
```

### 3. Instalasi Requirements

```bash
pip install -r requirements.txt
```

---

## 📝 Catatan

- Pastikan Python versi 3.9 atau lebih baru.
- Jika menggunakan Python 3.10+, pastikan modul `distutils` tersedia. Jika tidak, install secara manual:
  ```bash
  pip install setuptools
  ```
