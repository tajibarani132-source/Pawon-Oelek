# Pawon Oelek — Buku Belanja Warung

Aplikasi web sederhana untuk mencatat belanja warung Pawon Oelek.

- Catat **waktu pembelian**, **jenis barang**, **harga per item**, dan **kuantiti**; setiap baris langsung menampilkan subtotal (harga × kuantiti).
- Isi **modal yang dimiliki**; aplikasi menghitung **sisa modal = modal − total belanja**.
- Unduh laporan sebagai **gambar (JPEG)** atau **Microsoft Excel (.xlsx)**. Di file Excel, subtotal, total, dan sisa modal memakai rumus.

Data tersimpan di browser masing-masing perangkat (localStorage) dan tidak dikirim ke server mana pun. Unduh Excel untuk arsip.

Seluruh aplikasi ada di satu file: `index.html`. Pustaka [ExcelJS](https://github.com/exceljs/exceljs) dimuat dari cdnjs saat membuat file Excel.
