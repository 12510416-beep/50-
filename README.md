# DriveMoto — Website Dealer Motor

Website demo multi-halaman untuk proyek Sistem Informasi Dealer. Dibuat dengan HTML, CSS, dan JavaScript tanpa backend.

## Halaman

- `index.html` — Beranda, motor unggulan, alur layanan, dan promo.
- `katalog.html` — Katalog motor dengan pencarian, filter tipe, urutan harga/nama, informasi spesifikasi, pilihan warna, serta stok.
- `simulasi.html` — Kalkulator estimasi DP dan cicilan berdasarkan harga, persentase DP, tenor, dan bunga flat.
- `test-drive.html` — Formulir pengajuan jadwal test drive.
- `promo.html` — Daftar program promo yang dapat dikelola admin.
- `admin.html` — Login admin dan dashboard pengelolaan inventaris, booking, leads, serta promo.

## Login admin demo

- Username: `admin`
- Password: `drivemoto123`

Setelah login, buka menu **Inventaris motor** untuk menambah motor. Isi nama, merek, tipe, kapasitas mesin, harga, stok, warna, deskripsi, dan unggah foto. Foto akan dikompres otomatis agar lebih ringan. Data motor akan muncul di katalog dan pilihan motor pada simulasi/test drive. Admin juga dapat mengedit atau menghapus motor.

Pada halaman Admin tersedia menu untuk memantau dan memperbarui status booking test drive, mengelola data pelanggan yang masuk, dan menambah/menghapus promo.

## Cara menjalankan

1. Ekstrak folder proyek.
2. Buka `index.html` dengan browser, atau jalankan server lokal agar semua halaman diuji melalui satu alamat.
3. Untuk menjalankan server lokal di Windows, klik dua kali `run-local.bat`, lalu buka `http://localhost:8000`.

## Catatan penting

Website ini merupakan prototipe front-end untuk tugas/presentasi. Data disimpan pada `localStorage` browser, bukan database online. Login admin hanya pembatas tampilan di sisi browser dan belum aman untuk penggunaan bisnis sungguhan. Untuk produksi, diperlukan backend, autentikasi server, database, validasi upload, serta pengelolaan akses pengguna. Harga dan foto contoh perlu disesuaikan dengan data resmi dealer.
