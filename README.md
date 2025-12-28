# Credit Risk Prediction - ID/X Partners Data Scientist Project

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Scikit--Learn%20%7C%20Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
Repository ini berisi solusi *End-to-End* untuk masalah **Credit Risk Modeling** sebagai bagian dari Virtual Internship Experience (VIX) di **ID/X Partners**. Tujuan utama dari proyek ini adalah membangun model Machine Learning yang dapat memprediksi probabilitas seorang peminjam (borrower) mengalami gagal bayar (default).

## 💼 Business Understanding
Dalam industri perbankan dan multifinance, risiko kredit adalah kerugian yang terjadi karena peminjam gagal membayar kembali pinjaman atau memenuhi kewajiban kontraktualnya.

**Tujuan:**
1. Mengidentifikasi pola peminjam yang berisiko tinggi (Bad Loan) dan rendah (Good Loan).
2. Membantu perusahaan mengurangi kerugian finansial akibat kredit macet.
3. Memberikan rekomendasi persetujuan pinjaman berdasarkan data historis.

## 📂 Struktur Repository
Berikut adalah deskripsi file yang tersedia dalam repository ini:

| Nama File | Deskripsi |
| :--- | :--- |
| `credit_risk_analysis.ipynb` | **Notebook Utama**. Berisi proses lengkap mulai dari Data Cleaning, Exploratory Data Analysis (EDA), Feature Engineering, hingga Evaluasi Model. |
| `credit_risk_model.py` | **Python Script**. Versi script dari model untuk kebutuhan deployment atau testing modular. |
| `media presentasi end-to-end solution.pdf` | **Laporan Bisnis**. Slide presentasi yang menjelaskan metodologi, *finding* penting, dan rekomendasi bisnis untuk stakeholder. |

## 🛠️ Metodologi
Pengerjaan proyek ini dilakukan dengan tahapan sebagai berikut:
1. **Data Preprocessing**: Handling missing values, checking duplicates, dan penyesuaian tipe data.
2. **Exploratory Data Analysis (EDA)**: Menganalisis korelasi antar fitur dan distribusi target variable.
3. **Feature Engineering**: Melakukan encoding, scaling, dan menangani *imbalanced data* (jika ada).
4. **Modeling**: Menguji beberapa algoritma (seperti Logistic Regression, Random Forest, atau XGBoost).
5. **Evaluasi**: Menggunakan metrik **ROC-AUC**, **Accuracy**, dan **Recall** (fokus pada meminimalkan False Negative).

## 🚀 Cara Menjalankan Project
Untuk menjalankan notebook analisis di lokal komputer Anda:

1. Clone repository ini:
   ```bash
   git clone [https://github.com/RikaProjects/IDX-Partners-Data-Scientist-Project.git](https://github.com/RikaProjects/IDX-Partners-Data-Scientist-Project.git)
