## 📱 Deteksi Penipuan Pesan Singkat (SMS Fraud Detection)
Aplikasi ini merupakan sistem deteksi pesan singkat (SMS) yang bertujuan untuk mengidentifikasi apakah sebuah pesan tergolong penipuan, promosi, spam, atau normal menggunakan algoritma Logistic Regression dan teknik Natural Language Processing.

📌link aplikasi : https://deteksipenipuanpesan-psyifa.streamlit.app/

## 📊 Fitur Aplikasi
- Klasifikasi pesan menjadi 4 label: Normal, Fraud, Promo, dan Spam.
- Visualisasi data:
  - Grafik batang frekuensi label.
  - Word Cloud untuk kategori Fraud dan Promo.
  - Grafik modus penipuan digital.
- Input pesan manual untuk dianalisis langsung oleh pengguna.
- UI interaktif menggunakan Streamlit.

## 🔬 Metodologi Penelitian
1. Pengumpulan Data
2. Preprocessing
3. Cleaning :
   - Tokenization
   - Normalisasi Kata
   - Case Folding
   - Stopword Removal
   - Stemming
   - Ekstraksi Fitur (TF-IDF)
   - Seleksi Fitur (Chi-Square)
   - Klasifikasi (Logistic Regression)
   - Evaluasi Model
   - Pembuatan Aplikasi (Streamlit)

## 📁 Dataset
Dataset yang digunakan adalah SMS Spam Bahasa Indonesia yang tersedia di repositori id-nlp-resource by @kmkurn. Dataset terdiri dari pesan SMS berlabel penipuan dan non-penipuan.

## 🧪 Evaluasi Model
Model dikembangkan menggunakan metode supervised learning dan dievaluasi dengan metrik berikut:
- Akurasi: 90%
- Precision: 0.90
- Recall: 0.86
- F1-Score: 0.88
