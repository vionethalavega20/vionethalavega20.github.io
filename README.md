

# Laporan Keuangan Harian

Aplikasi web sederhana berbasis HTML, CSS (Bootstrap), dan JavaScript yang dirancang untuk mencatat serta mengelola keuangan harian secara manual.

## Deskripsi Proyek

Aplikasi ini memudahkan pengguna dalam mencatat transaksi harian, baik pemasukan maupun pengeluaran, menghitung saldo akhir secara otomatis, serta mencetak laporan keuangan dalam format PDF. Aplikasi ini sangat cocok digunakan untuk keperluan pribadi maupun usaha kecil.

## Fitur Utama

- Input data transaksi (tanggal, keterangan, tipe, jumlah)  
- Perhitungan otomatis total pemasukan, pengeluaran, dan saldo akhir  
- Tombol untuk menghapus semua data atau hanya baris terakhir  
- Ekspor laporan keuangan ke format PDF menggunakan jsPDF dan AutoTable  

## Instalasi

Untuk menjalankan proyek ini secara lokal, ikuti langkah-langkah berikut:

1. **Clone repositori ini ke komputer lokal:**
git clone https://github.com/vionethalavega20/vionethalavega20.github.io.git


2. **Masuk ke direktori proyek:**
cd vionethalavega20.github.io


3. **Buka file `index.html` di browser favorit kamu:**

- Klik dua kali pada file `index.html`, atau  
- Jalankan dengan Live Server jika menggunakan Visual Studio Code

Tidak diperlukan instalasi tambahan karena ini adalah proyek berbasis **HTML**, **CSS**, dan **JavaScript** yang berjalan langsung di browser.

> Pastikan kamu sudah menginstal [Visual Studio Code](https://code.visualstudio.com/) jika ingin mengedit proyek ini dengan mudah.

## Cara Penggunaan

1. Buka file `index.html` di browser.  
2. Isi formulir dengan data transaksi keuangan.  
3. Klik tombol **Tambah Transaksi** untuk menambahkan ke tabel.  
4. Gunakan tombol berikut sesuai kebutuhan:
   - **Hapus Semua Data** untuk menghapus seluruh entri  
   - **Cetak PDF** untuk mengekspor laporan  
   - **Hapus Baris Terakhir** untuk menghapus transaksi terakhir  

## Struktur File

- `index.html` — Berisi struktur halaman, logika JavaScript, serta integrasi dengan Bootstrap dan jsPDF.  
- Menggunakan CDN eksternal untuk:
  - Bootstrap 5 (antarmuka pengguna)  
  - jsPDF dan jsPDF-AutoTable (fitur ekspor PDF)  

## Screenshots

Berikut adalah tampilan antarmuka aplikasi:

### Form Input dan Tabel Transaksi

![Screenshot Form Input dan Tabel Transaksi](screenshots/form1.png) 


### Hasil Ekspor PDF
![Screenshot PDF Ekspor](screenshots/hasilpdf.png)


## Kontribusi

Kontribusi terbuka untuk siapa saja. Silakan buat *pull request* atau buka *issue* apabila memiliki saran atau menemukan bug.

## Lisensi

Proyek ini bersifat open-source. Bebas digunakan, dimodifikasi, dan dibagikan kembali sesuai kebutuhan.

## Kontak

Untuk pertanyaan atau kerja sama, silakan hubungi:  
**Nama**: Vionetha Lavega  
**Email**: vionetha2085@gmail.com

## Riwayat Versi

- **v1.0.0** (07 April 2025): Rilis awal dengan fitur dasar pencatatan transaksi dan ekspor PDF.
