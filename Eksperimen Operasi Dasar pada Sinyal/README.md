# Eksperimen Operasi Dasar pada Sinyal dan Citra
**Nama Mahasiswa:** [Isi Nama Kamu]  
**Mata Kuliah:** Pengolahan Sinyal Digital  

## Deskripsi Singkat Project
Project individu ini mengimplementasikan operasi dasar matematika berupa penjumlahan, penggeseran, dan amplifikasi pada sinyal diskrit 1D serta citra digital 2D menggunakan bahasa Python. Project ini juga memuat pengujian matematis dan visual untuk membuktikan sifat linieritas (homogenitas dan additivitas) pada sistem.

## Library yang Digunakan
- NumPy
- Matplotlib
- OpenCV

## Cara Menjalankan Notebook
1. Unduh atau clone repositori ini.
2. Buka file di dalam folder `notebook/operasi_sinyal_citra.ipynb` menggunakan Google Colab atau Jupyter Notebook.
3. Pastikan file gambar di folder `images/` sudah diunggah ke lingkungan kerja sebelum menjalankan kode citra.
4. Jalankan setiap cell kode secara berurutan.

## Struktur Folder Project
- notebook/
  - operasi_sinyal_citra.ipynb
- images/
  - citra.jpg
- report/
  - laporan.pdf
- README.md
- requirements.txt

## Ringkasan Hasil Eksperimen
- Operasi penjumlahan pada sinyal menghasilkan pergeseran DC offset, sementara pada citra mengubah tingkat kecerahan (brightness).
- Operasi penggeseran menyimulasikan efek delay waktu pada sinyal dan translasi posisi pada objek citra.
- Sifat linieritas terbukti penuh pada sistem linier T1(x) = 2x, sedangkan sistem kuadrat T2(x) = x^2 terbukti non-linier karena gagal memenuhi prinsip superposisi (homogenitas dan additivitas).