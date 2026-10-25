# Operasi Dasar Citra Digital: Grayscale

## Deskripsi
Proyek ini merupakan implementasi operasi dasar pengolahan citra digital menggunakan metode **Grayscale** dengan bahasa pemrograman Python. Program mengubah gambar berwarna menjadi gambar dengan tingkat keabuan menggunakan Google Colab.

## Tujuan
- Membaca dan menampilkan gambar digital.
- Mengubah citra berwarna RGB menjadi citra grayscale.
- Membandingkan gambar asli dengan hasil grayscale.
- Menyimpan hasil pengolahan citra digital.

## Teknologi yang Digunakan
- Python
- Google Colab
- Pillow (PIL)
- NumPy
- Matplotlib

## Metode Grayscale
Grayscale merupakan proses mengubah gambar berwarna menjadi gambar dengan tingkat keabuan. Setiap piksel RGB dikonversi menjadi satu nilai intensitas.

Rumus yang digunakan:

```text
Gray = 0.299R + 0.587G + 0.114B
```

Keterangan:
- `R` = intensitas warna merah (*Red*)
- `G` = intensitas warna hijau (*Green*)
- `B` = intensitas warna biru (*Blue*)

Rentang intensitas grayscale adalah 0–255:
- 0 menunjukkan warna hitam.
- 255 menunjukkan warna putih.
- Nilai di antaranya menunjukkan tingkat abu-abu.

## Cara Menjalankan Program
1. Buka [Google Colab](https://colab.research.google.com/).
2. Unggah notebook `.ipynb` melalui menu **File → Upload notebook**.
3. Jalankan setiap sel kode secara berurutan.
4. Unggah foto yang ingin diproses ketika diminta.
5. Program akan menampilkan gambar asli dan hasil grayscale.
6. Hasil grayscale dapat diunduh dengan nama `hasil_grayscale.png`.

## Tahapan Program
1. Import library.
2. Upload gambar.
3. Membaca dan menampilkan gambar asli.
4. Mengubah gambar RGB menjadi grayscale.
5. Menampilkan perbandingan citra asli dan grayscale.
6. Menyimpan serta mengunduh hasil.

## Output
- Gambar asli.
- Gambar hasil grayscale.
- File hasil pengolahan bernama `hasil_grayscale.png`.

## Kesimpulan
Program ini menerapkan satu metode utama, yaitu grayscale, untuk mengubah citra berwarna menjadi citra keabuan. Metode ini mempertahankan informasi intensitas dan detail bentuk objek, tetapi tidak mempertahankan informasi warna asli.

## Penulis
Nama: Ahmad galan Fikri

Mata Kuliah: Pengolahan Citra Digital
