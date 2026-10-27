<<<<<<< HEAD
# Prototype Profiling Penyedia SPSE

Prototype ini adalah situs statis. Seluruh tampilan, CSS, data simulasi, dan interaksi berada di dalam `index.html` sehingga tidak membutuhkan proses build atau backend.

Pada halaman perbandingan profil, tabel pengalaman menampilkan tiga pengalaman terbaru untuk setiap penyedia. Tombol pada masing-masing kelompok penyedia membuka pengalaman ke-4 dan seterusnya dalam tabel yang sama, dengan kolom Nama Tender, K/L/PD, Kualifikasi, Nilai Paket, dan Tanggal Selesai Tender. Tombol **Buka semua pengalaman** dapat digunakan untuk membuka seluruh daftar peserta sekaligus.

Pada halaman detail Profiling Penyedia, card Ringkasan Profil telah dihilangkan. Pengguna langsung melihat data detail mulai dari Identitas, Kualifikasi, dan Bidang Usaha. Tabel peserta, pengalaman, daftar hitam, Pemilik Manfaat, penilaian, dan perbandingan menggunakan pola visual yang konsisten.

Case **Rata-rata kinerja belum tersedia** menyembunyikan bagian nilai kinerja karena nilai tersebut masih dalam proses pengembangan dan tidak dihitung oleh Profiling Penyedia. Pengguna tetap melihat dua tabel: **Pengalaman sedang berjalan** dan **Pengalaman berpotensi berkontrak**, lengkap dengan Nama Tender, ID Paket, K/L/PD, Kualifikasi, Nilai Paket, tanggal, dan status.

## Menjalankan di localhost

```bash
python3 -m http.server 8080
```

Lalu buka `http://localhost:8080/`.

## Mempublikasikan dengan GitHub Pages

1. Buat repository kosong dan public di GitHub, misalnya `prototype-profiling-penyedia`.
2. Jalankan perintah berikut dari folder prototype ini:

```bash
git init -b main
git add index.html README.md
git commit -m "Publish prototype Profiling Penyedia"
git remote add origin https://github.com/USERNAME/prototype-profiling-penyedia.git
git push -u origin main
```

3. Di repository GitHub, buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch **main**, folder **/(root)**, lalu **Save**.
6. Setelah proses publikasi selesai, situs dapat diakses melalui:

```text
https://USERNAME.github.io/prototype-profiling-penyedia/
```

Semua data pada prototype merupakan data simulasi. Pastikan tidak menambahkan data asli, rahasia, token, password, atau identifier sensitif sebelum repository dibuat public.
=======
# prototype-profiling-penyedia-spse
Prototype untuk fitur Profiling Penyedia pada fitur SPSE (e-procurement)
>>>>>>> f10ba5be16442bb555d5328f9598ebc7370759c7
