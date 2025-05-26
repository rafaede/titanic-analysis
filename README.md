# 🚢 Titanic Survival Prediction Analysis

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2%2B-yellowgreen)

Proyek ini menganalisis data penumpang Titanic dan memprediksi kelangsungan hidup menggunakan Logistic Regression.

---

## 📋 Daftar Isi
- [Struktur Folder](#-struktur-folder)
- [Cara Menjalankan](#-cara-menjalankan)
- [Hasil Analisis](#-hasil-analisis)
- [Lisensi](#-lisensi)

---

## 📁 Struktur Folder
```
titanic-analysis/
├── titanic/
│   ├── gender_submission.csv
│   ├── train.csv
│   └── test.csv
└── titanic-survival-prediction.ipynb
```

---

## 🛠️ Cara Menjalankan
1. Clone repositori:
   ```bash
   git clone https://github.com/rafaede/titanic-analysis.git
   ```

2. Buka Jupyter Notebook:
   ```bash
   jupyter notebook titanic-survival-prediction.ipynb
   ```

3. Install dependencies (jika diperlukan):
   ```bash
   pip install pandas scikit-learn matplotlib
   ```

---

## 📊 Hasil Analisis
### Akurasi Model: **78%**
### Fitur Paling Berpengaruh:
1. Jenis Kelamin (♀: 74% selamat, ♂: 19% selamat)
2. Kelas Tiket (Kelas 1: 62% selamat)
3. Usia (Anak-anak <10 tahun: 59% selamat)

---

## 📝 Lisensi
[MIT License](LICENSE)
