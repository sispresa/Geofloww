# GeoFlow — GitHub Pages siap unggah

## Isi proyek
- `index.html` — beranda pembelajaran.
- `simulasi.html` — simulasi 3D angin darat dan angin laut.
- `pengunjung.html` — daftar nama pengunjung dan waktu kunjungan, ekspor CSV.
- `profil.html` — profil pengembang dan penjelasan proyek.
- `css/` — stylesheet.
- `js/main.js` — logika simulasi Three.js.
- `js/visitors.js` — formulir nama, penyimpanan kunjungan, dan daftar pengunjung.
- `.nojekyll` — menerbitkan aset statis tanpa pemrosesan Jekyll.

## Cara unggah
1. Ekstrak ZIP ini.
2. Unggah **isi folder** ke root repository GitHub Pages.
3. Pastikan folder `css/` dan `js/` ikut diunggah bersama file HTML.
4. Commit perubahan dan tunggu deployment selesai.
5. Buka `https://sispresa.github.io/Geoflow/` lalu muat ulang dengan `Ctrl + Shift + R`.

## Catatan penyimpanan pengunjung
Situs ini merupakan situs statis, jadi daftar pengunjung disimpan di `localStorage` browser. Nama otomatis muncul di menu Daftar Pengunjung pada browser/perangkat yang sama. Data tidak otomatis terkirim ke pemilik situs dan tidak tersinkron lintas perangkat. Untuk daftar terpusat dari semua pengunjung, diperlukan backend atau database eksternal. Hindari memasukkan data sensitif.

Simulasi Three.js memakai CDN, sehingga koneksi internet diperlukan.
