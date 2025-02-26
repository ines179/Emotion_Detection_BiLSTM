# Emotion_Detection_Model BiLSTM

Model Deteksi Emosi di Media Sosial mengenai Perbincangan Telekomunikasi

## Dataset
Data yang digunakan merupakan data mengenai perbincangan telekomunikasi yang mecakup mention dan keyword dari Indosat, Telkomsel, XL, dan Axis yang dikumpulkan dari media sosial Twitter, YouTube, Instagram, News, Facebook, dan Tiktok. Rentang waktu pengambilan data dimulai dari tanggal 01 Juni 2023 hingga 21 Agustus 2023. Dataset terdiri dari 11.730 data teks dari berbagai media sosial yang telah dilabeli 6 emosi yaitu kegembiraan, terkejut, kesedihan, ketakutan, kemarahan, dan rasa jijik.

Label-label tersebut melibatkan angka, dengan ketentuan label (1) untuk ketakutan, label (2) untuk rasa jijik, label (3) untuk kemarahan, label (4) untuk terkejut, label (5) untuk kegembiraan, dan label (6) untuk kesedihan. Pelabelan data emosi dilakukan oleh peneliti dengan bantuan dua mahasiswa psikologi.

## Data Balancing
Penanganan Imbalanced Data dilakukan dengan menggunakan metode Borderline SMOTE

## Word Embeddings
Penelitian ini menggunakan metode word embedding yaitu FastText Pre-Trained Model.

## Pemodelan
Pemodelan pada penelitian ini akan menggunakan metode Bidirectional Long Short-Term Memory (BiLSTM) dengan menggunakan Hyperparameter Tuning.

## Sitasi
Jika Anda ingin mempublikasikan penelitian yang menggunakan dataset atau code penelitian ini, silakan mengutip publikasi ini:
Sandrina Najwa, Sri Winarni, Anindya Apriliyanti Pravitasari, Yuyun Hidayat, Emotion classification in social media posts related to telecommunication services using bidirectional LSTM, Commun. Math. Biol. Neurosci., 2025 (2025), Article ID 16

## Copyright
Karya ini dilisensikan di bawah lisensi Creative Commons Attribution License, yang mengizinkan penggunaan, distribusi, dan reproduksi tanpa batas dalam media apa pun, asalkan karya aslinya dikutip dengan benar
