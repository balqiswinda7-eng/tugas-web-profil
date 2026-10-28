# Portfolio Balqis Winda Amaliah

Website portfolio satu halaman (*one-page*) yang dibuat dengan **HTML, CSS, dan JavaScript** murni plus **Bootstrap 5.3**. Tampilannya bergaya *glassmorphism* (kartu kaca transparan) dengan latar bertema jaringan futuristik berwarna teal.

---

## Isi Website

| Bagian | Isi |
|---|---|
| **Home** | Sapaan, nama, bidang, deskripsi singkat, dan foto profil dengan tulisan besar "PORTOFOLIO" di belakangnya |
| **About** | Cerita singkat tentang saya |
| **Skills** | Python, PostgreSQL, Git & GitHub |
| **Projek** | Sistem Inventaris Toko Sembako (Python, CustomTkinter, SQLite) |
| **Kontak** | Email, telepon, lokasi, dan media sosial (GitHub, LinkedIn, Instagram) |

### Fitur

- Navbar menempel di atas, dan link-nya menyala sesuai bagian yang sedang dilihat
- Animasi muncul saat di-scroll memakai **Intersection Observer API** (tanpa library animasi)
- Responsif dari layar HP sampai desktop (Bootstrap Grid)

---

## Struktur Folder

```
portfolio/
├── index.html      # Kerangka halaman (HTML)
├── ui.png          # Gambar latar, dipanggil dari css/style.css
├── css/
│   └── style.css   # Semua gaya tampilan (CSS)
├── js/
│   └── script.js   # Interaksi & animasi (JavaScript)
├── foto/           # Tempat foto profil
│   └── foto-balqis-w.png
├── projek/         # Screenshot Sistem Inventaris (halaman Data Barang)
│   └── projek inventaris.png
└── README.md
```

| Yang dicari | Ada di mana |
|---|---|
| Gambar latar (`ui.png`) | Ada di folder utama (sejajar `index.html`), dipanggil dari CSS |
| Foto profil | Folder `foto/` |
| Screenshot projek | Folder `projek/` |

> **Penting:** nama file dan folder harus **persis sama** dengan yang tertulis di kode (huruf besar-kecil juga berpengaruh). Kalau tidak, latar atau foto tidak akan tampil.

---

## Cara Menjalankan Website

1. Download atau *clone* repository ini.
2. Pastikan susunan foldernya sama seperti di atas.
3. Buka `index.html` di browser (klik dua kali, atau pakai ekstensi *Live Server* di VS Code).
4. Butuh koneksi internet, karena Bootstrap, Bootstrap Icons, dan Google Fonts dimuat dari CDN.

---

## Teknologi yang Dipakai

- HTML5, CSS3, JavaScript (Vanilla)
- [Bootstrap 5.3.3](https://getbootstrap.com/) dan [Bootstrap Icons 1.11.3](https://icons.getbootstrap.com/) via CDN
- Google Fonts: Plus Jakarta Sans, Anton, Great Vibes

---

## Cara Push ke GitHub

Jalankan di terminal dari dalam folder `portfolio`:

```bash
git init
git add .
git commit -m "Tambah website portfolio"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git push -u origin main
```

Ganti `USERNAME` dan `NAMA-REPO` dengan milikmu (buat repository kosong dulu di GitHub).

### Menampilkan sebagai website (opsional)

Di repository GitHub: **Settings → Pages → Branch: `main` / folder `/ (root)` → Save**. Setelah beberapa menit, websitenya bisa dibuka lewat link GitHub Pages.

---

## Pembuat

**Balqis Winda Amaliah**, mahasiswa Sistem Informasi, Universitas PGRI Delta.
