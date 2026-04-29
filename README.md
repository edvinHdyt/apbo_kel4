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

<h2 align="center">Pendahuluan</h2>
<h4>Latar Belakang Pemilihan Topik</h4>

Perkembangan teknologi informasi saat ini telah memberikan dampak signifikan terhadap berbagai sektor usaha, termasuk pada bidang Food and Beverage (F&B). Penerapan sistem informasi dalam pengelolaan usaha menjadi salah satu faktor penting dalam meningkatkan efisiensi, akurasi, serta kualitas pelayanan kepada pelanggan. <br>
Namun demikian, masih banyak usaha kecil dan menengah, khususnya pada sektor cafe atau kuliner, yang belum memanfaatkan sistem terintegrasi dalam operasionalnya. Sebagian besar proses bisnis masih dilakukan secara manual atau menggunakan alat bantu sederhana seperti aplikasi spreadsheet. Kondisi ini berpotensi menimbulkan berbagai permasalahan, antara lain kesalahan dalam pencatatan keuangan, kesulitan dalam pengelolaan stok bahan baku, serta kurang optimalnya koordinasi antar karyawan. <br>
Berdasarkan hasil wawancara yang telah dilakukan dengan pemilik usaha Sushi Mood, diketahui bahwa usaha tersebut masih menggunakan pencatatan berbasis Excel dan belum memiliki sistem manajemen yang terintegrasi. Selain itu, belum terdapat pembagian sistem kerja yang terstruktur secara formal, sehingga seluruh aktivitas operasional masih mengandalkan koordinasi langsung antar karyawan. <br>
Oleh karena itu, topik mengenai perancangan sistem manajemen usaha cafe dipilih sebagai fokus dalam penelitian ini, dengan harapan dapat memberikan solusi yang mampu meningkatkan efektivitas dan efisiensi operasional usaha. <br>

<h4>Tujuan Wawancara</h4>
Adapun tujuan dilakukannya wawancara dalam kegiatan ini adalah sebagai berikut:
  <ol>1.Mengidentifikasi proses bisnis yang sedang berjalan pada usaha cafe.</ol>
  <ol>2.Mengetahui kendala dan permasalahan yang dihadapi dalam operasional usaha. </ol>
  <ol>3.Menggali kebutuhan sistem informasi yang dapat mendukung kegiatan usaha. </ol>
  <ol>4.Mengumpulkan data sebagai dasar dalam perancangan solusi sistem yang sesuai dengan kebutuhan pengguna (user). </ol>

<h4>Destinasi Wawancara</h4>
Kegiatan wawancara dilakukan pada salah satu usaha di bidang kuliner dengan rincian sebagai berikut:
   <ol>-Nama Usaha : Sushi Mood</ol>
   <ol>-Bidang Usaha : Food and Beverage (F&B)</ol>
   <ol>-Jenis Kepemilikan : Usaha milik pribadi </ol>
   <ol>-Narasumber : Caesar (Pemilik Usaha) </ol>
Pemilihan usaha ini didasarkan pada kondisi usaha yang sedang berkembang serta belum menerapkan sistem informasi secara terintegrasi, sehingga relevan untuk dijadikan studi kasus dalam perancangan sistem.

<h2 align="center">Literasi bacaan</h2>
<h4><b>Penerapan Sistem Informasi Akuntansi pada Usaha Kedai Kopi: Studi Kasus pada Base Coffee Indonesia.</b></h4>
Base Coffee Indonesia adalah sebuah cafe yang yang sudah menggunakan sistem POS (Point Of Sale) dalam pelayanannya. Sistem pos yang digunakan oleh Base Coffee saat ini hanya mencangkup pencatatan untuk penjualan harian dan juga pembelian seperti atk dan kebutuhan-kebutuhan kecil lainnya, sedangkan untuk data pembelian stok cafe atau barang-barang operasional lainnya saat ini belum ada pencatatan data pembeliannya. Alur untuk laporan penjualan harian juga masih hanya dilaporkan ke manager di setiap cafe saja, sedangkan untuk pelaporan ke owner/pemilik masi dilakukan secara manual oleh manager di setiap cafe dengan cara menulis nota akumulasi penjualan harian dan akan dilaporkan kepada owner dengan waktu tidak tentu.Hal ini mengakibatkan kurangnya efisiensi dalam pendataan menyeluruh terhadap laporan keuangan dari operasional cafe.

