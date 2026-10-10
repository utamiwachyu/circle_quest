# Circle Lab — Garis Singgung Lingkaran

Website interaktif materi garis singgung lingkaran. Siswa mengisi identitas, memilih sendiri pusat dan jari-jari lingkaran serta gradien dan konstanta garis, lalu menjawab pertanyaan esensial berdasarkan pilihannya.

## File
- `index.html`: struktur halaman
- `style.css`: tampilan putih, responsif
- `script.js`: grafik, perhitungan, pertanyaan, umpan balik, petunjuk

## Unggah ke GitHub Pages
1. Buat repositori baru di GitHub.
2. Unggah ketiga file ini ke bagian root repositori (bukan hanya file ZIP).
3. Buka **Settings → Pages**.
4. Pada bagian Build and deployment, pilih deploy from branch, pilih branch `main` dan folder `/ (root)`, lalu Save.
5. Tunggu URL yang diberikan GitHub Pages, lalu bagikan kepada siswa.

## Cara siswa menggunakan
1. Isi nama dan kelas.
2. Tentukan pusat (a,b), jari-jari r, gradien m, dan konstanta c.
3. Amati grafik dan perbandingan jarak pusat ke garis dengan jari-jari.
4. Jawab 5 pertanyaan. Jawaban salah akan menampilkan petunjuk; siswa bisa mencoba lagi.
5. Lihat hasil dan lakukan refleksi.

## Rumus utama
Untuk pusat P(a,b) dan garis `y = mx + c`, jarak pusat ke garis adalah
`d = |ma - b + c| / √(m² + 1)`.
Garis menyinggung lingkaran jika dan hanya jika `d = r`.

## Catatan
- Grafik menggunakan Canvas, dan hasil disimpan di localStorage browser yang digunakan.
- Font dimuat dari Google Fonts; tanpa internet font alternatif tetap digunakan.
- Versi ini siap diunggah ke GitHub Pages, tetapi hasil siswa tidak otomatis terkumpul ke dashboard guru lintas perangkat. Jika ingin rekap 40 siswa secara real-time, perlu integrasi database/backend seperti Firebase atau Supabase.
