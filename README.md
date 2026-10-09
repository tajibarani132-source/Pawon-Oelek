# Pawon Oelek — Buku Belanja & Penjualan Warung

Aplikasi web sederhana untuk pembukuan harian warung Pawon Oelek.

- **Belanja:** catat waktu pembelian, jenis barang, harga per item, dan kuantiti. Setiap baris langsung menampilkan subtotal (harga × kuantiti).
- **Penjualan:** catat waktu penjualan, menu atau barang yang terjual, harga jual, dan kuantiti.
- **Hasil hitung:**
  - Sisa modal = modal − total belanja
  - Laba kotor = total penjualan − total belanja
  - Uang kas akhir = sisa modal + total penjualan
- **Nota customer:** susun pesanan satu customer (menu, qty, harga), pilih pembayaran Tunai/QRIS/Transfer, hitung kembalian, lalu **cetak nota** (printer thermal 58 mm/80 mm atau printer biasa) atau **simpan sebagai gambar** untuk dikirim lewat WhatsApp. Nota bernomor otomatis (PO-YYMMDD-001), bisa dicetak ulang, dan langsung tercatat ke daftar penjualan.
- **Histori:** simpan penghitungan hari ini, lalu buka lagi, unduh ulang, hapus, atau unduh rekap semua histori ke Excel.
- **Unduh laporan** sebagai **gambar (JPEG)** atau **Microsoft Excel (.xlsx)**. Di file Excel, subtotal, total, sisa modal, laba kotor, dan uang kas akhir memakai rumus.

Semua data, termasuk histori, tersimpan di browser masing-masing perangkat (localStorage) dan tidak dikirim ke server mana pun. Unduh rekap Excel secara berkala untuk arsip.

Seluruh aplikasi ada di satu file: `index.html`. Pustaka [ExcelJS](https://github.com/exceljs/exceljs) dimuat dari cdnjs saat membuat file Excel.
