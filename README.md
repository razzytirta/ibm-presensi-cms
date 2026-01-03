<p align="center">
  <img src="https://dummyimage.com/400x120/0b3a82/ffffff&text=IBM+PRESENSI+CMS" width="400" alt="IBM Presensi CMS Logo">
</p>

<p align="center">
  <strong>IBM Presensi CMS</strong><br>
  Sistem Manajemen Presensi Karyawan PT Intiboga Mandiri
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Laravel-red" alt="Laravel">
  <img src="https://img.shields.io/badge/Frontend-Flutter-blue" alt="Flutter">
  <img src="https://img.shields.io/badge/Status-Production%20Ready-green" alt="Status">
  <img src="https://img.shields.io/badge/License-Proprietary-orange" alt="License">
</p>

---

## 📌 Tentang IBM Presensi CMS

**IBM Presensi CMS** adalah aplikasi **Content Management System (CMS)** untuk mengelola **presensi karyawan** di lingkungan **PT Intiboga Mandiri**. Sistem ini berfungsi sebagai **backend & admin panel** yang terintegrasi dengan aplikasi mobile berbasis **Flutter**.

CMS ini dirancang untuk kebutuhan **enterprise**, aman, scalable, dan mudah dikembangkan.

---

## 🚀 Fitur Utama

- 👤 Manajemen Data Karyawan
- 🕒 Presensi Masuk & Pulang
- 📍 Validasi Lokasi (GPS / Geofencing)
- 📅 Manajemen Shift & Jadwal Kerja
- ⏱️ Lembur & Hari Libur Nasional
- 📊 Rekap & Laporan Presensi
- 🔐 Role & Hak Akses (Admin, HR, Supervisor)
- 🔗 REST API untuk Aplikasi Flutter

---

## 🧱 Teknologi yang Digunakan

### Backend
- **Laravel** (REST API & CMS)
- **MySQL / PostgreSQL** (Database)
- **Laravel Sanctum / JWT** (Authentication)

### Frontend
- **Flutter** (Mobile App Karyawan)

---

## 🗂️ Struktur Modul CMS

- Dashboard
- Karyawan
- Presensi
- Shift Kerja
- Lembur
- Hari Libur
- Laporan
- Manajemen User & Role
- Pengaturan Sistem

---

## ⚙️ Instalasi Singkat (Development)

```bash
# Clone repository
git clone https://github.com/intiboga/ibm-presensi-cms.git

# Masuk ke folder project
cd ibm-presensi-cms

# Install dependency
composer install

# Copy environment
cp .env.example .env

# Generate key
php artisan key:generate

# Migrasi database
php artisan migrate --seed

# Jalankan server
php artisan serve
```

---

## 🔐 Keamanan

- Autentikasi berbasis token
- Role-based access control (RBAC)
- Validasi data & logging aktivitas admin

---

## 📱 Integrasi Mobile (Flutter)

CMS ini menyediakan **REST API** yang digunakan oleh aplikasi mobile Flutter untuk:
- Login karyawan
- Presensi real-time
- Riwayat presensi
- Sinkronisasi jadwal & shift

---

## 🏢 Hak Kepemilikan

Aplikasi ini dikembangkan khusus untuk:

**PT Intiboga Mandiri**  
Semua hak cipta dan penggunaan bersifat **internal & proprietary**.

---

## 📄 Lisensi

**Proprietary License**  
Tidak diperkenankan menyalin, mendistribusikan, atau menggunakan sebagian maupun seluruh sistem tanpa izin resmi dari PT Intiboga Mandiri.

---

## ✨ Nama Internal Proyek

- **IBM Presensi CMS** (Nama Aplikasi)
- **ibm-attendance-admin** (Nama Repository)
- **ibm_attendance_db** (Nama Database)

---

> _Built with Laravel ❤️ for Enterprise Attendance Management_

