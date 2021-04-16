# Pemograman Web
~~~
Nama  : Andry Prasetia Perdana
NIM   : 311910284
Kelas : TI 19 C1
~~~
# 1.Membuat dokumen HTML
Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut
~~~
<!DOCTYPE  html>
<html  lang="en">
<head>
<meta  charset="UTF-8">
<meta  name="viewport"  content="width=device-width,  initial-scale=1.0">
<title>HTML  Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat  List</h1>
</header>
</body>
</html>
~~~
![Screenshot (46)](https://user-images.githubusercontent.com/81818989/114984304-ccfae600-9ebb-11eb-8819-f3ff06c0753c.png)
# 2.Membuat Ordered List
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
~~~
<section  id="order-list">
<h2>Ordered  List</h2>
<ol>
<li>Pemrograman  Web</li>
<li>Sistem  Informasi</li>
<li>Basis  Data  2</li>
</ol>
</section>
~~~
![Screenshot (47)](https://user-images.githubusercontent.com/81818989/114984456-f287ef80-9ebb-11eb-87f4-15a93ca08499.png)
# 3.Membuat Unorderd List
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada section unordered-list, seperti berikut.
~~~
<section  id="unorder-list">
<h2>Unordered  List</h2>
<ul type="square">
<li>Jaringan  Komputer</li>
<li>Struktur  Data</li>
<li>Algoritma  &amp;  Pemrograman</li>
</ul>
</section>
~~~
![Screenshot (48)](https://user-images.githubusercontent.com/81818989/114984709-34b13100-9ebc-11eb-9538-a506ea6c7448.png)
# 4.Membuat Description List
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list
~~~
<section  id="unorder-list">
<h2>Description  List</h2>
<dl>
<dt>Fakultas  Teknik</dt>
<dd>Teknik  Industri</dd>
<dd>Teknik  Informatika</dd>
<dd>Teknik  Lingkungan</dd>
<dt>Fakultas  Ekonomi  dan  Bisnis</dt>
<dd>Akuntansi</dd>
<dd>Manajemen</dd>
<dd>Bisnis  Digital</dd>
</dl>
</section>
~~~
![Screenshot (49)](https://user-images.githubusercontent.com/81818989/114984997-7cd05380-9ebc-11eb-86b7-3c522cadbc93.png)
# 5.Membuat Tabel
Buat file baru dengan nama lab3_tabel.html seperti berikut
~~~
<!DOCTYPE  html>
<html  lang="en">
<head>
<meta  charset="UTF-8">
<meta  name="viewport"  content="width=device-width,  initial-scale=1.0">
<title>HTML  Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat  Table</h1>
</header>
</body>
</html>
~~~
![Screenshot (50)](https://user-images.githubusercontent.com/81818989/114985225-c1f48580-9ebc-11eb-954f-7d3c1e18bd2c.png)
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
~~~
<table  border="1"  cellpadding="4"  cellspacing="0">
<thead>
<tr>
<th>No.</th>
<th>Fakultas</th>
<th>Program  Studi</th>
</tr>
</thead>
<tbody>
<tr>
<td>1.</td>
<td>Teknik</td>
<td>Teknik  Informatika</td>
</tr>
<tr>
<td>2.</td>
<td>Teknik</td>
<td>Teknik  Industri</td>
</tr>
<tr>
<td>3.</td>
<td>Teknik</td>
<td>Teknik  Lingkungan</td>
</tr>
</tbody>
</table>
~~~
![Screenshot (51)](https://user-images.githubusercontent.com/81818989/114985366-ecded980-9ebc-11eb-9c77-aa45aefdd40f.png)
# 6.Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan
cellspacing pada tag table
~~~
<table  border="1"  cellpadding="4"  cellspacing="0">
~~~
# 7.Menggabungkan Sel Data
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara horizontal).
~~~
<table  border="1"  cellpadding="6"  cellspacing="0">
<thead>
<tr>
<th>No.</th>
<th>Fakultas</th>
<th>Program  Studi</th>
</tr>
</thead>
<tbody>
<tr>
<td>1.</td>
<td  rowspan="3">Teknik</td>
<td>Teknik  Informatika</td>
</tr>
<tr>
<td>2.</td>
<td>Teknik  Industri</td>
</tr>
<tr>
<td>3.</td>
<td>Teknik  Lingkungan</td>
</tr>
</tbody>
</table>
~~~
![Screenshot (52)](https://user-images.githubusercontent.com/81818989/114985649-3e876400-9ebd-11eb-9472-7a61a2efbc8e.png)
# 8.Membuat Form
Buat file baru dengan nama lab3_form.html seperti berikut
~~~
<!DOCTYPE  html>
<html  lang="en">
<head>
<meta  charset="UTF-8">
<meta  name="viewport"  content="width=device-width,  initial-scale=1.0">
<title>HTML  Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat  Form</h1>
</header>
</body>
</html>
~~~
![Screenshot (53)](https://user-images.githubusercontent.com/81818989/114985762-624aaa00-9ebd-11eb-9b95-f57e46783166.png)
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
~~~
<form  action="proses.php"  method="post">
<fieldset>
<legend>Data  Pelanggan</legend>
<p>
<label  for="nama">Nama</label>
<input  type="text"  id="nama"  name="nama">
</p>
<p>
<label  for="alamat">Alamat</label>
<textarea  id="alamat"  name="alamat"  cols="20"  rows="3"></textarea>
</p>
<p>
<label>Jenis  Kelamin</label>
<input  id="jk_l"  type="radio"  name="kelamin"  value="L"  /><label for="jk_l">Laki-laki</label>
<input  id="jk_p"  type="radio"  name="kelamin"  value="P"  /><label
for="jk_p">Perempuan</label>
</p>
<p><input  type="submit"  value="Login"></p>
</fieldset>
</form>
~~~
![Screenshot (54)](https://user-images.githubusercontent.com/81818989/114985863-7db5b500-9ebd-11eb-8bd8-4ca296d311a7.png)
# 9.Menabahkan Style pada Form
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
~~~
form  p  >  label  {
display:  inline-block; width:  100px;
}
form  input[type="text"],  form  textarea  { border:  3px  solid  #197a43;
}
form  input[type="submit"]  { border:  2px  solid  #197a43; background-color:  #197a43; color:  #ffffff;
font-weight:  bold; padding:  5px  15px;
}
~~~
![Screenshot (55)](https://user-images.githubusercontent.com/81818989/114985961-9cb44700-9ebd-11eb-9db8-63d30b9a428f.png)

# Pertanyaan dan Tugas
1.	Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
menampilkan dropdown menu
~~~
<div class="dropdown">
    <button class="mainmenubtn">Main Menu</button>
    <div class="dropdown-child">
      <a href="D:\Tugas Kuliah\Semester 4\Pemograman web\Lab3\lab3_list.html">Menu List</a>
      <a href="D:\Tugas Kuliah\Semester 4\Pemograman web\Lab3\lab3_tabel.html">Menu Table</a>
      <a href="D:\Tugas Kuliah\Semester 4\Pemograman web\Lab3\lab3_form.html">Menu Form</a>
    </div>
  </div>
~~~
![Screenshot (56)](https://user-images.githubusercontent.com/81818989/114999396-050a2500-9ecc-11eb-8ced-2285bd93c43c.png)

menambahkan tampilan listbox dengan multiple selection
~~~
 <!doctype html>

<html>

    <head>

        <title>Cara Membuat Multiple Select Di Satu Tag Select</title>

        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

        <link href="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.6-rc.0/css/select2.min.css" rel="stylesheet" />

    </head>

    <body style="background: rgb(230, 173, 216)">

        <div style="width: 500px; padding: 15px; margin:200px auto;">

            <div class="form-group">

               <h1>Program Fakultas Studi</h1>

                <label>Universitas Pelita Bangsa</label>

                <select id="paket" name="paket[]" class="form-control" multiple="multiple">

                    <option value=""></option>

                    <option value="Teknik Informatika">Teknik Informatika</option>
                    <option value="Teknik Industri">Teknik Industri</option>
                    <option value="Teknik Lingkungan">Teknik Lingkungan</option>
                    <option value="Akuntansi">Akuntansi</option>
                    <option value="Manajemen">Manajemen</option>
                    <option value="Bisnis Digital">Bisnis Digital</option>

                </select>
            </div>
        </div>
</body>
</html>
~~~
![Screenshot (57)](https://user-images.githubusercontent.com/81818989/114999439-0e938d00-9ecc-11eb-97a8-da215c15c5b0.png)
