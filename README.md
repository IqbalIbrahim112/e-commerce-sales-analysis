# 🛒 E-Commerce Sales Analysis

Proyek ini bertujuan untuk menganalisis data penjualan dari sebuah platform e-commerce berdasarkan data historis transaksi, produk, pembayaran, pelanggan, dan wilayah. Analisis ini membantu dalam memahami pola pembelian, kategori produk unggulan, metode pembayaran populer, serta perubahan performa penjualan dari tahun ke tahun.

## 📁 Struktur Dataset

Semua data mentah berada di dalam folder `data/`, dengan rincian sebagai berikut:

- `customer.csv` : Data master pelanggan
- `customer_detail.csv` : Detail profil pelanggan
- `order.csv` : Data order utama
- `order_detail.csv` : Detail item di dalam setiap order
- `order_tab.csv` : Data tabulasi pesanan
- `payment_detail.csv` : Informasi metode pembayaran
- `product.csv` : Master produk
- `region.csv` : Data wilayah atau area
- `shipment.csv` : Detail pengiriman
- `sku_detail.csv` : Detail SKU (Stock Keeping Unit)
- `user_tab.csv` : Data pengguna

## 📝 Analisis yang Dilakukan

Berikut adalah rangkuman beberapa analisis utama dalam proyek ini:

1. **Analisis Bulanan Tahun 2021**
   - Menemukan bulan dengan nilai transaksi tertinggi sepanjang tahun 2021.

2. **Analisis Kategori Produk Tahun 2022**
   - Mengidentifikasi kategori dengan total transaksi terbesar pada 2022.

3. **Year-on-Year (YoY) Category Comparison**
   - Membandingkan nilai transaksi kategori produk tahun 2021 dan 2022.
   - Menunjukkan kategori yang mengalami peningkatan atau penurunan.

4. **Metode Pembayaran Terpopuler**
   - Menyaring 5 metode pembayaran paling banyak digunakan di 2022.

5. **Analisis Produk Populer**
   - Menentukan produk atau merek dengan transaksi tertinggi, seperti Apple, Samsung, Sony, Huawei, dan Lenovo.

## 💻 Teknologi

- PostgreSQL (untuk penulisan query)
- Python (opsional untuk visualisasi/analisis lanjutan)
- CSV (sebagai data source)

## 🚀 Cara Menjalankan

1. Import dataset dari folder `data/` ke database (PostgreSQL atau RDBMS lain).
2. Jalankan query SQL di folder ini sesuai kebutuhan analisis.
3. (Opsional) Lakukan eksplorasi lanjutan dengan Python menggunakan Pandas atau alat BI (misalnya Power BI, Tableau).

## 📊 Hasil

Hasil analisis dapat digunakan untuk:
- Optimasi strategi marketing
- Pengelolaan stok barang
- Peningkatan pelayanan pelanggan
- Rekomendasi produk ke pelanggan

## 📌 Catatan

- Pastikan struktur relasi antar tabel sesuai (contohnya `sku_id`, `payment_id`, `customer_id`).
- Data `order_detail` menjadi pusat transaksi yang dihubungkan ke data lain.

**Happy analyzing!** 🚀
