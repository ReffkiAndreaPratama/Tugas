# LinkShelf 🔖

Bookmark manager ringan untuk menyimpan dan menemukan kembali tautan penting. Dibuat dengan HTML, CSS, dan JavaScript murni—tanpa framework, database, API key, atau proses build.

## Fitur
- Tambah, edit, dan hapus bookmark.
- Kategori: Kuliah, Developer Tools, Referensi, Hiburan, Pribadi, dan Lainnya.
- Pencarian berdasarkan judul, URL, catatan, atau kategori.
- Favorit dan pengurutan terbaru/terlama/judul.
- Ekspor dan impor backup JSON.
- Mode gelap/terang.
- Penyimpanan lokal menggunakan `localStorage`.
- Responsif untuk desktop dan ponsel.

## Menjalankan
Buka `index.html` langsung di browser modern. Tidak memerlukan instalasi paket.

## Catatan privasi
Data bookmark disimpan di browser/perangkat yang digunakan, tidak dikirim ke server. Data tidak otomatis tersinkron antarperangkat. Gunakan tombol **Ekspor** untuk membuat backup JSON secara berkala. Impor file hanya dari sumber tepercaya.

## Struktur
```
linkshelf/
├── index.html
├── style.css
├── app.js
└── README.md
```

## Ide pengembangan
- Tag kustom dan koleksi buatan pengguna.
- Pengecekan tautan mati.
- Sinkronisasi opsional melalui backend.
- Ekspor ke CSV/HTML.

Lisensi: MIT.