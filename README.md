# Proyek TripleTen 8:  Analisis Data Toko Daring untuk Meningkatkan Pendapatan Menggunakan A/B Testing

# Tujuan :

Memprioritaskan hipotesis dan menjalankan uji A/B untuk mengetahui apakah hipotesis tersebut dapat meningkatkan pendapatan toko daring

# Data :

/datasets/hypotheses_us.csv
- Hypotheses — deskripsi singkat tentang hipotesis
- Reach — jangkauan pengguna, dalam skala satu hingga sepuluh
- Impact — dampak terhadap pengguna, dalam skala satu hingga sepuluh
- Confidence — keyakinan pada hipotesis, dalam skala satu sampai sepuluh
- Effort — sumber daya yang diperlukan untuk menguji hipotesis, dalam skala satu sampai sepuluh. Semakin tinggi nilai Effort, semakin intensif sumber daya pengujiannya.

/datasets/orders_us.csv
- transactionId — ID pesanan
- visitorId — ID pengguna yang membuat pesanan
- date — tanggal dibuatnya pesanan
- revenue — pendapatan dari pesanan
- group — kelompok uji (test group) A/B tempat pengguna berada
  
/datasets/visits_us.csv Unduh dataset
date — tanggal
group — kelompok uji (test group) A/B
visits — jumlah kunjungan pada tanggal yang ditentukan untuk kelompok uji A/B yang ditentukan

# Library : 

pandas, matplotlib, numpy, seaborn, scipy

