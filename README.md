# BookStore UI — Prototype UTS (HTML & CSS)

Versi ini adalah rancangan tampilan statis yang diselaraskan dengan project full-stack BookStore (PHP/MySQL) yang diberikan sebagai referensi.

## Teknologi
- HTML5
- CSS3

Tidak ada PHP, JavaScript, MySQL, API, maupun backend pada project ini. Form dan tombol merupakan elemen visual; tautan antarhalaman statis dapat digunakan untuk melihat rancangan halaman.

## Cara menjalankan
Ekstrak ZIP, lalu buka `index.html` melalui browser. Tidak memerlukan Docker, XAMPP, PHP, atau database.

## Halaman
### Pengunjung / pelanggan
- `index.html` — Beranda
- `pages/katalog.html` — Katalog buku
- `pages/detail-buku.html` — Detail buku
- `pages/login.html` — Masuk
- `pages/register.html` — Registrasi
- `pages/keranjang.html` — Keranjang belanja
- `pages/checkout.html` — Checkout
- `pages/riwayat.html` — Riwayat pesanan

### Admin
- `admin/index.html` — Dashboard
- `admin/books.html` — Kelola buku
- `admin/categories.html` — Kategori
- `admin/users.html` — Pengguna
- `admin/orders.html` — Transaksi

## Penyesuaian terhadap project backend
- Menggunakan stylesheet yang sama dengan project PHP: `assets/css/style.css`.
- Identitas dan navigasi mengikuti `includes/header.php`.
- Footer mengikuti `includes/footer.php`.
- Navigasi admin mengikuti `admin/_header.php`; tidak menggunakan sidebar karena project backend aslinya memakai navigasi header.
- Struktur halaman mengikuti komponen dan istilah pada halaman PHP seperti katalog, detail buku, keranjang, checkout, riwayat pesanan, dan halaman admin.

## Batasan
Prototype hanya menunjukkan rancangan UI. Data buku, pelanggan, dan transaksi merupakan data contoh. Login, pencarian, filter, pengubahan jumlah, checkout, dan pengelolaan admin belum menjalankan proses sebenarnya.
