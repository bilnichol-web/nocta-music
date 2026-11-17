NOCTA v2 — Panduan menjalankan

Isi folder:
- index.html: tampilan NOCTA
- server.js: server lokal + endpoint pencarian
- gdstudio.js: modul GDStudio yang kamu kirim
- package.json: konfigurasi Node.js

SYARAT
- Node.js 18 atau lebih baru
- curl tersedia di komputer/server (modul gdstudio.js menjalankan curl)
- Koneksi internet

CARA MENJALANKAN DI KOMPUTER
1. Ekstrak ZIP ini.
2. Buka terminal/Command Prompt di folder hasil ekstrak.
3. Jalankan: npm start
4. Buka browser ke: http://localhost:3000

CARA MENGGUNAKAN
- Cari judul lagu atau artis.
- Hasil pencarian berasal dari NetEase, JOOX, dan Bilibili melalui GDStudio.
- Tombol hati menyimpan favorit di browser.
- Tombol + menambahkan lagu ke playlist.

CATATAN
- Ini versi awal integrasi; layanan sumber dapat berubah, membatasi permintaan, atau tidak selalu menyediakan audio/cover/lirik.
- Pemutaran audio bergantung pada URL stream yang dikembalikan layanan dan dukungan browser. Gunakan hanya konten yang memang boleh kamu akses/putar sesuai ketentuan sumber dan hak pemiliknya. Tidak ada fitur unduh.
- NOCTA hanya menampilkan status ketersediaan lirik, bukan menyalin teks lirik berhak cipta.
- Jangan membuka server ini ke internet publik tanpa menambahkan rate limit, validasi, dan pengamanan tambahan.


IDENTITAS WEBSITE
Owner: bil gtg ky jfri
TikTok Admin: https://www.tiktok.com/@eldigidw?_r=1&_t=ZS-9Au8ckVUVmi
Copyright footer sudah ditambahkan pada halaman utama (index.html).
