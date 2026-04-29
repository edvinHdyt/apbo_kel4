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

<h2 align="center">Alur bisnis</h2>

<h2 align="center">Use Case</h2>
