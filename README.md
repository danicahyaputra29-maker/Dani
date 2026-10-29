# Latihan JLPT (N5/N4)
Web statis. Tanpa build, tanpa backend.

## Deploy ke GitHub Pages (dari HP)
1. Buat repo publik di github.com (mis. `jlpt-latihan`).
2. Add file > Create new file. Ketik path lengkap, mis. `data/n5-vocab.json` (tanda `/` membuat folder), tempel isinya, Commit. Ulangi untuk semua 10 file: `index.html`, `css/style.css`, `js/app.js`, `data/config.json`, dan 6 file `data/n5-*.json`, `data/n4-*.json`.
3. Settings > Pages > Source: Deploy from a branch > `main` / `(root)` > Save.
4. Tunggu 1-2 menit. Alamat: `https://USERNAME.github.io/jlpt-latihan/`.

## Menambah soal
Tambah objek ke file JSON di `data/`. `mondai` harus sesuai nomor 問題. `answer` = indeks opsi benar (mulai 0). Jumlah soal per 問題 dan durasi diatur di `data/config.json`.

## Menambah level (N3-N1)
Tambah blok level di `config.json` dan file JSON-nya. Kode tidak perlu diubah.
