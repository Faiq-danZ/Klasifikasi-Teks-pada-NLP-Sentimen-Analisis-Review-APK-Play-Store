# Klasifikasi Teks pada NLP: Sentimen Analisis Review APK Play Store

[![Python Version](https://img.shields.io/badge/python-3.14.2-blue.svg)](https://www.python.org)
[![Framework](https://img.shields.io/badge/Framework-TensorFlow/Keras-orange.svg)](https://tensorflow.org)

## 📌 Deskripsi Proyek
Proyek ini berfokus pada penerapan **Deep Learning** untuk melakukan analisis sentimen terhadap ulasan aplikasi di Google Play Store. Dengan menggunakan pendekatan *Natural Language Processing* (NLP), model ini dikembangkan untuk mengklasifikasikan opini pengguna ke dalam kategori **Positif**, **Netral**, atau **Negatif**.

Tujuan utama proyek ini adalah untuk memahami bagaimana arsitektur jaringan syaraf tiruan dapat menangkap konteks dan semantik dalam bahasa manusia, khususnya pada data teks yang tidak terstruktur seperti ulasan aplikasi.

## 🚀 Fitur Utama
* **Text Preprocessing:** Case folding, filtering, stopword removal, dan tokenization.
* **Word Embedding:** Representasi kata ke dalam ruang vektor untuk menangkap makna semantik.
* **Deep Learning Model:** Implementasi menggunakan arsitektur sekuensial (seperti **LSTM** atau **GRU**) yang efektif untuk data urutan teks.
* **Evaluation Metrics:** Visualisasi akurasi dan loss melalui grafik, serta evaluasi menggunakan Confusion Matrix.

## 🛠️ Tech Stack
* **Bahasa Pemrograman:** Python 3.14.2
* **Library Utama:**
  * `TensorFlow` / `Keras` (Model Deep Learning)
  * `Pandas` & `NumPy` (Data Manipulation)
  * `NLTK` / `Sastrawi` (NLP Preprocessing)
  * `Matplotlib` / `Seaborn` (Data Visualization)

## 📂 Struktur Repositori
```text
├── data/               # Dataset ulasan Play Store (.csv)
├── notebooks/          # Jupyter Notebook untuk eksperimen & pelatihan model
├── models/             # File model yang sudah dilatih (.h5 atau .keras)
├── requirements.txt    # Daftar library yang diperlukan
└── README.md           # Dokumentasi proyek
