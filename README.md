# Transaction Dashboard

## Profil Singkat: 
Sebuah perusahaan ritail multikategori yang berfokus pada penjualan produk elektronik, fashion, dan kebutuhan rumah tangga melalui platform digital dan toko fisik. Dengan beragam kategori seperti Mobiles & Tablets, Entertainment, Computing, Appliances, Men & Women Fashion, Home & Living, serta Beauty & Grooming, Trendora melayani konsumen dari berbagai segmen dengan pengalaman belanja yang modern dan personal.

## Tujuan Dashboard Penjualan
Dashboard ini dirancang untuk membantu manajemen memahami performa penjualan secara menyeluruh, mengidentifikasi tren, dan mengoptimalkan strategi promosi serta metode pembayaran. Seorang Product manager (PM) yang bersangkutan meminta bantuan tim Data Analyst untuk menganalisis performa penjualan. Untuk itu PM meminta sebuah dashboard dengan requirements sebagai berikut:
1. Menampilkan performa transaksi secara keseluruhan
2. Mengetahui trend penjualan
3. Mengetahui performa dari setiap metode pembayaran
4. Mengetahui product mana yang paling laku
5. Mengetahui spending untuk discount
6. Ringkasan transaksi untuk setiap produk dan konsumen

## Dataset
Dataset yang digunakan merupakan data transaksi penjualan dari tahun 2021 hingga 2022, terdiri dari 5.885 baris dan 15 kolom. Dataset ini mencakup informasi lengkap mengenai transaksi, produk, pelanggan, dan metode pembayaran.

### Struktur Kolom Dataset
Berikut adalah daftar kolom beserta penjelasannya:

- id: ID unik untuk setiap transaksi

- customer_id: ID pelanggan yang melakukan transaksi

- order_date: Tanggal transaksi dilakukan

- sku_id: ID produk (Stock Keeping Unit)

- sku_name: Nama produk

- category: Kategori produk (misalnya: Mobiles & Tablets, Fashion, dll.)

- price: Harga satuan produk

- qty_ordered: Jumlah produk yang dibeli

- before_discount: Total harga sebelum diskon

- discount_amount: Nilai diskon yang diberikan

- after_discount: Total harga setelah diskon

- is_gross: Status apakah harga termasuk pajak

- is_net: Status apakah harga bersih setelah pajak

- is_valid: Validitas transaksi

- payment_id: ID metode pembayaran

- payment_method: Jenis metode pembayaran (misalnya: e-wallet, transfer bank, dll.)

- base_price: Harga dasar produk sebelum margin

- cogs: Biaya pokok penjualan

- registered_date: Tanggal registrasi pelanggan

## Pembuatan mockup
Mockup ini dirancang untuk menyajikan insight penjualan secara menyeluruh melalui berbagai komponen visual yang terstruktur. Setiap bagian mewakili analisis spesifik yang mendukung pengambilan keputusan bisnis.

### Requiment
1. Menampilkan Performa Transaksi Secara Keseluruhan
- Metrik utama:
  - Total penjualan (sales)

  - Total konsumen yang melakukan transaksi

  - Profit

  - Total diskon

  - Kuantitas barang terjual

2. Mengetahui Tren Penjualan
- Visualisasi:

  - Line chart: Sales/Revenue vs Time

3. Mengetahui Performa Berdasarkan Metode Pembayaran
- Jumlah transaksi per metode pembayaran

  - Visual: Bar chart / Column chart

- Nilai transaksi per metode pembayaran

  - Visual: Bar chart / Column chart / Pie chart

4. Mengidentifikasi Produk Terlaris
- Nilai penjualan per produk

  - Visual: Bar chart / Column chart / Pie chart

5. Mengetahui Pengeluaran untuk Diskon
- Nilai diskon per produk/kategori

6. Ringkasan Transaksi per Produk dan Konsumen
- Produk A:

  - Jumlah terjual

  - Total revenue

  - Total diskon

- Konsumen A:

  - Jumlah transaksi

  - Total revenue

  - Total profit

- Visualisasi: Tabel

### Struktur Layout Mockup

<img width="878" height="1500" alt="image" src="https://github.com/user-attachments/assets/a9865879-9295-46f8-bb4f-ad12398d1d4e" />



