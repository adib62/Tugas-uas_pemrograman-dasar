# Tugas-uas_pemrograman-dasar

KELOMPOK TERNIAT
ANGGOTA:
-Mhd Adib Sholahuddin (24.83.1065)
-Muhammad Febrian Nurrafi (24.83.1092)
-Yudhistira Baskoro Adi Admojo (24.83.1094)
-Adha Joy Eriyanto (24.83.1072)
-Fathan salaudin Avicena (24.83.1074)

#Penjelasan# 

1. SERVER : Disini kami menggunakan FastAPI untuk SERVER sebagai penyimpanan data "Mentah" Website Lelang Mobil Rally, seperti nama mobil,spesifikasi,daftar gambar, harga bid tertinggi, dan nama orang yang menawar atau ikut lelang mobil.
   
3. CLIENT : untuk web client kami menggunakan streamlit sebagai wadah untuk menampilkan antarmuka web dan sebagai jembatan antara user dan server

4. Proses Menawar (Bidding): Pada saat user memasukkan nama dan nominal tawaran, website akan mengecek apakah kita lebih banyak dari penawar sebelumnya. Jika iya, server akan memperbarui harga dan mencatat kita sebagai pemenang sementara.

5. Tampilan Real-Time: Perubahan harga dan riwayat penawaran langsung muncul di layar tanpa harus repot-repot menghitung manual, sehingga user merasa nyaman menggunakan website kami


#Fitur-Fitur Utama#

1.Interactive 360° Gallery: Untuk fitur ini digunakan untuk menampilkan gambar mobil dari berbagai sisi, dan sini menggunakan tombol navigasi ◀️ dan ▶️ untuk menampilkannya.

2.Progress Bar Galeri: Ada indikator di bawah foto yang menunjukkan posisi gambar yang kita lihat.

3.Live Bidding System: Fitur utama untuk memasukkan nama dan nominal tawaran secara interaktif.

4.Format Rupiah Otomatis (Anti-Bingung): Setiap angka yang kita masukkan akan otomatis diberi titik setiap 3 digit (contoh: 1.000.000). Fitur ini penting agar orang yang ingin ikut lelang tidak salah memasukkan nominalnya.

5.Log Riwayat Penawaran: Tabel di bagian bawah yang mencatat semua riwayat transaksi, termasuk jam berapa bid dilakukan, nama penawarnya, dan mobil yang dipilih.

6.Detail Spesifikasi: Kotak informasi yang bisa dibuka-tutup yang tujuannya  untuk melihat sejarah tahun rilis, mesin, hingga driver legendaris mobil tersebut.
