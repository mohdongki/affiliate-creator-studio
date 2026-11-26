# Affiliate Creator Studio — versi awal

Aplikasi web responsif untuk pengelolaan kegiatan affiliate dari browser HP/desktop.

## Fitur yang sudah tersedia
- Dashboard ringkas.
- CRUD produk affiliate.
- Rencana konten sederhana.
- Pencatatan klik, pesanan, dan komisi secara manual.
- Laporan dasar dan ekspor CSV.
- Ekspor/pulihkan cadangan JSON.
- 10 alur AI Agent berbasis template lokal.

## Batasan penting
Versi ini adalah fondasi aplikasi lokal. Data disimpan di `localStorage` browser pada perangkat yang digunakan. Data tidak otomatis tersinkron ke perangkat lain dan belum terhubung ke Shopee, TikTok Shop, atau marketplace lain.
Sepuluh agent saat ini menghasilkan template/draf lokal, bukan panggilan ke model AI. Untuk AI generatif sungguhan diperlukan backend dan API key yang disimpan aman di server, bukan di HTML publik.

## Cara mencoba
Buka `index.html` di browser. Tidak perlu instalasi Node.js atau aplikasi tambahan.

## Cara menerbitkan lewat GitHub Pages
1. Buat repository GitHub.
2. Unggah isi folder ini ke root repository (pastikan `index.html` berada di root).
3. Tekan **Commit changes**.
4. Di repository, buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main`, folder `/(root)`, lalu **Save**.
7. Tunggu proses selesai, lalu buka URL GitHub Pages yang ditampilkan.

## Keamanan dan privasi
Jangan masukkan password, token, atau API key ke file HTML/JS yang diunggah ke repository publik. Gunakan repository private untuk source pribadi, dan backend untuk rahasia API.
