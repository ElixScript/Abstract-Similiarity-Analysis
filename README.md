

# 📚 **Tugas Pattern Recognition: Analisis Kemiripan Abstrak**

Repository ini berisi implementasi tugas **Pattern Recognition** untuk membandingkan tingkat kemiripan antar abstrak makalah dari **IJCCS (Indonesian Journal of Computing and Cybernetics Systems)**.

---

## 📋 **Deskripsi Tugas**
Tugas ini mencakup langkah-langkah berikut:
1. **Dataset**: 
   - Menggunakan 10 abstrak makalah dari IJCICS dalam **bahasa Indonesia** atau **bahasa Inggris** (dari 5 tahun terakhir).
2. **Preprocessing Teks**:
   - Mengikuti seluruh langkah-langkah pemrosesan teks seperti tokenisasi, stopword removal, dan stemming.
3. **Representasi Fitur**:
   - Membandingkan abstrak menggunakan **2 metode representasi fitur** (contoh: TF-IDF, Word2Vec).
4. **Pengukuran Similaritas**:
   - Menggunakan **2 metode perhitungan similaritas** (contoh: Cosine Similarity, Jaccard Similarity).
5. **Penggunaan Bahasa**:
   - Pemrograman Python atau bahasa lain diperbolehkan.
6. **Deadline**:
   - Minggu depan.

---

## 🚀 **Tujuan Proyek**
- **Menganalisis kemiripan antar dokumen** menggunakan metode representasi fitur dan pengukuran similaritas yang berbeda.
- Memahami bagaimana langkah-langkah pemrosesan teks memengaruhi hasil analisis kemiripan.

---

## 🛠️ **Teknologi dan Library**
- **Bahasa Pemrograman**:
  - Python (atau bahasa lain yang relevan).
- **Library yang Disarankan**:
  - Scikit-learn
  - NLTK atau Sastrawi (untuk preprocessing teks bahasa Indonesia)
  - Gensim
  - NumPy dan Pandas
  - Matplotlib atau Seaborn (untuk visualisasi)

---

## 🔍 **Langkah-Langkah Pemrosesan**
1. **Pengumpulan Data**:
   - Dataset berupa 10 abstrak dari IJCICS (format `.txt` atau `.csv`).
2. **Preprocessing Teks**:
   - Cleaning: Menghapus karakter khusus, angka, dan simbol.
   - Tokenisasi: Memecah teks menjadi token.
   - Stopword Removal: Menghapus kata-kata yang tidak memiliki makna penting.
   - Stemming: Mengubah kata menjadi bentuk dasarnya.
3. **Representasi Fitur**:
   - TF-IDF: Representasi berbasis statistik.
   - Word2Vec: Representasi berbasis embedding.
4. **Penghitungan Similaritas**:
   - Cosine Similarity: Mengukur sudut antara dua vektor.
   - Jaccard Similarity: Mengukur kesamaan antara dua set.

---

## 📈 **Hasil**
- **Metrik Evaluasi**: Analisis kemiripan ditampilkan menggunakan matriks similaritas.
- **Visualisasi**: Heatmap digunakan untuk memvisualisasikan hubungan antar abstrak.

---

