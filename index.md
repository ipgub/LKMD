---
layout: default
title: Home
---

# LKMD BIG 2.0
{: .no_toc .text-delta }

Selamat datang di halaman Laporan Kerja Mingguan Dosen. Halaman ini akan menjelaskan langkah tahap demi tahap untuk membuat laporan LKMD berbasis web pada BIG 2.0 dengan fitur dokumentasi visual (gambar/screenshot). 

## Daftar Isi
{: .no_toc .text-delta }

* TOC
{:toc}

## Persiapan
  - Mendokumentasikan kegiatan dalam bentuk gambar/foto/screenshoot.
  - Mengupload gambar ke repository file; untuk contoh di sini, kita menggunakan repository file yang ada di [https://files.bakrie.ac.id/](https://files.bakrie.ac.id/)
  - Mengeset share link gambar yang sudah diupload ke repository file; link gambar pada repo tersebut ada di [https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK](https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK)
  
## Mengisi Detail Kegiatan
  - Isi dengan teks biasa untuk deskripsi kegiatan
  - Tambahkan dengan link ke gambar yang sudah diupload di repository file dengan menambahkan baris berikut:
    ```html
    <img src="https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK/preview" width=500>
    ```
    Perhatikan bahwa pada bagian yang menandakan sumber gambar (source/src image) kita isi dengan link pada gambar yang ada di repo di atas + '/preview' agar gambar bisa ditampilkan pada rekap LKMD di BIG.

## Save
  - Jangan lupa untuk selalu melakukan saving setiap kali melakukan perubahan detail isian LKMD.
  - Perhatikan selalu kategori kegiatan agar tepat dengan pekerjaan yang dilakukan.
  - Jangan lupa juga untuk mengisi isi-isian waktu mulai dan akhir.
  - Jangan lupa mengeklik tombol simpan data.
