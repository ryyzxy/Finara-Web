# FINARA — Website Profil

Landing page profil jasa **FINARA — Consulting & Advisory for SME's**
(Owner: Ismi Danty Nopiani).

## Struktur folder
```
finara website/
├── index.html        ← halaman utama
├── css/style.css     ← semua styling
├── js/script.js      ← interaksi (tab, counter, menu)
├── assets/           ← simpan foto di sini (ismi.jpg)
└── README.md
```

## Cara menjalankan (Visual Studio Code)
1. Buka folder `finara-website` di VS Code (`File > Open Folder`).
2. Install extension **Live Server** (oleh Ritwick Dey).
3. Klik kanan `index.html` → **Open with Live Server**.
4. Browser terbuka di `http://127.0.0.1:5500` — selesai.

## Yang perlu diganti
- **Foto owner:** taruh foto di `assets/ismi.jpg` (rasio 4:5 paling pas).
- **Nomor WhatsApp:** cari `6285721432928` di `index.html`, ganti bila perlu.
- **Link LinkedIn:** cari `linkedin.com/in/ismidanty` di `index.html`.
- **Warna/aksen:** ubah variabel di bagian `:root` pada `css/style.css`.

## Deploy gratis (opsional)
- Drag folder ke **Netlify Drop** (app.netlify.com/drop), atau
- Push ke GitHub lalu aktifkan **GitHub Pages**.
