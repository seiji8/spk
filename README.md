# README – SPK Pemilihan Tempat Makan Mahasiswa (Metode SAW)
Deskripsi
Sistem Pendukung Keputusan berbasis web ini dibuat untuk membantu mahasiswa dalam menentukan tempat makan terbaik berdasarkan beberapa kriteria menggunakan metode Simple Additive Weighting (SAW). Aplikasi ini memungkinkan pengguna memasukkan alternatif tempat makan dan memberikan bobot pada setiap kriteria sesuai preferensi.

Fitur
Input bobot kriteria dinamis (total harus 100%)

Penambahan alternatif tempat makan secara fleksibel

Perhitungan otomatis menggunakan metode SAW

Hasil ranking ditampilkan dalam bentuk daftar dan visualisasi grafik batang

Antarmuka responsif menggunakan Tailwind CSS

Kriteria Penilaian
Kriteria	Skala
QRIS	0 (Tidak Ada) / 1 (Ada)
Instagramability	Skala 1–5
Kenyamanan Nugas	Skala 1–5
Harga Terjangkau	Skala 1–5 (semakin murah semakin tinggi nilai)
Jarak	Skala 1–5 (semakin dekat semakin tinggi nilai)

Metode SAW (Simple Additive Weighting)
Metode SAW digunakan untuk melakukan evaluasi multi-kriteria dengan menjumlahkan nilai-nilai yang telah dinormalisasi dan dikalikan dengan bobot kriteria. Alternatif dengan skor total tertinggi dianggap sebagai pilihan terbaik.

Struktur File
bash
Copy
Edit
.
├── index.html       # Halaman utama SPK
├── README.md        # Dokumentasi

Teknologi yang Digunakan
HTML5

Tailwind CSS (melalui CDN)

JavaScript (Vanilla)

Chart.js (untuk visualisasi hasil)

Catatan Tambahan
Total bobot seluruh kriteria harus tepat 100% agar perhitungan dapat dilakukan.

Data yang dimasukkan tidak disimpan, karena aplikasi ini bersifat statis dan tanpa backend.

