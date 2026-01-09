# Risfi_Ayu_Sandika_Analitik_Teks
Nama : Risfi Ayu Sandika
NIM : 24917035
# Analisis Sentimen Ulasan Gojek Menggunakan IndoBERT

Repository ini berisi kode dan laporan tugas akhir mata kuliah Analitik Teks.

## Deskripsi
Penelitian ini bertujuan untuk melakukan analisis sentimen terhadap ulasan aplikasi Gojek menggunakan model pretrained IndoBERT. Sentimen diklasifikasikan menjadi tiga kelas: positif, netral, dan negatif.

## Dataset
Dataset berasal dari ulasan aplikasi Gojek di Google Play Store yang telah dibersihkan (cleaned).

## Metodologi
- Preprocessing teks
- Tokenisasi menggunakan IndoBERT tokenizer
- Fine-tuning model IndoBERT
- Evaluasi menggunakan accuracy, precision, recall, F1-score
- Visualisasi confusion matrix

## Model
- Pretrained Model: `indobenchmark/indobert-base-p1`
