# 📰 Analisis Sentimen Berita Kesehatan Berbahasa Indonesia

Pipeline **Data Mining dan Natural Language Processing (NLP)** untuk mengumpulkan, membersihkan, dan menganalisis sentimen berita kesehatan berbahasa Indonesia menggunakan data hasil **web scraping dari Liputan6**.

---

## 📌 Ringkasan Proyek

Proyek ini membangun pipeline analisis teks dari tahap pengumpulan data hingga interpretasi hasil.

Data berita kesehatan dikumpulkan melalui **web scraping**, kemudian diproses melalui beberapa tahapan preprocessing, yaitu:

- Data cleaning
- Penghapusan data duplikat
- Case folding
- Normalisasi kata
- Tokenization
- Stopword removal
- Stemming

Setelah data siap dianalisis, digunakan pendekatan **lexicon-based sentiment analysis** untuk mengidentifikasi kecenderungan sentimen setiap artikel.

Hasil analisis kemudian divisualisasikan menggunakan distribusi sentimen, word cloud, serta analisis bigram dan trigram.

---

## 🎯 Tujuan

- Mengotomatisasi pengumpulan berita kesehatan melalui web scraping.
- Membersihkan dan menyiapkan data teks untuk analisis.
- Mengidentifikasi kecenderungan sentimen menggunakan pendekatan berbasis leksikon.
- Menemukan kata dan frasa yang dominan pada berita.
- Menyajikan hasil analisis dalam visualisasi yang mudah dipahami.

---

## 🔄 Alur Pemrosesan

```text
Web Scraping
     ↓
Data Collection
     ↓
Data Cleaning
     ↓
Remove Duplicate Data
     ↓
Case Folding
     ↓
Word Normalization
     ↓
Tokenization
     ↓
Stopword Removal
     ↓
Stemming
     ↓
Lexicon-Based Sentiment Analysis
     ↓
Data Visualization
     ↓
Interpretation