Dengan permasalahan-permasalahan tersebut, Djuri dkk jurnal ini melaporkan bahwa terdapat beberapa resiko dari sistem pencatatan dan pembukuan yang ada saat ini, seperti:
1. Risiko kesalahan pencatatan pada pembukuan Base Coffee Indonesia 
2. Risiko fraud dalam pencatatan penerimaan dan pengeluaran kas
3. Risiko terjadinya fraud dalam hal pencatatan persediaan bahan baku
4. Risiko Analisa dan kesalahan informasi terhadap aktivitas dalam perusahaan 
Dengan permasalahan-permasalahan yang ada Djuri dkk mengusulkan untuk membuat sistem informasi akuntansi demi memperbaiki proses pencatatan data-data operasional yang dilakukan oleh cafe.

<h4><b>PENGARUH PENGGUNAAN SISTEM POINT OF SALE (POS) TERHADAP KINERJA KEUANGAN DAN MANAJEMEN STOK PADA COFFEE BAWA STUDIO</b></h4>
Melalui jurnal tersebut, Putri et al melakukan penelitian pada coffee shop bawa studio mengenai pengaruh sistem pos terhadap kinerja keuangan dan manajemen stok pada cafe. Sistem manajemen yang dipakai pada cafe tersebut adalah Olsera POS, sistem ini telah terintegrasi dengan sistem kasir dan juga penjualan sehingga mampu untuk melakukan pencatatan stok barang dan juga penjualan yang dilakukan oleh cafe, beberapa keuntungan yang didapatkan setelah cafee menggunakan sistem ini adalah meningkatkan efisiensi operasional, meminimalkan permasalahan dalam pencatatan transaksi, dan memudahkan laporan pencatatan laporan keuangan cafe.

Putri et al juga menyebutkan bahwa keuntungan dari penggunaan sistem pos ini tidak hanya berdampak dari sisi keuangan saja melainkan dapat dilihat dari kepemilikan aset jangka panjang yang menguntungkan. Aplikasi pos pada dunia UMKM dinilai meningkatkan citra yang dimiliki perusahaan karena aplikasi ini berhubungan langsung dengan pelayanan konsumen sehingga konsumen akan menilai umkm yang telah menggunakan aplikasi ini sudah mengikuti perkembangan jaman sehingga kepercayaan konsumen terhadap perusahaan menjadi semakin meningkat. 

Sedangkan untuk manfaat dalam kinerja keuangan adalah adanya peningkatan akurasi dan transparansi semua transaksi (tunia, QRIS, debit) yang tercatat secara otomatis dan real time; Penyusunan laporan keuangan seperti laporan mingguan dan bulanan yang dapat diakses secara cepat, termasuk semua rincian pembayaran; Efisiensi waktu dan tenaga, yaitu mengurangi beban kerja staff yang harus melakukan pencatatan keuangan secara manual sehingga jika menggunakan sistem pos, para staf dapat fokus pada layanan pelanggan.

Meskipun banyaknya manfaat yang diberikan oleh sistem POS terhadap UMKM tidak dipungkiri bahwa ditemukannya satu masalah yaitu ketergantungan terhadap koneksi internet, ketergantungan ini mengharuskan pengguna sistem POS untuk selalu online setiap saat ingin menggunakan sistem, jika tidak maka sistem tidak akan dapat diakses, hal ini menjadi kesimpulan dalam jurnal tersebut bahwa sistem POS ini harus dapat beroperasi secara offline juga demi semakin mempermudah penggunaannya.

<h4><b>Pengembangan Aplikasi Point of Sale (POS) berbasis Mobile untuk Membantu UMKM</b></h4>
Jurnal ini membahas mengenai pengembangan aplikasi POS berbassis mobile yang diperuntukan untuk membantu UMKM (khususnya kafe), pada prosesnya Suhargo et al melakukan analisis user requirement  terlebih dahulu guna membantu untuk menemui apa saja yang dibutuhkan untuk membangun sebuah sistem POS yang akan digunakan untuk membantu UMKM.

Suhargo et al menemukan bahwa terdapat beberapa kebutuhan yang dibutuhkan oleh user agar sistem pos dapat dibangun, kebutuhan-kebutuhan tersebut yaitu:
1. Pemberlakuan Transaksi
2. Histori Transaksi
3. Manajemen Meja
4. Laporan Penjualan
5. Manajemen Produk
6. Manajemen banyak cabang
7. Fungsi GPS

