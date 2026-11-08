# Rancang Bangun Sistem Informasi Helpdesk dan Penugasan Teknisi Berbasis Web

Aplikasi web helpdesk dan manajemen penugasan lapangan yang dirancang khusus untuk mengoptimalkan layanan pelanggan serta mempermudah koordinasi tugas teknisi di **PT. Gerak Maju Abadi**. 

Proyek ini dikembangkan sebagai bagian dari Laporan Magang / Praktik Kerja Lapangan (PKL) di bidang Teknologi Informasi.

---

## Fitur Utama
* **Portal Publik (Pelanggan):** Memungkinkan pelanggan mengirimkan laporan kendala atau keluhan mandiri secara *real-time* lengkap dengan unggah foto kondisi awal dan fitur "Salin Nomor" tiket untuk konfirmasi via WhatsApp.
* **Portal Login Karyawan:** Sistem autentikasi berbasis database cloud untuk membedakan hak akses (*role-based access control*) secara otomatis.
* **Dashboard Admin:** Pusat kendali untuk memonitor seluruh tiket masuk, rekap tanggal request dan tanggal selesai, melihat foto dokumentasi awal & bukti, serta manajemen data karyawan (*CRUD*).
* **Dashboard Kepala Teknisi:** Fitur *Quick Assign* untuk mendistribusikan tugas kepada anggota teknisi lapangan.
* **Portal Anggota Teknisi:** Antarmuka khusus *mobile-friendly* bagi teknisi untuk menerima tugas, melihat detail alamat dengan fitur **"Buka Peta" (Google Maps)**, mengubah status perjalanan, hingga mengunggah foto bukti penyelesaian dan catatan *feedback*.

---

## Tech Stack & Arsitektur
* **Frontend:** HTML5, Tailwind CSS (via CDN), Lucide Icons, Vanilla JavaScript.
* **Backend & Database:** Supabase (Cloud PostgreSQL Database & Storage Buckets).
* **Deployment:** GitHub Pages.

---

## Status Proyek
* **Status:** *Production / Live*
* **Instansi:** PT. Gerak Maju Abadi
