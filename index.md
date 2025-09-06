---
layout: default
title: LKMD BIG 2.0
---

# LKMD BIG 2.0
{: .no_toc .text-delta }

Halaman ini akan menjelaskan ringkasan langkah tahap demi tahap untuk membuat laporan LKMD berbasis web pada BIG 2.0 dengan fitur dokumentasi visual (gambar/screenshot). 

## Daftar Isi
{: .no_toc .text-delta }

* TOC
{:toc}

## Persiapan
  - Mendokumentasikan kegiatan dalam bentuk gambar/foto/screenshoot.
  - Mengupload gambar ke repository file; untuk contoh di sini, kita menggunakan repository file yang ada di [https://files.bakrie.ac.id/](https://files.bakrie.ac.id/)
  - Mengeset share link gambar yang sudah diupload ke repository file; misalnya, pada contoh di bawah ini, link gambar pada repo tersebut ada di [https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK](https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK)
    
    ![Link sharing](img/Screen%20Shot%202025-09-01%20at%2013.17.11.png)
  
## Mengisi Detail Kegiatan
  - Isi dengan teks biasa untuk deskripsi kegiatan
  - Atau, bisa juga gunakan template kode html berikut untuk mengisi judul kegiatan dan rincian sederhana kegiatan:
    ```html
    <b>NAMA KEGIATAN</b>
    <br>
    <ul>
      <li> Deskripsi singkat 1
      <li> Deskripsi singkat 2
      <li> dst
    </ul>
    ```
  - Tambahkan dengan link ke gambar yang sudah diupload di repository file dengan menambahkan baris berikut:
    ```html
    <img src="https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK/preview" width=500>
    ```
    Perhatikan bahwa pada bagian yang menandakan sumber gambar (source/src image) kita isi dengan link pada gambar yang ada di repo di atas + '/preview' agar gambar bisa ditampilkan pada rekap LKMD di BIG.

    * Lokasi URL gambar di repo: `https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK`
    * Link gambar yang kita masukkan di Detail Kegiatan isian LKMD: `https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK/preview`

  - Untuk file gambar yang diupload ke folder repository lain seperti github, misalnya, URL gambar yang diupload adalah sebagai berikut:
     ```html
     <img src="https://github.com/username/repo/raw/main/path/filename.jpg" width=500>
     ```

## Menyimpan
  - Jangan lupa untuk selalu melakukan saving setiap kali melakukan perubahan detail isian LKMD.
  - Perhatikan selalu kategori kegiatan agar tepat dengan pekerjaan yang dilakukan.
  - Jangan lupa juga untuk mengisi isi-isian waktu mulai dan akhir.
  - Jangan lupa mengeklik tombol simpan data.

## Contoh Tampilan 

  - Menu LKMD

  ![LKMD01](img/LKMD01.png)

  - Print out (jika dibutuhkan)
    
  ![LKMD02](img/LKMD02.png)
    
## Template

Template isian item laporan LKMD berbasis web/html agar bisa menggunakan font styles, list, dan gambar:

```html
<b>NAMA KEGIATAN</b>
<br>
<ul>
  <li> Deskripsi singkat 1
  <li> Deskripsi singkat 2
  <li> dst
</ul>
<br>
<b>Dokumentasi
<br>
<ol>
<li>Upload repo UBakrie:<br>
<img src="https://files.bakrie.ac.id/s/9kj33C6m5Xd6fYK/preview" width=500>
<li>Upload repo lain (Github): <br>
<img src="https://github.com/username/repo/raw/main/path/filename.jpg" width=500>
</ol>
```