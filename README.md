# Tokoku - Sistem Manajemen Terpadu & Kasir Toko

Aplikasi desktop Point of Sale (POS) berbasis GUI yang dirancang khusus untuk digitalisasi pencatatan transaksi, manajemen inventaris barang, dan pengelolaan loyalitas pelanggan (CRM Member) secara real-time. Proyek ini dikembangkan untuk memenuhi Tugas Akhir/Proyek Akhir mata kuliah Pemrograman Desktop, Program Studi Pendidikan Teknik Informatika dan Komputer (PTIK), Universitas Sebelas Maret (UNS).

##  Fitur Utama Aplikasi
* **Multi-Role Authentication**: Pembagian hak akses sistem yang ketat antara Admin (Manajemen Data & Laporan Keuangan) dan Kasir (Operasional Terminal Transaksi).
* **Manajemen Inventaris (CRUD Penuh)**: Pengelolaan data barang yang dinamis lengkap dengan pembatasan tipe data, status kontrol stok (Aman, Menipis, Habis), serta relasi database yang aman (Data Integrity).
* **Sistem Kasir (POS) & CRM**: Penghitungan transaksi otomatis yang terintegrasi dengan Pajak (PPN harian) serta pemotongan Diskon otomatis berdasarkan Tier Member (Bronze, Gold, Platinum).
* **Ekspor Struk PDF**: Fitur cetak bukti pembayaran atau struk belanja thermal secara otomatis langsung ke format file PDF yang rapi.
* **Dashboard Statistik**: Halaman utama Admin yang menyajikan visualisasi data komprehensif berupa grafik tren penjualan interaktif (Matplotlib).
* **Inisialisasi Database Otomatis**: Sistem akan otomatis mendeteksi dan membangun file database SQLite lokal saat pertama kali program dijalankan.

##  Spesifikasi Teknis & Dependensi
* **Bahasa Pemrograman**: Python 3.11+
* **Framework GUI**: PyQt6 (Python Bindings untuk Qt6)
* **Database Relasional**: SQLite3 (Memenuhi Aturan Normalisasi 2NF)
* **Library Eksternal**: ReportLab (Generator PDF) & Matplotlib (Visualisasi Grafik)
* **Distribution Wrapper**: PyInstaller (Kompilasi Executable) & Inno Setup (Setup Installer)
