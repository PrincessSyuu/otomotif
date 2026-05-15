# Otoproject Garage Bekasi — Website Landing Page by Elbert from SMAK Tunas Bangsa Cakung

Landing page untuk **Otoproject Garage Bekasi** (bengkel aksesori mobil) yang menampilkan layanan, fasilitas, galeri, ulasan pelanggan, dan informasi lokasi.

## Fitur
- Desain single-page berbasis anchor (`#tentang`, `#layanan`, `#fasilitas`, `#galeri`, `#ulasan`, `#lokasi`).
- Tailwind CSS via CDN.
- Animasi fade-up saat scroll menggunakan `IntersectionObserver`.
- Mobile navbar dengan toggle (hamburger).
- Galeri **lightbox** (klik gambar) + tutup dengan klik area atau tombol **Escape**.
- Floating tombol WhatsApp dan toast notification.
- Embedded Google Maps pada section lokasi.

## Cara Menjalankan
Karena project ini berupa file HTML statis, cukup buka file berikut di browser:

- `index.html`

Atau jalankan dengan live server (opsional) dari VSCode:
1. Install ekstensi **Live Server**.
2. Klik kanan `index.html` → **Open with Live Server**.

## Teknologi yang Dipakai
- HTML5
- Tailwind CSS (CDN)
- Tailwind config inline (warna & font)
- Iconify (CDN) untuk ikon
- Google Maps Embed

## Catatan Penggantian Konten
Jika ingin mengganti:
- Nomor WhatsApp / link WA: cari bagian `https://wa.me/6281112531327` di `index.html`.
- Alamat & jam operasional: bagian section `#lokasi`.
- Gambar galeri: di beberapa blok `onclick="openLightbox(this)"` (tepatnya pada tag `<img src="...">`).

## Struktur File
- `index.html` — seluruh halaman + style custom + script interaktif.

## Lisensi
Dokumentasi ini menyertakan materi desain/teks yang dapat disesuaikan. Silakan gunakan sesuai kebutuhan proyek Anda.
