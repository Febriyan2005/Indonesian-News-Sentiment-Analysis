# 📰 Analisis Sentimen Berita Kesehatan Berbahasa Indonesia

Proyek Data Mining dan Natural Language Processing (NLP) untuk menganalisis sentimen berita kesehatan berbahasa Indonesia menggunakan data hasil web scraping.

Proyek mencakup proses pengumpulan data, preprocessing teks, analisis sentimen berbasis lexicon, serta visualisasi hasil analisis.

---

## 🎯 Tujuan Proyek

Proyek ini bertujuan untuk:

- Mengumpulkan data berita kesehatan melalui web scraping.
- Membersihkan dan mempersiapkan data teks untuk analisis.
- Menganalisis sentimen berita menjadi kategori positif dan negatif.
- Mengidentifikasi kata dan frasa yang sering muncul pada masing-masing sentimen.
- Menyajikan hasil analisis melalui visualisasi yang mudah dipahami.

---

## 📊 Dataset

Data dikumpulkan melalui proses web scraping berita kesehatan berbahasa Indonesia.

Jumlah data awal:

- **5.000 artikel berita**

Setelah proses pembersihan dan penghapusan data duplikat, diperoleh data yang digunakan untuk analisis sentimen.

---

## 🔄 Alur Analisis

```text
Web Scraping
     ↓
Data Cleaning
     ↓
Case Folding
     ↓
Normalisasi Kata
     ↓
Tokenization
     ↓
Stopword Removal
     ↓
Stemming
     ↓
Lexicon-Based Sentiment Analysis
     ↓
Visualisasi & Interpretasi
