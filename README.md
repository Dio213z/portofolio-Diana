# Diana Putri Fadilah — Digital Studio
Portofolio HTML/CSS/JavaScript bertema studio digital coklat–cream. Layout editorial, panel profil berlapis, bagian kemampuan gelap, dan kartu proyek profesional.
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

## Interaksi — versi rombak total
- Sort Motion: visualisasi bubble sort 8 angka. Putar/jeda, satu langkah, acak ulang; otomatis berhenti ketika selesai atau dialog ditutup.
- Letter Shift: sandi Caesar A–Z, geser 0–25, sandikan/buka sandi, balikkan hasil. Huruf besar/kecil dipertahankan; karakter lain tidak berubah. Ini demo pendidikan, bukan keamanan data.
- Date Distance: selisih dua tanggal kalender dengan dasar UTC agar tidak terpengaruh daylight saving; mendukung tahun kabisat dan tanggal terbalik. Tanggal yang sama = 0 hari, awal tidak dihitung.
Ketiga proyek adalah demo baru untuk portofolio ini, bukan klaim karya lampau. Proyek Teman Baca, Jembatan Ukuran, dan Sketsa Kotak sudah diganti.
Kemampuan HTML/CSS, JavaScript, Python, Java 100% merupakan penilaian diri sesuai formulir.

## Animasi dan aksesibilitas
Profil melayang, bola tiga dimensi berbasis CSS, cincin berputar, efek kemiringan ringan mengikuti mouse, teks berjalan, cahaya latar, animasi masuk saat scroll, indikator kemajuan scroll dan hover kartu.
Tombol Jeda animasi menghentikan dekorasi CSS dan kemiringan profil; visualisasi pengurutan memiliki tombol jeda tersendiri. Reduced motion perangkat mematikan animasi dekoratif. Seluruh konten tetap terlihat tanpa animasi. Menu HP, tombol keyboard, dan Escape pada dialog didukung.
Foto dan WhatsApp tetap melalui config.js. Font lokal dan lisensi di assets/fonts.

## Koleksi pita coklat — revisi dekorasi
Tiga SVG lokal: pita-satin.svg, pita-polkadot.svg (bintik putih), dan pita-caramel.svg (ekor panjang). Pita menghiasi profil, biodata, proyek, tombol menuju prestasi, halaman prestasi, dan footer. Geraknya bervariasi, mengikuti tombol jeda dan reduced motion. Semua dekorasi tidak menangkap klik dan disembunyikan dari pembaca layar.
