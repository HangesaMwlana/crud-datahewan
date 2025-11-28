# crud-datahewan / 
========================================
📌 CRUD DATA HEWAN - PADALARANG PET HOUSE
========================================

👤 Nama Siswa:
Hangesa Maulana Saputra

📍 Deskripsi Singkat:
Aplikasi ini dibuat untuk membantu Padalarang Pet House dalam mencatat data hewan yang masuk. 
Aplikasi menggunakan fitur CRUD (Create, Read, Update, Delete) untuk mengelola data hewan seperti nama, jenis, umur, dan keterangan.

========================================
🧪 Teknologi yang Digunakan
========================================
• Bahasa Pemrograman : PHP
• Database           : MySQL
• Framework          : Tanpa Framework (Native PHP)
• CSS Framework      : Bootstrap 5 + Custom Styling

========================================
🗄 Struktur Database
========================================
Nama Database  : padalarang_petshop
Nama Tabel     : hewan

Struktur Kolom:
- id (INT, AUTO_INCREMENT, PRIMARY KEY)
- nama_hewan (VARCHAR)
- jenis_hewan (VARCHAR)
- umur (VARCHAR)
- keterangan (TEXT)

SQL Setup (jika dibutuhkan):

CREATE DATABASE padalarang_petshop;

USE padalarang_petshop;

CREATE TABLE hewan (
  id INT AUTO_INCREMENT PRIMARY KEY,
  nama_hewan VARCHAR(100),
  jenis_hewan VARCHAR(100),
  umur VARCHAR(50),
  keterangan TEXT
);

========================================
🔌 Cara Menjalankan Project
========================================

1️⃣ Pastikan XAMPP atau Laragon aktif  
   - Nyalakan Apache & MySQL

2️⃣ Letakkan folder project ke dalam:
   - Windows: `htdocs/`

3️⃣ Buat database di phpMyAdmin:
   - Nama database: padalarang_petshop

4️⃣ Import atau biarkan sistem membuat data kosong.

5️⃣ Jalankan aplikasi melalui browser:
   👉 http://localhost/padalarang-petshop/

========================================
⚙️ Konfigurasi Koneksi (koneksi.php)
========================================

$host = "localhost";
$user = "root";
$pass = "";
$db   = "padalarang_petshop";

$koneksi = mysqli_connect($host, $user, $pass, $db);

========================================

Wajib ada:

✔ Halaman daftar hewan (Read)
✔ Halaman tambah data (Create)
✔ Halaman edit data (Update)
✔ Notifikasi saat hapus/simpan data (Delete Confirmation)

========================================
📦 Isi Folder Project
========================================
|-- index.php
|-- tambah.php
|-- edit.php
|-- hapus.php
|-- koneksi.php
|-- style.css
|-- README.txt
|-- (opsional) database.sql

========================================
🚀 Status Project
========================================
✔ CRUD Berfungsi
✔ Database tersambung
✔ Tampilan Bootstrap modern
✔ Sudah berisi sample data dummy

========================================
📄 Lisensi
========================================
Project ini dibuat untuk kebutuhan tugas Bootcamp Coding
dan dapat dikembangkan lebih lanjut.

========================================
✨ Terima Kasih
========================================

