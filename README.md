# Sistem Manajemen Inventaris Toko Online

Repositori ini berisi berkas kode sumber (*source code*) untuk Aplikasi Sistem Manajemen Inventaris Toko Online yang dibangun menggunakan arsitektur *decoupled* REST API Laravel (Backend) dan Vue.js (Frontend).

## Isi Repositori
* `toko-online.zip` : Berkas arsip utama yang memuat seluruh komponen *source code* aplikasi (Controller, Route, Migrasi Database, dan Komponen Frontend).

## Panduan Penggunaan / Ekstraksi Project
Untuk menjalankan project ini di lingkungan lokal (*local development*), silakan ikuti instruksi berikut:

1. Unduh (*download*) berkas `toko-online.zip` yang tersedia di dalam repositori ini.
2. Ekstrak berkas ZIP tersebut ke dalam direktori kerja komputer Anda.
3. Buka terminal atau *command prompt* pada folder hasil ekstraksi, lalu jalankan perintah berikut secara berurutan untuk memulihkan seluruh pustaka (*library*) sistem:

### Backend (Laravel)
```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
