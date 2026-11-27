TEMANIBELAJAR.ID — PAKET HOMEPAGE

ISI PAKET
- index.html: homepage responsif
- logo.png: logo bulat sementara
- hero.png: visual hero tanpa teks/manusia/hewan
- products.json: katalog 20 produk
- site.json: pengaturan judul, deskripsi, logo, dan hero
- .pages.yml: konfigurasi Pages CMS
- netlify.toml: konfigurasi publish Netlify

UPLOAD KE GITHUB
1. Ekstrak ZIP.
2. Buka repository temanibelajarid-creator/temanebelajar-website.
3. Upload seluruh isi folder ini ke root repository (termasuk .pages.yml).
4. Commit ke branch main.
5. Pastikan Netlify terhubung ke repository dan branch main, lalu tunggu deploy.

CMS
1. Buka https://app.pagescms.org dan masuk dengan GitHub.
2. Berikan akses Pages CMS ke repository website.
3. Pilih repository temanibelajarid-creator/temanebelajar-website.
4. Pages CMS membaca .pages.yml untuk menampilkan Katalog Produk dan Pengaturan Homepage.
5. Perubahan yang disimpan ke GitHub akan memicu deploy Netlify jika integrasi Git aktif.

CATATAN
- Logo saat ini adalah konsep sementara; ganti logo.png setelah logo final Canva siap.
- Gambar hero menggunakan hero.png. Copy judul dan deskripsi tetap berupa teks HTML agar mudah disunting dan responsif.
- Harga produk berupa angka dengan pemisah ribuan opsional, tanpa awalan Rp.
- Tautan pembelian mengarah ke Lynk.id.
