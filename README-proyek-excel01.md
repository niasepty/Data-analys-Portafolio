# Latihan Excel: Data Cleaning, VLOOKUP, dan Pivot Table

Proyek latihan ini dibuat untuk mempraktikkan tiga keterampilan dasar analisis data di Microsoft Excel: pembersihan data, pencarian data antar tabel, dan peringkasan data menggunakan Pivot Table.

## Isi Proyek

File `Latihan_Data_Cleaning_VLOOKUP.xlsx` terdiri dari beberapa sheet:

| Sheet | Deskripsi |
|---|---|
| `Data_Transaksi` | Data transaksi penjualan yang dibersihkan dari duplikasi dan inkonsistensi format |
| `Referensi_Produk` | Tabel master produk (kode, nama, dan harga satuan) sebagai sumber pencarian VLOOKUP |
| `Latihan_VLOOKUP` | Implementasi rumus VLOOKUP untuk menarik data nama produk dan harga berdasarkan kode produk |
| `pivot table` | Ringkasan otomatis dari data transaksi — menampilkan total penjualan per kota, rincian per produk, dan tren penjualan per bulan menggunakan Pivot Table |

## Keterampilan yang Dipelajari

### 1. Data Cleaning
- Mengidentifikasi dan menghapus baris data duplikat menggunakan fitur **Remove Duplicates**
- Memahami perbedaan antara duplikasi baris penuh dan duplikasi nilai per kolom
- Merapikan inkonsistensi teks (spasi berlebih, variasi kapitalisasi) menggunakan kombinasi rumus `TRIM()` dan `PROPER()`
- Mengonversi data tanggal yang tersimpan sebagai teks menjadi format Date menggunakan fitur **Text to Columns**

### 2. VLOOKUP
- Menyusun rumus `VLOOKUP()` untuk menarik data dari tabel referensi berdasarkan nilai kunci (kode produk)
- Menggunakan referensi sel absolut (`$`) agar rentang tabel referensi tidak berubah saat rumus disalin ke sel lain

### 3. Pivot Table
- Membuat ringkasan data agregat (total penjualan per kota)
- Menyusun Pivot Table dengan lebih dari satu dimensi (kota dan kode produk)
- Mengelompokkan data tanggal menjadi periode bulanan menggunakan fitur **Group**
- Menyusun tabel silang (*cross-tabulation*) untuk melihat tren penjualan per kota per bulan

## Tools
- Microsoft Excel
