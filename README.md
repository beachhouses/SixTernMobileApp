<div align="center">

# SIXTERN: Student Internship Experience & Evaluation App

*Platform Manajemen, Pemantauan, dan Evaluasi Magang Multi-Role Terintegrasi*

[![Status](https://img.shields.io/badge/Status-In%20Development-blue?style=for-the-badge&logo=git)](https://github.com/)
[![Mobile Platform](https://img.shields.io/badge/Platform-Flutter%20%2F%20Android%20%2F%20iOS-orange?style=for-the-badge&logo=flutter)](https://github.com/)
[![Backend](https://img.shields.io/badge/Backend-Node.js%20%2F%20Laravel-green?style=for-the-badge&logo=nodedotjs)](https://github.com/)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)

</div>

---

## 1. Tentang Aplikasi (Overview)

**SixTern** adalah solusi digital komprehensif yang dirancang untuk mendigitalisasi dan menyederhanakan ekosistem program magang. Aplikasi ini **bukan sekadar platform pendaftaran**, melainkan pusat pemantauan (*monitoring hub*) end-to-end yang menjembatani komunikasi antara **Mahasiswa (Peserta Magang), Pembimbing Lapangan (Perusahaan),** dan **Universitas/Prodi (Kampus)**.

Dengan pendekatan berbasis *mobile*, seluruh aktivitas harian, pelacakan kehadiran, persetujuan logbook, hingga rekapitulasi penilaian akhir dapat diakses secara transparan, *real-time*, dan akurat dari mana saja.

---

## 2. Rencana Fitur & Kapabilitas Sistem (Roadmap Features)

### Mobile Capability (Client-Side)
*   **GPS Attendance:** Sistem presensi harian berbasis geolokasi untuk memvalidasi titik kehadiran peserta magang di instansi/perusahaan.
*   **Daily Logbook & Activity:** Fitur pencatatan laporan kegiatan harian yang terhubung langsung dengan sistem antrean persetujuan.
*   **Smart Notification & Reminder:** Pengingat otomatis bagi peserta untuk menghindari keterlambatan pengisian logbook.
*   **Secure File Upload:** Kemudahan mengunggah dokumen pendukung, file tugas, atau laporan akhir secara langsung.

### Dashboard & System Output
*   **Progress Chart:** Visualisasi grafik perkembangan performa, tingkat kerajinan, dan penyelesaian tugas peserta.
*   **Approved Logbook Archive:** Rekapitulasi arsip logbook yang telah divalidasi dan disetujui secara sah.
*   **System Activity Audit:** Pencatatan riwayat aktivitas sistem untuk menjaga transparansi nilai dan kehadiran.

---

## 3. Arsitektur Multi-Role & Hak Akses

Sistem keamanan dan alur kerja aplikasi **SixTern** dibagi menjadi 3 peran utama (*multi-role*) agar koordinasi antar-instansi berjalan mulus:

| Role Pengguna | Tanggung Jawab Utama | Fitur / Hak Akses |
| :--- | :--- | :--- |
| ** Mahasiswa** <br>*(Peserta Magang)* | Menjalankan kewajiban harian dan melaporkan progres magang secara mandiri. | • Absensi GPS harian<br>• Input & Edit Logbook<br>• Upload dokumen/tugas<br>• Monitoring grafik progres pribadi |
| ** Pembimbing Lapangan** <br>*(Mentor Perusahaan)* | Mengawasi kinerja operasional harian peserta magang di tempat kerja. | • Approval / Revisi Logbook<br>• Validasi kehadiran GPS<br>• Input catatan evaluasi kerja<br>• Penilaian performa harian/mingguan |
| ** Universitas / Prodi** <br>*(Dosen / Admin Kampus)* | Memantau kredibilitas akademik dan status kelulusan program magang mahasiswa. | • Monitoring rekapitulasi nasional/prodi<br>• Supervisi progress chart mahasiswa<br>• Validasi dan sinkronisasi nilai akhir akademik |

---

## 4. Tech Stack (Teknologi yang Digunakan)

*   **Frontend Mobile:** Flutter (Dart) / React Native
*   **Backend API:** Node.js (Express) atau Laravel (PHP)
*   **Database:** PostgreSQL / MySQL dengan struktur relasional multi-tenant
*   **Geolocation:** Google Maps API / OpenStreetMap SDK

---

## 5. Cara Menjalankan Project (Installation)

Jika Anda ingin menjalankan atau berkontribusi pada pengembangan project ini, ikuti langkah-langkah di bawah ini:

```bash
# 1. Clone repository ini
git clone [https://github.com/username-kamu/SixTern.git](https://github.com/username-kamu/SixTern.git)

# 2. Masuk ke direktori project
cd SixTern

# 3. Install dependencies (contoh untuk Flutter / Node.js)
flutter pub get   # atau npm install

# 4. Jalankan aplikasi
flutter run       # atau npm start
