# Sistem Pengelolaan Stok Produk (Inventory Management)

Aplikasi berbasis web untuk mengelola stok barang secara real-time. Proyek ini dibangun untuk memastikan konsistensi data dan efisiensi dalam operasional inventaris barang.

## 🚀 Fitur Utama
**Autentikasi User**: Sistem login yang aman untuk mengelola akses pengguna.
**Manajemen Produk (CRUD)**: Menambah, melihat, mengubah, dan menghapus data produk dengan mudah.
**Monitoring Stok**: Pantauan stok barang secara real-time untuk menghindari kekurangan atau kelebihan muatan.
**Database Relasional**: Menggunakan MySQL dengan perancangan tabel yang saling terhubung untuk integritas data yang optimal.

## 🛠️ Tech Stack
**Framework**: PHP Laravel (MVC Architecture).
**Database**: MySQL.
**Frontend**: Tailwind CSS / Bootstrap.
**Konsep**: RESTful API & MVC Design Pattern.

## 💻 Cara Instalasi (Lokal)
1. Persiapan:
   Pastikan sudah menginstal:
   * PHP >= 8.x
   * Composer
   * Web Server (Laragon / XAMPP)

2. Clone repository ini:

   git clone https://github.com/albert727/pengelolaan_stok.git

4. Instalasi Dependency
   jalankan composer untuk mengunduh semua library Laravel yang dibutuhkan:
   composer install

5. Konfigurasi Env
   Salin file .env.example menjadi .env:
   cp .env.example .env

6. Generate Application Key & Migrasi:
   php artisan key:generate
   php artisan migrate

7. Jalankan aplikasi:
   php artisan serve
