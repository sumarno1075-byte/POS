# RasaPOS — POS Restoran & Cafe

Aplikasi POS web statis terhubung ke Supabase. Tidak membutuhkan XAMPP.

## Menjalankan
1. Ekstrak ZIP.
2. Deploy `index.html` ke Cloudflare Pages (Direct Upload atau hubungkan repository GitHub).
3. Supabase URL dan publishable key sudah dikonfigurasi di file. Publishable key memang aman berada di frontend; jangan pernah menambahkan `service_role` atau secret key.
4. Di Supabase Authentication → URL Configuration, tambahkan URL aplikasi hasil deploy sebagai Site URL dan Redirect URL.
5. Daftarkan akun pemilik pertama terlebih dahulu. Akun pertama yang berhasil dibuat menjadi Admin. Jangan bagikan alamat aplikasi sebelum Admin pertama berhasil dibuat.
6. Akun yang mendaftar berikutnya otomatis berperan sebagai Kasir.

## Fitur
Login/pendaftaran, dashboard, kasir dine-in/takeaway/delivery, diskon/pajak, pembayaran dan kembalian, cetak struk, produk, kategori, stok masuk, laporan omzet/laba kotor, ekspor CSV, pengaturan toko.

## Catatan
- Perlu internet dan browser modern.
- Uji transaksi sebelum operasional.
- Backup data berkala. Paket gratis dapat memiliki kuota dan kebijakan jeda project saat tidak aktif.
- Akun Kasir baru bisa mendaftar dari layar login setelah Admin pertama dibuat.
