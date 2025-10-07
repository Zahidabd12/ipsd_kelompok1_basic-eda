# 🩺 Exploratory Data Analysis: Insurance Dataset

## 👥 Kelompok
| Nama | NIM |
|------|-----|
| Zahid Abdullah | [103102400034] |
| Lasmauli Yunita | [103102400026] |
| Zalsabilah Rezky Amelia Arep | [103102400043] |
| Adhinda Dwi Rahmadilla | [103102400061] |
| Asaagama Nashrul Haq | [103102400065] |

---

## 📂 Struktur Repository
📁 IPSD_M3_EDA/<br>
┣ 📜 insurance.csv → Dataset utama <br>
┣ 📘 IPSD_M3_EDA.ipynb → Notebook analisis EDA <br>
┗ 📄 README.md → Dokumentasi project 

## 📊 Deskripsi Dataset
Dataset ini berisi informasi mengenai **biaya asuransi kesehatan** berdasarkan beberapa faktor seperti usia, jenis kelamin, indeks massa tubuh (BMI), jumlah anak, kebiasaan merokok, dan wilayah tempat tinggal.

**Jumlah data:** 1338 baris  
**Jumlah kolom:** 7  

**Fitur-fitur:**
- `age`: Usia pemegang polis (tahun)
- `sex`: Jenis kelamin (male/female)
- `bmi`: Indeks massa tubuh
- `children`: Jumlah anak tanggungan
- `smoker`: Status merokok (yes/no)
- `region`: Wilayah tempat tinggal
- `charges`: Biaya asuransi (USD)

---

## 🌐 Sumber Dataset
Dataset ini diambil dari Kaggle:  
🔗 [Medical Cost Personal Datasets – Kaggle](https://www.kaggle.com/datasets/mosapabdelghany/medical-insurance-cost-dataset)  

---

## 🎯 Tujuan Analisis
1. Melakukan **Exploratory Data Analysis (EDA)** terhadap dataset `insurance.csv`.  
2. Mengidentifikasi pola dan hubungan antar variabel (misalnya pengaruh usia, BMI, dan kebiasaan merokok terhadap biaya asuransi).  
3. Menampilkan hasil analisis berupa grafik dan insight yang mudah dipahami.

---

## 🛠️ Tools dan Library
Project ini menggunakan bahasa pemrograman **Python** dengan beberapa library pendukung:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
## 🚀 Cara Menjalankan
1. Clone repository ini:
```
git clone https://github.com/Zahidabd12/ipsd_kelompok1_basic-eda
cd nama-repo
```
2. Buka file notebook:
```
jupyter notebook IPSD_M3_EDA.ipynb
```
3. Jalankan sel-sel kode secara berurutan untuk melihat hasil analisis dan visualisasi.

## 📈 Hasil dan Temuan Utama
- Perokok memiliki rata-rata biaya asuransi jauh lebih tinggi dibanding non-perokok.
- Usia berbanding lurus dengan biaya asuransi, terutama bagi perokok.
- BMI tinggi cenderung meningkatkan biaya, menunjukkan korelasi antara obesitas dan risiko kesehatan.
- Faktor wilayah (region) tidak menunjukkan perbedaan signifikan terhadap biaya.

## 🧾 Kesimpulan
- Dari hasil EDA, ditemukan bahwa status merokok dan usia adalah dua faktor paling berpengaruh terhadap biaya asuransi kesehatan.
- Analisis ini memberikan dasar penting untuk pengembangan model prediksi biaya asuransi di tahap selanjutnya.
