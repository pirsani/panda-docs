# Panda

Aplikasi Panda (Pengelolaan Administrasi Perbendaharaan) adalah alat bantu pencatatan untuk menyederhanakan beragamnya aplikasi yang digunakan untuk pencatatan administrasi perbendaharaan.

## 1. **Pendahuluan**

- **1.1. Tentang Aplikasi Panda**
  - Deskripsi singkat aplikasi
  - Tujuan pengembangan
- **1.2. Fitur Utama**
  - **1.2.1. Dashboard**
    - Dashboard
    - Workbench
    - Pending Matters
  - **1.2.2 Proses**
    - Pencatatan Setup Kegiatan
    - Pengajuan
      - Pengajuan cetak SPD & rampungan
      - Pengajuan Honorarium Narasumber
        - Penambahan jadwal kelas narasumber
      - Pengajuan Uang Harian Dalam Negeri
      - Pengajuan Uang Harian Luar Negeri
    - Verifikasi Pengajuan
      - Verifikasi pengajuan cetak SPD & rampungan
      - Verifikasi Pengajuan Honorarium Narasumber untuk setiap jadwal kelas narasumber
      - Verifikasi Pengajuan Uang Harian Luar Negeri
      - Verifikasi Pengajuan Uang Harian Dalam Negeri
    - Daftar Nominatif dan Pengajuan Pembayaran
      - Daftar Nominatif Pengajuan Pembayaran Honorarium Narasumber untuk setiap jadwal kelas narasumber
      - Daftar Nominatif Pengajuan Pembayaran Uang Harian Luar Negeri
      - Daftar Nominatif Pengajuan Pembayaran Uang Harian Dalam Negeri
    - Pembayaran
      - Pembayaran Honorarium Narasumber untuk setiap jadwal kelas narasumber
      - Pembayaran Uang Harian Luar Negeri
      - Pembayaran Uang Harian Dalam Negeri
  - **1.3 Fitur Pendukung**
    - **1.3.1 Tabel Referensi**
      - Narasumber
      - Materi
      - Kelas
      - SBM Honorarium
      - SBM Uang Harian Luar Negeri
      - SBM Uang Representasi
      - SBM Transpor
      - Pengelola Keuangan
      - Satker Anggaran
      - Unit Kerja
      - Negara
      - Propinsi
    - **1.3.2. Pengaturan Pengguna**
      - Role
      - Pengguna
- **1.3. Manfaat Penggunaan**
  - Menyederhanakan alat bantu pencatatan administrasi perbendaharaan
  - Efisiensi waktu dan sumber daya
  - Akurasi dalam pencatatan
  - Transparansi antar unit organisasi

## 2. **Prasyarat Sistem**

- **2.1. Hardware**
  - Spesifikasi minimum server
- **2.2. Software**
  - Sistem operasi yang didukung
  - Dependensi dan pustaka yang diperlukan
- **2.3. Koneksi Internet**
  - Kebutuhan jaringan untuk akses dan sinkronisasi

Baca [Prasyarat Sistem](technical/index.md#prasyarat-sistem)

## 3. **Panduan Instalasi**

- **3.1. Persiapan Lingkungan Server**
  - Instalasi sistem operasi
  - Konfigurasi jaringan
- **3.2. Instalasi Aplikasi Panda**
  - Langkah-langkah instalasi
  - Konfigurasi awal
- **3.3. Instalasi Dependensi**
  - Database (misalnya PostgreSQL)
  - Web server (misalnya NGINX)
  - Manajer proses (misalnya PM2 atau lainnya)
- **3.4. Konfigurasi Aplikasi**
  - Pengaturan file `.env`
  - Konfigurasi database
  - Pengaturan keamanan
  
Baca [Panduan Instalasi](technical/deploy.md#panduan-instalasi)

## 4. **Panduan Pengguna**

- **4.1. Login**  
  - [Proses login](manual-pengguna/login/login.md)
- **4.2. Dashboard Utama**
  - Navigasi dashboard
  - Tampilan overview keuangan
- **4.3. Modul-modul Aplikasi**
  - **4.3.1. Setup Kegiatan**
    - [Setup Kegiatan](manual-pengguna/setup-kegiatan/setup-kegiatan.md)
  - **4.3.2. Pengelolaan Pengeluaran**
    - Mencatat pengeluaran
    - Kategori pengeluaran
  - **4.3.3. Pengelolaan Penerimaan**
    - Mencatat penerimaan
    - Sumber penerimaan
  - **4.3.4. Laporan Keuangan**
    - Membuat laporan
    - Export laporan (PDF, Excel)
- **4.4. Pengaturan Akun**
  - Mengubah profil
  - Pengaturan keamanan

## 5. **Panduan Admin**

- **5.1. Manajemen Pengguna**
  - Menambah pengguna baru
  - Menyunting pengguna
  - Menghapus pengguna
  - Mengatur peran dan izin
- **5.2. Pengaturan Sistem**
  - Konfigurasi umum aplikasi
  - Integrasi dengan aplikasi lain
- **5.3. Backup dan Restore**
  - Prosedur backup data
  - Prosedur restore data

## 6. **API dan Integrasi**

- **6.1. Dokumentasi API**
  - Endpoints yang tersedia
  - Contoh penggunaan API
- **6.2. Integrasi dengan Aplikasi Lain**
  - Cara menghubungkan dengan sistem ERP
  - Sinkronisasi data

## 7. **Troubleshooting**

- **7.1. Masalah Umum**
  - Kesalahan login
  - Kesalahan koneksi database
- **7.2. Solusi dan Cara Mengatasi**
  - Langkah-langkah pemecahan masalah
  - Kontak dukungan teknis

## 8. **FAQ (Frequently Asked Questions)**

- Pertanyaan umum dan jawabannya
- Tips penggunaan efektif

## 9. **Lampiran**

- **9.1. Glossary**
  - Istilah-istilah penting
- **9.2. Referensi**
  - Link ke sumber tambahan
  - Dokumentasi teknis terkait

## 10. **Kontak dan Dukungan**

- **10.1. Informasi Kontak**
  - Email dukungan
  - Nomor telepon
- **10.2. Sumber Daya Dukungan**
  - Forum pengguna
  - Tutorial video

---

**Catatan:** Outline ini dapat disesuaikan lebih lanjut sesuai dengan kebutuhan spesifik aplikasi Panda dan umpan balik dari pengguna. Pastikan setiap bagian dokumentasi diisi dengan informasi yang jelas dan terperinci untuk memudahkan pengguna dalam memahami dan menggunakan aplikasi dengan optimal.


- [Gambaran Umum](overview.md)
- [Memulai](setup.md)
- [Fitur](features.md)
- [Petunjuk Penggunaan](manual/index.md)
- [Dokumentasi Teknis](technical/index.md)
- [Contribution Guidelines](guides/contributing.md)