Kebutuhan-kebutuhan yang sudah ditemukan tersebut yang menjadi dasar pembuatan sistem POS untuk kafe.Selain penemuan kebutuhan untuk merancang pembangunan sistem Suhargo et al juga merencanakan proses pengujian sistem dengan 2 cara, yaitu pengujian Black Box dan pengujian User Acceptance Test (UAT). Pengujian blackbox atau blackbox testing dijalankan untuk memastikan setiap fungsi sudah berjalan sesuai dengan skenario use case, sementara pengujian UAT dijalankan dengan melibatkan responden dari pelaku umkm kafe untuk menilai aspek functionality, usability, dan effisiency, sehingga dapat dipastikan aplikasi yang dikembangkan layak digunakan sebagai solusi bagi UMKM kafe.

Perancangan sistem POS berbasis mobile ini menghasilkan beberapa fitur utama seperti:
1. Autentikasi pengguna
2. Tampilan informasi outlet, transaksi, menu, meja, dan laporan penjualan
3. Transaksi dan riwayat transaksi
4. Manajemen menu dan meja
5. Fitur GPS, yang digunakan untuk menampilkan lokasi outlet yang terdaftar.

Selanjutnya Suhargo et al menjabarkan hasil testing menggunakan 2 metode tadi, hasil-hasil tersebut seperti fungsi aplikasi yang berjalan dengan baik sesuai dengan perannya masing-masing pada use case, dan pengujian UAT terhadap 50 responden yang menghasilkan nilai rata-rata sebanyak 86%.  Hal ini menunjukan pengguna sangat setuju aplikasi POS diterapkan pada lingkungan kerja mereka sehingga dapat mengefisiensi kinerja dan juga memudahkan untuk para pelanggan dalam menemukan outlet kafe dan juga informasi terkait seperti menu dan lokasi.

<h2 align="center">Pertanyaan</h2>
<h4>List Pertanyaan Wawancara</h4>
<ul>
<ol>
   1.Apa nama usaha bapak/ibu?
</ol>
<ol>
  2.Apa bentuk usaha yang bapak/ibu lakukan?
</ol>
<ol>
  2.Apa bentuk usaha yang bapak/ibu lakukan?
</ol>
<ol>
 3. Apakah usaha ini milik sendiri/franchise/reseller?
</ol>
<ol>
  4. Apa saja langkah langkah kegiatan usaha yang dilakukan? 
</ol>
<ol>
  5. Apakah ada kendala tertentu dalam melakukan usaha ini? (Seperti salah pencatatan keuangan, kesulitan mencatat stok barang, dll)
</ol>
<ol>
  6. Apakah dalam usaha ini sudah mempunyai sistem?
</ol>
<ol>
  7. Dalam melakukan kegiatan usaha apakah perlu sistem tertentu? (Seperti sistem manajemen keuangan/sistem pelaporan)
</ol>
<ol>
  8. Apakah ada pembagian struktural kerja, kalau ada jobdesknya apa saja
</ol>
<ol>
  9. Apakah pendataan sekarang masih secara manual? kalau iya, menggunakan apa? apakah excel? atau pembukuan?
</ol>
<ol>
  10. Apakah mempunyai toko online?
</ol>
</ul>
<h2 align="center">Dokumentasi</h2>
Berikut adalah Link Dokumentasi kami pada wawancara dengan SushiMood pada hari Rabu, 29 April 2026 Pukul 13.10 WIB :
<a href="https://youtu.be/AKdoKPQM6m4?si=DiMCfM6n75lhusBY">
WAWANCARA TERHADAP SUSHI MOOD UNTUK ANALISIS KEBUTUHAN USER</a>
<p>
  <h3>NOTULENSI WAWANCARA</h3>
  <p><strong>Narasumber:</strong> Kaesar</p>
    <h4>Profil Usaha</h4>
    <ul>
      <li><strong>Nama Usaha:</strong> Sushi Mood</li>
      <li><strong>Kepemilikan:</strong> Usaha milik sendiri</li>
      <li><strong>Bidang:</strong> Food and Beverage (F&B)</li>
    </ul>
    <h4>Kegiatan Operasional</h4>
    <ul>
      <li>Menyiapkan bahan baku</li>
      <li>Menjaga kebersihan usaha</li>
      <li>Melayani pelanggan</li>
    </ul>
    <h4>Sistem yang Digunakan</h4>
    <p>Belum menggunakan sistem khusus. Kemungkinan membutuhkan sistem apabila usaha berkembang lebih besar.</p>
    <h4>Struktur Organisasi</h4>
    <ul>
      <li>Helper</li>
      <li>Cook</li>
    </ul>
    <h4>Pencatatan</h4>
    <p>Pencatatan saat ini masih menggunakan Microsoft Excel.</p>
    <h4>Jobdesk Karyawan</h4>
      <p>Tugas utama Cooker memasak dan Helper membantu saat melayani. Setiap karyawan saling berkoordinasi dalam melayani pelanggan dan menjalankan operasional usaha.</p>
