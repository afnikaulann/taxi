TAXI LOKAL SIDRAP — WEBSITE MOBILE

CARA MENJALANKAN
1. Ekstrak file ZIP.
2. Buka folder taxi_lokal_sidrap.
3. Buka index.html dengan browser (Chrome disarankan). Website bisa dijalankan tanpa server untuk fungsi dasar.

WAJIB DIATUR SEBELUM DIGUNAKAN PUBLIK
Buka index.html lalu cari:
const WA_ADMIN = "6280000000000";
Ganti dengan nomor WhatsApp admin dalam format internasional tanpa tanda +. Contoh format Indonesia: 62812XXXXXXXX.

PEMBAYARAN
- QRIS: situs ini hanya menampilkan instruksi placeholder. Untuk pembayaran, kirim QRIS resmi usaha kepada pelanggan melalui admin atau pasang gambar QRIS resmi dengan mengisi QRIS_IMAGE.
- Transfer bank: ganti BANK_DETAILS dengan nama bank, nomor rekening, dan nama pemilik rekening resmi.
- Jangan pernah meminta PIN atau OTP pelanggan.
- Website belum memverifikasi pembayaran otomatis.

JARAK DAN ONGKOS
- Jarak awal 3 km adalah SIMULASI.
- Rumus ongkos: maksimum(jarak × tarif per km, tarif minimum).
- Tombol Google Maps membuka rute berkendara. Website ini belum mengambil jarak rute dari API; konfirmasi jarak dan tarif final secara manual.
- Untuk menghitung jarak rute otomatis, perlu integrasi Google Maps Routes API atau penyedia rute lain, termasuk pengaturan API key dan billing bila diwajibkan.

PUBLIKASI GRATIS
Anda dapat mengunggah file ini ke layanan hosting statis seperti GitHub Pages atau Netlify. Untuk memakai nama domain sendiri biasanya ada biaya domain.
