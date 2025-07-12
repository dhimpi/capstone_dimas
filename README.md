
# 🫁 Capstone Project – Prediksi Risiko Penyakit Paru-Paru dengan Machine Learning dan IBM Granite AI

## 📌 Deskripsi Proyek

Proyek ini merupakan bagian dari tugas akhir (Capstone Project) yang bertujuan untuk:
- Memprediksi apakah seseorang berisiko terkena **penyakit paru-paru** berdasarkan data pribadi dan gaya hidup.
- Memberikan **analisis dan saran medis berbasis AI**, menggunakan model **IBM Granite** melalui API `Replicate`.

Notebook ini dirancang agar interaktif, mudah dipahami, dan siap digunakan oleh pengguna umum untuk **self-assessment kesehatan paru-paru**.

## 🧠 Teknologi yang Digunakan

| Teknologi | Fungsi |
|-----------|--------|
| Python | Bahasa pemrograman utama |
| Pandas | Manipulasi data |
| Scikit-learn | Pelatihan model prediktif (Random Forest) |
| Langchain + Replicate | Menghubungkan AI Granite |
| Google Colab | Platform eksekusi notebook |
| Google Drive | Penyimpanan dataset `.csv` |
| Kaggle | Sumber dataset asli |

## 📁 Struktur File

```
Capstone_project.ipynb     # Notebook utama
predic_tabel.csv           # Dataset berisi data kesehatan pengguna
README.md                  # Deskripsi proyek
```

## 📊 Dataset

Dataset diambil dari Kaggle:  
🔗 [https://www.kaggle.com/datasets/andot03bsrc/dataset-predic-terkena-penyakit-paruparu](https://www.kaggle.com/datasets/andot03bsrc/dataset-predic-terkena-penyakit-paruparu)

**Kolom-kolom utama:**
- Usia (Muda/Tua)
- Jenis Kelamin
- Merokok
- Bekerja
- Rumah Tangga
- Aktivitas Begadang
- Aktivitas Olahraga
- Asuransi
- Penyakit Bawaan
- Hasil (label target: Ya/Tidak terkena penyakit paru-paru)

## ⚙️ Cara Menjalankan Proyek

### 1. Buka Notebook
Gunakan Google Colab untuk membuka `Capstone_project.ipynb`.

### 2. Mount Google Drive
Unggah file dataset ke Google Drive, lalu hubungkan ke Colab:
```python
from google.colab import drive
drive.mount('/content/drive')
```

### 3. Jalankan Semua Cell
Pastikan semua cell dieksekusi berurutan:
- Preprocessing
- Training model
- Input user
- Prediksi + Analisis AI

### 4. Masukkan API Token
Gunakan token dari [Replicate](https://replicate.com/) untuk mengakses model AI Granite.

## 🧪 Contoh Output

```
=== HASIL ANALISIS ===
Status Risiko Penyakit Paru-paru Anda: 🚨 YA 🚨

=== Analisis AI Granite ===
Pasien memiliki risiko tinggi terkena penyakit paru-paru. Faktor utama meliputi merokok aktif dan kebiasaan begadang. Disarankan untuk mengurangi paparan asap rokok dan meningkatkan aktivitas fisik.
```

## 💡 Fitur Unggulan

- ✅ **Prediksi cepat dan akurat** menggunakan model Random Forest
- 🤖 **Analisis naratif** menggunakan model AI Granite 8B
- 🧾 Format input sederhana & ramah pengguna
- 📈 Siap dikembangkan menjadi aplikasi web

## ✍️ Kontributor

- **Nama**: Dimas Setia Adi  
- **Program Studi**: Teknik Informatika  
- **Universitas**: UIN Maulana Malik Ibrahim Malang  
- **Tahun**: 2025  

## 📜 Lisensi

Proyek ini hanya untuk tujuan edukasi. Hak data milik Kaggle dan model AI oleh IBM melalui Replicate.
