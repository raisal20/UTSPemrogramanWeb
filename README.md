# BOOKSPACE — UTS Pemrograman Web 1

Website front-end sederhana untuk simulasi toko buku online. Dibuat menggunakan HTML, CSS, dan JavaScript tanpa backend/database.

## Struktur folder
```text
BOOKSPACE-UTS-Pemrograman-Web/
├── login.html
├── dashboard.html
├── stok.html
├── checkout.html
├── tracking.html
├── css/
│   └── style.css
└── js/
    ├── data.js
    └── app.js
```

## Cara menjalankan
1. Buka folder project di Visual Studio Code.
2. Jalankan `login.html` dengan ekstensi Live Server (klik kanan → Open with Live Server). Bisa juga membuka file `login.html` langsung di browser.
3. Login dengan akun demo:
   - Email: `admin@bookspace.com`
   - Password: `123456`

## Fitur yang dibuat
- Login dengan validasi dan alert jika email/password salah.
- Modal Lupa Password dan Daftar.
- Dashboard dengan greeting sesuai waktu lokal.
- Katalog dari konstanta `dataKatalogBuku` di `js/data.js`.
- Tambah, cari, dan hapus data buku menggunakan JavaScript DOM.
- Checkout: pilih buku, atur jumlah, validasi stok, isi data pemesan dan pembayaran.
- Nomor Delivery Order otomatis dan tracking status pengiriman.
- Laporan ringkas dan histori transaksi pada dashboard.
- Data katalog dan pesanan disimpan di `localStorage` agar tidak hilang saat halaman dimuat ulang pada browser yang sama.

## Catatan
Ini adalah simulasi front-end. Login, pendaftaran, reset password, pembayaran, dan status kurir tidak terhubung ke server atau layanan sungguhan. Data awal dapat dilihat dan diedit di `js/data.js`.
