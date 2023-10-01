<h1><p align="center">Praktikum 1: HTML Dasar</h1>
<table>
  <tr>
    <th colspan="2">DATA MAHASISWA</th>
  </tr>
  <tr>
    <td>Nama</td>
    <td>Aan Fadillah Putra</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312210327</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI.22.A3</td>
  </tr>
</table>

### Membuat Paragraf
```
<!-- paragraf pertama -->
<p>
  Kami sedang belajar HTML dasar, pada matakuliah Pemograman Web di
  prodi Teknik Informatika Universitas Pelita Bangsa
  Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
  dalam mengenal tag-tag dasar HTML.
</p>

<!-- paragraf kedua -->
<p>
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```

![1](https://github.com/aanfadillah/lab1Web/assets/115763475/9c4c34e0-d5a3-4646-90fa-b7ea4a045679)


atur atribut paragraf
```
<p align="center">
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```

![2](https://github.com/aanfadillah/lab1Web/assets/115763475/6f189535-93ff-4dd7-87b6-5ce5099ab2e7)

### Menambahkan Judul 
```
    <!-- paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<p>
  Kami sedang belajar HTML dasar, pada matakuliah Pemograman Web di
  prodi Teknik Informatika Universitas Pelita Bangsa.
  Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
  dalam mengenal tag-tag dasar HTML.
</p>

<!-- paragraf kedua -->
<h2>Paragraf pada HTML</h2>
<p align="center">
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```

![3](https://github.com/aanfadillah/lab1Web/assets/115763475/c80a2f9d-7cd8-4878-9ede-ec0c341ab234)

### Memformat Teks
```
<!-- paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<p>
  Kami sedang belajar HTML dasar, pada matakuliah <b>Pemograman Web</b> di
  prodi <i>Teknik Informatika</i> <mark>Universitas Pelita Bangsa</mark>.
  Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
  dalam mengenal tag-tag dasar HTML.
</p>

<!-- paragraf kedua -->
<h2>Paragraf pada HTML</h2>
<p align="center">
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```
### Menyisipkan Gambar
```
<h3>Menyisipkan gambar</h3>
<img src="Clarkson.jpg" width="480" />
```
![5](https://github.com/aanfadillah/lab1Web/assets/115763475/5ee8f07f-6df9-40aa-a46c-d0c39fe99ac1)

### Menambahkan Hyperlink
```
<nav>
<a href="lab1_tag_dasar.html"><b>DASAR HTML</b></a>
</nav>
```
![6](https://github.com/aanfadillah/lab1Web/assets/115763475/5b9ffc4e-dfc6-45c9-99a6-f5aaa60a41d0)


#### Menjawab Pertanyaan

<b>1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag? </b> <br>
Tidak ada error dan HTML akan berjalan seperti normal. 
<br>

<b>2. Apa perbedaan dari tag ```< p >``` dengan tag ```< br >``` , berikan penjelasannya! </b> <br>
```<br>``` digunakan untuk menggerakan teks ke barisan baru sedangkan ```<p>``` digunakan untuk membuat paragraf baru, ```<br>``` bisa digunakan untuk menambah barisan baru kedalam sebuah teks.
<br>

<b>3. Apa perbedaan atribut ```title``` dan ```alt``` pada tag ```<img>```, berikan penjelasannya! </b> <br>
```alt``` adalah untuk menyediakan tag alt gambar untuk menggambarkan gambar ke crawler mesin pencari dan pembaca layar untuk aksesibilitas web yang lebih baik. ```title``` adalah untuk memberikan penjelasan tentang tag alt gambar dan URL gambar dalam atribut ```src```.
<br>

<b>4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya! </b> <br>
Hanya dengan menggunakan ```width``` foto akan menjadi lebih presisi tetapi ```height``` bisa mengatur foto semaunya 
<br>

<b>5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( ```_blank```, ```_self```, ```_top```, ```_parent``` ), apa yang terjadi pada masing-masing nilai antribut tersebut? </b> <br>
- ```_blank```: Membuka dokumen yang dituju di jendela atau tab baru. 
- ```_self```: Membuka dokumen yang dituju di jendela atau frame yang sama dengan elemen yang diklik. Ini adalah nilai default jika atribut target tidak ditentukan. 
- ```_parent```: Membuka dokumen yang dituju di frame <i>parent</i> dari elemen yang diklik. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self. 
- ```_top```: Membuka dokumen yang dituju di jendela penuh, menggantikan semua frame, termasuk frame luar. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self. 
