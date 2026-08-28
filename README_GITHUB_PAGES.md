# ZENSTORE — GitHub Pages

Versi ini menggunakan **transfer langsung** ke akun DANA, GoPay, dan ShopeePay. Tidak membutuhkan XAMPP, Vercel, atau Xendit.

## Upload
1. Upload isi folder `zenwork` ke repository GitHub.
2. Pastikan `index.html` berada di root repository.
3. Aktifkan Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Ganti nomor pembayaran
Buka `index.html`, cari `const paymentAccounts`, lalu ganti nomor DANA, GoPay, dan ShopeePay sesuai akun ZENSTORE.

## Alur
Pelanggan memilih metode → klik BAYAR SEKARANG → nomor tujuan dan total muncul → pelanggan transfer → klik SUDAH TRANSFER & KONFIRMASI → WhatsApp ZENSTORE terbuka dengan detail order otomatis.

> Catatan: karena ini transfer langsung, status pembayaran tidak dapat diverifikasi otomatis oleh GitHub Pages. Bukti transfer tetap perlu diperiksa oleh admin.
