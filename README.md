# KLASIFIKASI-TEKS-MENGGUNAKAN-RNN
Proyek ini bertujuan untuk membangun model klasifikasi teks menggunakan arsitektur Recurrent Neural Network (RNN), khususnya LSTM dan GRU. Dataset yang digunakan berisi teks berita berbahasa Inggris dengan dua kategori utama, yaitu sport dan politics.

Langkah-langkah yang dilakukan dalam proyek ini meliputi:

Explorasi data – melihat distribusi label, memeriksa missing values, dan memahami karakteristik dataset.

Preprocessing – meliputi tokenisasi, padding, dan normalisasi agar data siap diproses model.

Pembangunan model – menggunakan RNN dengan dua varian, yaitu LSTM dan GRU, untuk membandingkan performa.

Pelatihan dan evaluasi – model dilatih pada data training dan diuji pada data validasi untuk mengevaluasi akurasi serta loss.

Kesimpulan – GRU menunjukkan hasil generalisasi yang lebih baik dengan akurasi validasi mencapai ±98–99%, sedangkan LSTM lebih cepat konvergen.

Cara Menjalankan Kode

Clone repository ini atau buka notebook di Kaggle:

git clone https://github.com/maulash-miee/KLASIFIKASI-TEKS-MENGGUNAKAN-RNN.git


Pastikan semua dependensi terinstal (bisa menggunakan Kaggle Notebook atau Google Colab).

pip install tensorflow keras pandas matplotlib scikit-learn


Jalankan notebook:

Upload file dataset transformer.csv ke environment notebook.

Buka file klasifikasi-teks-menggunakan-rnn.ipynb.

Eksekusi sel kode secara berurutan.

Hasil pelatihan model akan ditampilkan dalam bentuk grafik akurasi/loss serta evaluasi model pada data validasi.

Struktur Dataset

Dataset terdiri dari 928 baris dengan dua kolom:

data → teks berita

labels → kategori berita (sport atau politics)

Distribusi label:

sport: 511 data

politics: 417 data

Hasil

LSTM: akurasi validasi tinggi, lebih cepat konvergen.

GRU: akurasi validasi lebih stabil (hingga 98–99%), generalisasi lebih baik.
