# SewaIn

Website penyewaan barang online dengan antarmuka responsif berbahasa Indonesia.

## Menjalankan

Buka `index.html` di browser, atau jalankan server statis dari folder ini, misalnya:

```sh
python -m http.server 8000
```

Lalu kunjungi `http://localhost:8000`.

## Cakupan demo

- Beranda, kategori, katalog dengan pencarian dan filter, kartu produk, serta detail barang.
- Alur checkout dengan input tanggal, pilihan antar/ambil, ringkasan biaya, dan tanggal tampil dalam format `dd-mm-yyyy`.
- Tampilan QRIS demo, riwayat pesanan, form ulasan dan KTP, panel admin/mitra, serta ekspor laporan CSV yang dapat dibuka di Excel atau spreadsheet.
- Login dan pendaftaran menyediakan tombol Google sebagai titik integrasi.

Data saat ini bersifat contoh dan interaksi berjalan di sisi browser. Produksi memerlukan backend untuk akun/OAuth Google, penyimpanan dan pemeriksaan KTP, stok dan persetujuan pesanan, serta integrasi QRIS dari penyedia pembayaran. Kode QR yang tampil adalah visual demo, bukan instruksi pembayaran aktif.
