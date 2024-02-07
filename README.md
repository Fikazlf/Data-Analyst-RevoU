## Analisis Transaksi Penjualan

### Deskripsi
Proyek ini merupakan analisis data transaksi penjualan yang dilakukan pada sebuah toko retail. Data transaksi mencakup informasi seperti tanggal transaksi, metode pembayaran, ID faktur, cabang toko, kota, tipe pelanggan, jenis kelamin pelanggan, jenis produk yang dibeli, harga satuan, dan jumlah barang yang dibeli.

### Langkah-langkah Proyek
1. **Pengumpulan dan Pembersihan Data:**
   - Data transaksi diunduh dari Google Sheets dan dibaca menggunakan pandas.
   - Dilakukan pembersihan data untuk mengatasi missing values, outlier, dan format yang tidak sesuai.
   - Kolom 'Date' diubah menjadi tipe data datetime.
   - Kolom baru 'Revenue' dibuat dengan mengalikan harga satuan dengan jumlah barang.

2. **Eksplorasi Data Awal (EDA):**
   - Diperiksa distribusi dan statistik ringkasan dari setiap kolom.
   - Ditemukan dan diperbaiki kesalahan penulisan pada kolom 'Gender'.
   - Dilakukan visualisasi untuk memahami jumlah transaksi berdasarkan metode pembayaran, cabang toko, kota, tipe pelanggan, jenis kelamin pelanggan, dan jenis produk.

3. **Analisis Tren Harian:**
   - Data diagregat berdasarkan tanggal untuk melihat tren harian pendapatan dan jumlah barang yang terjual.
   - Dilakukan visualisasi tren harian menggunakan plot garis.

4. **Analisis Pembayaran:**
   - Data diagregat berdasarkan metode pembayaran untuk melihat total pendapatan dan jumlah transaksi untuk setiap metode pembayaran.
   - Dilakukan visualisasi menggunakan plot batang untuk membandingkan total pendapatan dari setiap metode pembayaran.

5. **Analisis Berdasarkan Jenis Kelamin dan Jenis Produk:**
   - Data diagregat berdasarkan jenis kelamin dan jenis produk untuk melihat jumlah transaksi (faktur) untuk setiap kombinasi jenis kelamin dan jenis produk.
   - Dilakukan visualisasi menggunakan plot batang dengan hue berdasarkan jenis kelamin untuk membandingkan jumlah transaksi berdasarkan jenis produk.

### Library dan Penggunaan
Projek ini menggunakan library seperti pandas, numpy, matplotlib, dan seaborn untuk melakukan analisis data dan visualisasi. Data transaksi dibaca dari Google Sheets dan disimpan dalam bentuk DataFrame. Visualisasi dilakukan menggunakan berbagai jenis plot seperti plot garis, plot batang, dan pie chart.

### Tentang Data
Data transaksi penjualan berisi informasi tentang lebih dari 1000 transaksi yang dilakukan dalam rentang waktu tertentu. Setiap transaksi mencakup detail tentang tanggal transaksi, metode pembayaran, cabang toko, kota, tipe pelanggan, jenis kelamin pelanggan, jenis produk yang dibeli, harga satuan, dan jumlah barang yang dibeli. Analisis ini bertujuan untuk memberikan wawasan tentang pola pembelian pelanggan, performa penjualan, dan preferensi pelanggan berdasarkan jenis produk dan jenis kelamin.
