ayomain arcade — paket deploy
==============================
Isi zip ini = isi folder public_html (index.html di root).

Cara pasang (cPanel > File Manager > public_html):
1. (Opsional, disarankan) Cadangkan isi public_html lama dulu — itu portal anak versi lama.
2. Upload zip ini ke public_html, lalu Extract.
3. Buka ayomain.cloud — portal arcade tampil, 12 game siap dimainkan.

Fitur portal: cari game, filter kategori, favorit (bintang di kartu),
"Terakhir Dimainkan", tombol Main Acak, dan panel Ganti Game di halaman main.
Favorit + riwayat main tersimpan lokal di browser pengunjung (bukan pelacakan).

Nambah game berikutnya:
- Taruh folder game open-source di games/<slug>/ (harus ada index.html + berkas LICENSE).
- Tambah 1 entri di catalog.js. Selesai — kartu + halaman kredit ikut otomatis.

Semua game berlisensi open-source (MIT / Apache-2.0 / GPL-3.0 / AGPL-3.0).
Atribusi lengkap: credits.html. Model portal mengikuti katalog attogram/games.
