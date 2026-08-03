# Shadow Ninja — Landing Page

Website statis bertema ninja, dibangun dengan **HTML + Tailwind CSS (via CDN)**.
Layout, warna, dan struktur seksi mengikuti desain referensi (hero merah-hitam,
tentang, karakter ikonik, jelajahi dunia, CTA, footer).

## Cara pakai
1. Ekstrak folder ini.
2. Buka `index.html` langsung di browser (tidak perlu server/build step).
3. Semua gambar ilustrasi ada di folder `assets/` (format SVG, ringan & mudah diedit).

## Struktur file
```
ninja-site/
├── index.html
├── README.md
└── assets/
    ├── hero-bg.svg          (background hero: gunung, bulan, kuil)
    ├── kai.svg, jay.svg, lloyd.svg, cole.svg, zane.svg, nya.svg  (6 karakter)
    ├── about-city.svg       (ilustrasi kota untuk section "Tentang")
    ├── world-monastery.svg
    ├── world-dark-island.svg
    ├── world-kingdoms.svg
    └── cta-figure.svg       (figur silhouette untuk section CTA)
```

## Catatan penting soal hak cipta
Desain referensi yang kamu kirim menggunakan logo **LEGO**, brand **NINJAGO**,
dan artwork karakter yang merupakan kekayaan intelektual berlisensi milik
The LEGO Group — saya tidak bisa mereproduksi logo atau gambar karakter
tersebut secara langsung.

Sebagai gantinya saya:
- Mengganti nama brand jadi **"Shadow Ninja"** (generik, bisa kamu ubah bebas)
- Membuat ilustrasi SVG orisinal (mask ninja, siluet kota, gunung, kuil, dll)
  dengan palet warna & komposisi yang senada dengan desain referensi

Kalau kamu ingin memakai ini untuk proyek/tugas sekolah bertema LEGO Ninjago,
sebaiknya ganti nama brand dan tambahkan disclaimer "fan project, bukan
produk resmi" — atau ganti sepenuhnya ke tema orisinal supaya aman dari
sisi hak cipta.

## Kustomisasi cepat
- Warna utama ada di variabel CSS `:root` bagian atas `index.html`
  (`--crimson`, `--ink`, `--panel`, `--gold`).
- Font judul pakai **Bebas Neue**, font body pakai **Inter** (Google Fonts).
- Semua section punya `id` (misalnya `#karakter`, `#dunia`) untuk anchor link navbar.
