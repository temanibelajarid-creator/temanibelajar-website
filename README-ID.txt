PAKET WEBSITE TEMANIBELAJAR — NETLIFY + PAGES CMS

ISI PAKET
- index.html: homepage
- assets/: logo dan ilustrasi hero
- content/products.json: katalog produk yang dapat diedit melalui Pages CMS
- content/site.json: logo, gambar utama, dan teks hero yang dapat diedit melalui Pages CMS
- .pages.yml: konfigurasi Pages CMS
- netlify.toml: konfigurasi publish Netlify

CARA UPLOAD KE GITHUB
1. Ekstrak ZIP ini di komputer.
2. Buka repository GitHub temanibelajarid-creator/temanibelajar-website.
3. Add file > Upload files.
4. Upload SELURUH ISI folder ini (bukan folder induknya), termasuk file tersembunyi .pages.yml.
5. Commit changes ke branch main.
6. Kembali ke Netlify dan lanjutkan deploy/import.

PENTING TENTANG CMS
CMS yang dipakai adalah Pages CMS (pagescms.org), yang mengedit file di GitHub. Setelah repository dihubungkan dan akses diberikan di Pages CMS, perubahan pada content/products.json akan memicu deploy Netlify otomatis jika integrasi Git Netlify aktif. Halaman admin dikelola di situs Pages CMS, bukan /admin di domain sendiri.

CATATAN
- Logo brand dan ilustrasi utama disimpan di assets/.
- Produk awal mengikuti 20 item yang terlihat di toko Lynk.id saat pengecekan.
- Harga disimpan sebagai angka tanpa Rp/titik.
- Untuk mengganti gambar cover, upload gambar ke assets/ melalui GitHub atau Pages CMS, lalu isi path gambar seperti /assets/nama-gambar.png pada kolom Gambar cover.
- Jangan masukkan password, token, atau rahasia ke file website.
