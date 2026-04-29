<div align="center">

# Laporan Tugas APBO

*"Untuk memenuhi tugas pada mata kuliah Analisis Pemrograman Berbasis Objek (A)"*

<br>

<img src="logo up.png" alt="Logo Universitas Pancasila" width="250">

<br>
<br>

**Disusun Oleh Kelompok 10:**
| Nama Anggota | NIM |
| :--- | :--- |
| AA Rangga | 4524210001 |
| Dina Camelia Putri | 4524210028 |
| Evelin Ade Oktalia | 4524210031 |
| Fais Base Febrian | 4524210033 |
| Muhamad Edvin Hidayat | 4524210054 |

<br>

**Dosen Pengampu:**
Adi Wahyu Pribadi, S.Si., M.Kom

<br>
<br>

# PROGRAM STUDI TEKNIK INFORMATIKA
# FAKULTAS TEKNIK UNIVERSITAS PANCASILA
# 2026

---
</div>

<h2 align="center">Topik</h2>

<h2 align="center">Literasi bacaan</h2>

<h2 align="center">Pertanyaan</h2>
<h4>List Pertanyaan Wawancara</h4>
1. Apa nama usaha bapak/ibu?
2. Apa bentuk usaha yang bapak/ibu lakukan?
3. Apakah usaha ini milik sendiri/franchise/reseller?
4. Apa saja langkah langkah kegiatan usaha yang dilakukan? 
5. Apakah ada kendala tertentu dalam melakukan usaha ini? (Seperti salah pencatatan keuangan, kesulitan mencatat stok barang, dll)
6. Apakah dalam usaha ini sudah mempunyai sistem?
7. Dalam melakukan kegiatan usaha apakah perlu sistem tertentu? (Seperti sistem manajemen keuangan/sistem pelaporan)
8. Apakah ada pembagian struktural kerja, kalau ada jobdesknya apa saja
9. Apakah pendataan sekarang masih secara manual? kalau iya, menggunakan apa? apakah excel? atau pembukuan?
10. Apakah mempunyai toko online?
<h2 align="center">Dokumentasi</h2>

<h2 align="center">Alur bisnis</h2>

<h2 align="center">Use Case</h2>
<p align="center">
<img src="image/UseCaseSushiMod.svg" width="700" height="700" align="center">
</p>
<h4>1. Aktor Sistem</h4>
  <ol>Terdapat dua aktor yang berinteraksi dengan sistem:</ol>
  <ol>Penjual: Pengguna yang bertanggung jawab mengelola operasional toko, data barang, dan laporan.</ol>
  <ol>Pelanggan: Pengguna yang melakukan aktivitas pemilihan menu dan transaksi pembelian.</ol>
<h4>2. Fungsionalitas (Use Case)</h4>
A. Sisi Penjual
  <ol>Penjual memiliki wewenang untuk melakukan manajemen data di balik layar:</ol>
  <ol>Mengelola Profile: Memperbarui informasi akun penjual.</ol>
  <ol>Mengelola Stock Penjualan: Memantau dan memperbarui ketersediaan produk.</ol>
  <ol>Mengelola Laporan Keuangan: Melihat dan mengatur data pemasukan/pengeluaran.</ol>
  <ol>Melihat Data Penjualan Menu Populer: Analisis data untuk melihat produk mana yang paling laku.</ol>
  <ol>Mengelola Barang Operasional Toko: Mengatur kebutuhan inventaris pendukung toko.</ol>
  <ol>Mengelola Pesanan Pelanggan: Memproses pesanan yang masuk dari pelanggan.</ol>
B. Sisi Pelanggan
    <ol>Pelanggan berinteraksi dengan sistem untuk kebutuhan belanja:</ol>
    <ol>Melihat Menu: Menjelajahi daftar produk yang tersedia.</ol>
    <ol>Memasukkan Menu ke Keranjang: Memilih produk sebelum melakukan checkout.</ol>
    <ol>Melakukan Pembelian: Memproses pesanan dari keranjang belanja.</ol>
    <ol>Melakukan Pembayaran: Menyelesaikan transaksi secara finansial.</ol>
<h4>3. Relasi include dan Autentikasi</h4>
Di tengah diagram terdapat Use Case Autentikasi yang dihubungkan dengan garis putus-putus berlabel include dari semua Use Case lainnya. Hal ini menunjukkan bahwa Autentikasi (login/verifikasi identitas) adalah syarat wajib. Artinya, baik Penjual maupun Pelanggan tidak dapat menjalankan fitur apa pun (seperti melihat laporan atau melakukan pembayaran) sebelum mereka berhasil melakukan proses autentikasi terlebih dahulu.
