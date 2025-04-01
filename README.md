# Aplikasi Kasir Sederhana 🛒

Aplikasi desktop untuk mengelola transaksi penjualan, mencetak struk, dan mencatat riwayat transaksi.

## 📋 Fitur Utama
- **Manajemen Produk**  
  Tambah, edit, hapus produk (kode, nama, harga, stok).
- **Transaksi Penjualan**  
  Input item belanja, hitung total, diskon, dan kembalian.
- **Cetak Struk**  
  Generate struk dalam format PDF atau cetak langsung.
- **Riwayat Transaksi**  
  Simpan dan tampilkan riwayat transaksi dengan filter tanggal.
- **Laporan Harian**  
  Tampilkan total pendapatan harian dan ekspor ke Excel.
- **Pencarian Produk**  
  Cari produk berdasarkan nama/kode.
- **Autentikasi (Opsional)**  
  Login kasir dengan username dan password.

## 🛠 Teknologi
- **Bahasa Pemrograman**:  
  ![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white)  
  *(Alternatif: Java Swing)*
- **Database**:  
  ![SQLite](https://img.shields.io/badge/SQLite-07405E?logo=sqlite&logoColor=white)  
  *(Alternatif: MySQL untuk skala besar)*
- **Library**:
  - `iTextSharp` - Cetak struk PDF
  - `ClosedXML` - Ekspor data ke Excel
  - `Dapper` (Opsional) - ORM untuk akses database
