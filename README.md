# Diana Putri Fadilah — Jurnal Digital
Portofolio HTML/CSS/JavaScript bertema coklat–cream, scrapbook dan meja belajar.
Identitas: X RPL 3, absen 3, SMK Krian 1 Sidoarjo.

## Membuka
Ekstrak ZIP lalu buka index.html. Semua font dan dekorasi tersedia lokal. Tidak memerlukan npm install.

## Foto dan kontak
Edit config.js untuk foto profil: imageUrl dapat berupa URL gambar HTTPS publik atau path assets/fotoprofil.jpg. URL harus langsung menuju gambar, bukan album/login. objectPosition mengatur posisi foto, misalnya center top.
Jika kosong, situs mencoba assets/fotoprofil.png, .jpg, .jpeg, lalu menampilkan inisial DP.
Belum ada foto asli yang diberikan.
WhatsApp sudah terisi: 085748391219, format internasional 6285748391219. Tautan membuka percakapan, tidak mengirim pesan otomatis. Email dan Instagram masih kosong; isi jika tersedia.

## Prestasi
Masukkan dokumentasi asli ke folder asset dengan nama prestasi1.png, prestasi2.jpg, prestasi3.jpeg, dan seterusnya.
Tanpa build: gunakan nomor berurutan mulai 1; berhenti pada nomor pertama yang tidak ada.
Dengan build: semua file sesuai pola nama ditemukan, boleh ada celah nomor.
Build: node scripts/build-prestasi.mjs
Hasil: dist. Daftar gambar dibangkitkan otomatis saat build.

## GitHub dan Vercel
1. Unggah isi ZIP yang sudah diekstrak ke root repository GitHub, termasuk index.html dan vercel.json.
2. Import repository di Vercel. Konfigurasi telah disertakan: build node scripts/build-prestasi.mjs, output dist, tanpa framework.
3. Deploy ulang setelah menambah prestasi.
Untuk hosting statis lain, unggah isi dist. GitHub Pages tanpa build bisa memakai galeri dengan nomor berurutan.

## Interaksi
- Teman Baca: hitung kata dan estimasi durasi, pilihan kecepatan 150/200/250 kata per menit. Maksimal 50.000 karakter.
- Jembatan Ukuran: konversi panjang mm/cm/m/km, validasi angka 0 sampai 1 miliar, tampilan maksimal 12 digit signifikan (nilai amat kecil ditampilkan ilmiah).
- Sketsa Kotak: kanvas 8×8, empat warna dan penghapus, tombol bersihkan. Tidak disimpan setelah ditutup.
Ketiga proyek adalah demo yang dibuat untuk portofolio ini, bukan klaim karya lampau.
Kemampuan HTML/CSS, JavaScript, Python, Java 100% ditampilkan sebagai penilaian diri sesuai formulir, bukan sertifikasi.

Menu HP, tema terang/gelap yang disimpan di browser, galeri dengan perbesar gambar, tombol jeda animasi dan reduced motion disertakan. Uap cangkir, bintang, efek scroll, dan hover kartu memakai CSS/JS ringan.
Font lokal memakai DejaVu; lisensi disertakan dalam assets/fonts.
