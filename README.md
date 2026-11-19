# Website Pribadi - Alung Riadi

Tugas 3 Komputasi Awan: deployment website statis dengan GitHub Pages.

## Struktur
- `index.html` - Beranda (nama, NIM, foto, deskripsi)
- `materi.html` - Materi Komputasi Awan
- `portofolio.html` - Portofolio Tugas 1 dan Tugas 2
- `assets/css/`, `assets/images/` - gaya dan gambar

## Sebelum dipublikasikan
Cari teks `[ISI` dan `href="#"` pada `index.html` dan `portofolio.html`, lalu ganti dengan data asli (NIM, ringkasan, tautan Tugas 1 dan 2).

## Deploy ke GitHub Pages
1. Buat repositori publik baru di GitHub.
2. Unggah **isi** folder ini (bukan folder pembungkusnya) ke branch `main`, sehingga `index.html` berada di root repositori.
3. Buka Settings > Pages > Source: *Deploy from a branch*, pilih branch `main` dan folder `/ (root)`, lalu Save.
4. Tunggu 1-2 menit; situs tersedia di `https://<username>.github.io/<nama-repo>/`.
