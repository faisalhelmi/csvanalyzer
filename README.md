# 📊 CSV Analyzer

Aplikasi web untuk menganalisis dan memfilter data dari banyak file CSV sekaligus. Berjalan 100% di browser — tidak perlu server atau instalasi apapun.

## ✨ Fitur

- **Multi-file CSV** — Upload banyak file CSV sekaligus; data digabung otomatis
- **Filter per Kolom** — Checkbox filter dinamis untuk setiap kolom kategori
- **Pencarian Global** — Cari teks di semua kolom sekaligus
- **Sort Kolom** — Klik header untuk sort naik/turun
- **Toggle Kolom** — Sembunyikan/tampilkan kolom tertentu
- **Stats Summary** — Ringkasan statistik data yang sedang tampil
- **Export CSV** — Download hasil filter sebagai file CSV baru
- **Pagination** — Navigasi halaman dengan jumlah baris yang dapat diatur

## 🚀 Deploy ke GitHub Pages

### 1. Buat Repository

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/csv-analyzer.git
git push -u origin main
```

### 2. Aktifkan GitHub Pages

1. Buka repository di GitHub
2. Klik **Settings** → **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** / folder: **/ (root)**
5. Klik **Save**

Aplikasi akan live di: `https://USERNAME.github.io/csv-analyzer/`

## 📁 Struktur

```
csv-analyzer/
└── index.html   ← Semua kode ada di sini (pure HTML/CSS/JS)
```

## 💡 Cara Pakai

1. Buka aplikasi di browser
2. Drag & drop atau klik **Pilih File** untuk upload CSV
3. Upload sebanyak file yang diinginkan — data otomatis digabung
4. Gunakan panel filter di kiri untuk memfilter berdasarkan nilai kolom
5. Gunakan kotak pencarian untuk cari teks bebas
6. Klik **Export CSV** untuk download hasil filter
