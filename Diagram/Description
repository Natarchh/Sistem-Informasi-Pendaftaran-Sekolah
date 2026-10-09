# SISTEM INFORMASI PENDAFTARAN SEKOLAH

---

# Sistem-Informasi-PPDB-Tugas-Kelompok-RPL

Sistem Informasi Pendaftaran Sekolah (Penerimaan Peserta Didik Baru) adalah platform digital terintegrasi berbasis web yang dirancang untuk menangani seluruh alur penerimaan siswa baru secara mandiri, mulai dari pembuatan akun hingga konfirmasi daftar ulang digital.

### Fitur Utama

* **Autentikasi Multi-Peran**: Akses khusus dan aman yang disesuaikan untuk peran Siswa, Panitia, dan Administrator dengan keamanan enkripsi tingkat lanjut.


* **Pendaftaran & Unggah Berkas Interaktif**: Fasilitas bagi calon siswa untuk mengisi biodata, memilih jalur masuk (Zonasi, Prestasi, Afirmasi, Tes), dan mengunggah dokumen administrasi (batas maksimal 2MB per file).


* **Verifikasi & Pemeringkatan Otomatis**: Dasbor *split-view* bagi panitia untuk memverifikasi dokumen secara langsung, dikombinasikan dengan mesin kalkulasi yang secara otomatis menghitung bobot nilai/jarak untuk meranking pendaftar sesuai kuota.


* **Portal Pengumuman & Daftar Ulang**: Publikasi status kelulusan secara tepat waktu yang dilengkapi fitur cetak Bukti Diterima (PDF) dan formulir konfirmasi daftar ulang *online*.



### Arsitektur & Teknologi

Sistem ini berdiri sendiri (*standalone system*) yang mengimplementasikan arsitektur *Model-View-Controller* (MVC) atau *Clean Architecture* untuk performa dan skalabilitas tinggi:

* **Frontend**: Antarmuka *User-Centered Design* (UCD) yang sepenuhnya responsif (kompatibel mulai dari layar *smartphone* minimum 360px hingga layar PC).


* **Backend**: Dieksekusi menggunakan *runtime* PHP 8.2+ atau Node.js yang berjalan di lingkungan Linux OS (Ubuntu Server 22.04 LTS) dengan Web Server Nginx / Apache.


* **Database**: Manajemen data terstruktur menggunakan MySQL 8.0 / PostgreSQL 15, dilengkapi perlindungan transaksi ACID (kemampuan *Fail-Safe / Rollback*) dan rutinitas *backup* otomatis harian.


* **Security**: Komunikasi data dijamin melalui enkripsi HTTPS (TLS 1.3), perlindungan *hashing* kata sandi (*bcrypt* atau *Argon2*), dan fitur *Auto Timeout* sesi.



### Dokumentasi Rekayasa Perangkat Lunak

Seluruh rancangan sistem mengacu pada standar rekayasa kebutuhan perangkat lunak IEEE Std 29148-2018 dan format Karl E. Wiegers.

* **SRS PPDB(5).pdf**
