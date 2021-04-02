# Lab1Web

# Praktikum 1

# Pemograman WEB

~~~
Nama  : Isnaini Rizkyana
NIM   : 311910254
Kelas : TI.19.C1
~~~
## Langkah-langkah Praktikum
Persiapan membuka VSCode dan Browser.
![VSCode](https://user-images.githubusercontent.com/81541764/113438810-831df480-9413-11eb-8b22-9707c889a216.JPG)

Kemudian buat file baru dengan nama **lab1_tag_dasar.html** dan tambahkan tag dasar dokumen HTML.

~~~
<!DOCTYPE html>
<html>
  <head>
    <title>Tag HTML Dasar</title>
  </head>
  <body>
  
  </body>
</html>
~~~
### Modul Praktikum Pemograman WEB

Kemudian selanjutnya, buka file tersebut pada web browser misalnya **Mozilla Firefox**.
![Dasar 0](https://user-images.githubusercontent.com/81541764/113439399-b1500400-9414-11eb-976b-8b942d61fdb2.JPG)

## 1. Membuat Paragraf
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut.
~~~
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
   Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
   adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
    
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
   kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
   dengan menggunakan tag dasar html.</p>
~~~
Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser, lihat hasilnya.
![1](https://user-images.githubusercontent.com/81541764/113440583-e9f0dd00-9416-11eb-9e63-be32d1c80f68.JPG)

## Modul Praktikum Pemrograman Web
![1](https://user-images.githubusercontent.com/81541764/113441068-ced29d00-9417-11eb-93d7-1e1dfa8bd7ee.JPG)

Kemudian atur atribut paragraf seperti berikut, dan amati perubahanya.
~~~
<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
~~~
Simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser. Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.

### Align Justify
~~~
<!-- Ini adalah paragraf pertama -->
<p align=”justify”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”justify”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
~~~
![Langkah 1 (Membuat Paragraf) align justify](https://user-images.githubusercontent.com/81541764/113441503-9ed7c980-9418-11eb-9e4b-a9b76c644c8a.JPG)

### Align Right
~~~
<!-- Ini adalah paragraf pertama -->
<p align=”right”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
~~~
![Langkah 1 (Membuat Paragraf) align right](https://user-images.githubusercontent.com/81541764/113441847-30473b80-9419-11eb-968f-e3ff38bc12c7.JPG)

### Align Left
~~~
<!-- Ini adalah paragraf pertama -->
<p align=”left”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”left”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
~~~
![Langkah 1 (Membuat Paragraf) align left](https://user-images.githubusercontent.com/81541764/113442024-7a302180-9419-11eb-9b20-8808d4bbbebf.JPG)

### Align Center
~~~
<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”center”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
~~~
![Langkah 1 (Membuat Paragraf) align center](https://user-images.githubusercontent.com/81541764/113442144-b8c5dc00-9419-11eb-8dcb-e6256345cdc3.JPG)

## 2. Menambahkan Judul
Seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu mulai h1 sampai h6. Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
~~~
<!-- judul paragraf pertama -->
  <h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
  <h2>Paragraf pada HTML</h2>
~~~
Simpan perubahannya dan lihat hasilnya dengan melakukan refresh pada browser.

### Modul Praktikum Pemrograman Web
![Langkah 2 (Menambahkan Judul)](https://user-images.githubusercontent.com/81541764/113442930-2cb4b400-941b-11eb-81a1-f5085b6a0c1f.JPG)

## 3. Memformat Teks
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
~~~
<p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
~~~
![Langkah 3 (Pemformatan Text)](https://user-images.githubusercontent.com/81541764/113443437-2ecb4280-941c-11eb-91be-a8c2aee35e67.JPG)
Lakukan eksperimen lainnya dengan tag-tag pemformatan teks yang ada.
### Tag sub - Subscript text
  ~~~
  <p align="justify">Ini merupakan <sub>sebuah paragraf</sub> yang terdiri dari beberapa kalimat yang saling mendukung
    sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>
  ~~~
  ![Langkah 3 (Pemformatan Text) (sub)](https://user-images.githubusercontent.com/81541764/113443601-7e117300-941c-11eb-9a6f-835d2960f4cf.JPG)
### Tag em - Emphasized text
  ~~~
  <p align="justify">Ini merupakan <sub>sebuah paragraf</sub> yang terdiri dari <em>kalimat yang saling mendukung</em>
    sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>
  ~~~
  ![Langkah 3 (Pemformatan Text) huruf miring (em)](https://user-images.githubusercontent.com/81541764/113443927-11e33f00-941d-11eb-88db-7f21ae857c9a.JPG)
### Tag strong - Important text
~~~
  <p align="justify">Ini merupakan <sub>sebuah paragraf</sub> yang terdiri dari <em>kalimat yang saling mendukung</em>
    sehingga menjadi satu <strong>kesatuan</strong>. Paragraf dibuat dengan menggunakan tag dasar html.</p>
~~~
![Langkah 3 (Pemformatan Text)  strong](https://user-images.githubusercontent.com/81541764/113444892-f5e09d00-941e-11eb-85fc-c9af5d1c06ba.JPG)
### Tag sup - Superscript text
~~~
  <p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi 
    <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama yang kami dapat
    <sup>adalah membuat </sup> tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
~~~
![Langkah 3 (Pemformatan Text) (sup)](https://user-images.githubusercontent.com/81541764/113445112-71424e80-941f-11eb-93d9-ecd5bb33113c.JPG)
### Tag del - Deleted text
~~~
 <p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi 
    <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama yang kami dapat
    <sup>adalah membuat </sup> tampilan <del>web sederhana</del> dalam rangka mengenal tag-tag dasar HTML.</p>
~~~
![Langkah 3 (Pemformatan Text) (del)](https://user-images.githubusercontent.com/81541764/113445330-e31a9800-941f-11eb-9e19-b77a956fe00b.JPG)
### Tag small - Smaller text
~~~
 <p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi 
    <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama yang kami dapat
    <sup>adalah membuat </sup> tampilan <del>web sederhana</del> dalam rangka mengenal tag-tag dasar HTML.</p>
~~~
![Langkah 3 (Pemformatan Text) (small)](https://user-images.githubusercontent.com/81541764/113445523-3987d680-9420-11eb-8e3e-818643e11e24.JPG)

## 4. Menyisipkan Gambar
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan gambar dari website external.

### Modul Praktikum Pemograman WEB
![4](https://user-images.githubusercontent.com/81541764/113445705-9c796d80-9420-11eb-8b40-99b7e63506b5.JPG)

Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.
~~~
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo_pelita.jpg" width="200" title="Logo Univeritas Pelita Bangsa">
~~~