</p>
<h2 align="center">Alur bisnis</h2>

## Informasi Umum Usaha

| Aspek | Keterangan |
|-------|-------------|
| Nama Usaha | SushiMood |
| Narasumber | Caesar |
| Jenis Usaha | Food & Beverage (Sushi) |
| Status Kepemilikan | Milik sendiri |
| Sistem Saat Ini | Manual Tanppa Sistem Digital |
| Pencatatan | Menggunakan Microsoft Excel |
| Struktur Karyawan | Helper dan Cook |
---

## Alur Bisnis Yang Berjalan Saat Ini

Berikut adalah alur bisnis harian di SushiMood:

1. **Persiapan Bahan Baku**  
   Cook dan helper bersama-sama menyiapkan nasi, nori, ikan, ayam, sayuran, dan bahan lainnya.
2. **Pembersihan Area Usaha**  
   Helper membersihkan area dapur, meja layanan, dan peralatan masak.
3. **Proses Pemesanan**  
   Pelanggan datang langsung ke tempat atau memesan via Gojek, Grab, atau Shopee Food.
4. **Penerimaan Pesanan**  
   Helper atau cook menerima pesanan secara langsung dan berkoordinasi secara lisan.
5. **Proses Memasak Sushi**  
   Cook mulai membuat sushi sesuai dengan pesanan dari pelanggan.
6. **Penyajian atau Pengemasan**  
   Helper menyajikan sushi untuk dine-in atau dikemas untuk takeaway.
7. **Pembayaran**  
   Helper atau cook menerima pembayaran secara tunai atau scan Qris.
8. **Pencatatan ke Excel**  
   Salah satu karyawan mencatat transaksi penjualan ke dalam file Excel setelah jam operasional selesai.
9. **Koordinasi Internal**  
   Helper dan cook saling berkomunikasi langsung secara lisan dalam melayani pelanggan. Tidak ada jobdesk yang kaku.
---

## Kendala Operasional Saat Ini

| No | Kendala | Dampak |
|----|---------|--------|
| 1 | Pencatatan masih manual menggunakan Excel | Data mudah salah atau hilang |
| 2 | Tidak ada sistem antrean | Dapur kewalahan saat ramai |
| 3 | Tidak ada notifikasi status pesanan | Pelanggan menunggu tanpa kepastian |
| 4 | Stok bahan baku tidak terpantau real-time | Bisa kehabisan bahan saat jam sibuk |
| 5 | Laporan penjualan harus dibuat manual | Sulit mengetahui performa usaha secara cepat |
---

## Rencana Kebutuhan Sistem Kedepan (To-Be)

> Berdasarkan pernyataan Caesar: *"Kemungkinan butuh sistem apabila sudah lebih besar usahanya"*

Berikut adalah sistem yang sebaiknya dimiliki SushiMood di masa mendatang:
1. **Sistem Kasir Digital**  
   Mencatat pesanan dan pembayaran secara otomatis.
2. **Sistem Manajemen Stok**  
   Memantau jumlah bahan baku secara real-time.
3. **Peringatan Stok Menipis**  
   Notifikasi otomatis jika stok bahan habis atau mendekati habis.
4. **Sistem Antrean Pesanan (FIFO)**  
   Mengatur urutan pesanan di dapur agar tidak ada yang terlewat.
5. **Notifikasi Pesanan Selesai**  
   Memberi tahu kasir dan pelanggan ketika pesanan sudah siap.
6. **Laporan Penjualan Otomatis**  
   Menampilkan pendapatan harian, menu terlaris, dan jumlah transaksi.
---

## Kesimpulan

Saat ini SushiMood masih berjalan secara manual dengan koordinasi lisan antara helper dan cook. Pencatatan keuangan dan penjualan masih menggunakan Excel.
Untuk mengembangkan usaha ke level yang lebih besar, SushiMood sangat membutuhkan sistem digital yang terintegrasi, mulai dari kasir, stok barang, antrean dapur, hingga laporan penjualan otomatis.

**Dokumen ini disusun berdasarkan hasil wawancara langsung dengan Caesar, selaku pemilik gerai SushiMood.**

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
