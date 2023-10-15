# Membuat List, Table dan Form

## 1. Membuat Ordered List
```
<!DOCTYPE html>
<html lang="en">
<head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>
    
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
    </ol>
</section>
```
### Hasilnya
![Gambar Ordered List](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/d23e97b3-d5cc-4393-bc4c-951c72ce4d32)

## 2. Unordered List
```
<section id="unordered-list">
    <h2>Unordered List</h2>
    <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemrograman</li>
    </ul>
</section>
```
### Hasilnya
![Gambar Unordered List](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/043b2a10-0c07-4b0c-a22f-955ec46008d5)

## 3. Membuat Description List
```
<section id="Description-list">
    <h3>Description List</h3>
    <dl>
        <dt>Fakultas Teknik</dt>
        <dd>Teknik Industri</dd>
        <dd>Teknik Informatika</dd>
        <dd>Teknik Lingkungan</dd>
        <dt>Fakultas Ekonomi dan Bisnis</dt>
        <dd>Akuntansi</dd>
        <dd>Manajemen</dd>
        <dd>Bisnis Digital</dd>
    </dl>
</section>
```
### Hasilnya
![Gambar Description List](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/d4549795-570e-45b6-9c5e-700b21b887dd)

## 4. Membuat Tabel
```
<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>

</head>
<body>
    
    <header>
    <h1>Membuat Table</h1>
    </header>
</table>
</body>
</html>
```
### Hasilnya
![Gambar tabel 1](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/efd52e04-3e0c-41ac-8adc-7e2f654352cc)

## 5. Menggabungkan Sel Data
```
<table border="1" cellpadding="5" cellspacing="5">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>        
    </thead>
    <tbody>
        <tr>               
            <td>1.</td>
            <td rowspan="3">Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
### Hasilnya
![Gambar menggabungkan sel datal](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/de7f08f6-348e-42da-88a5-786d39d7cdce)

## 6. Mengatur Margin dan Padding
Cara untuk merubah margin dan padding tabel dapat mengubah angka pada:
```
<table border="1" cellpadding="5" cellspacing="5">
```
![Gambar mengatur margin   padding](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/e9ebec87-c97c-41dd-8d11-ea3b85760585)

## 7. Membuat Form
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Form Mahasiswa</h1>
    </header>
<form action="proses.php" method="post">
    <fieldset>
        <legend>Data Mahasiswa</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>
        <p>
            <label for="NIM">NIM</label>
            <textarea id="NIM" name="NIM" cols="20" rows="1"></textarea>
        </p>
        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
            <input id="jk_p" type="radio" name="kelamin" value="P" /><label
for="jk_p">Perempuan</label>

</form>
</body>
</html>
```
### Hasilnya
![Gambar membuat form](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/d516eb34-eb91-4d99-9d41-4d766cdd770a)

## 8. Menambahkan Style pada Form
```
    <style>
        form p > label {
        display: inline-block;
        width: 100px;
        }
        form input[type="text"], form textarea {
        border: 1px solid #197a43;
        }
        form input[type="submit"] {
        border: 1px solid #197a43;
        background-color: #197a43;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
        }
    </style>
```
### Hasilnya
![Gambar menambahkan style form](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/615800c6-184e-4dab-a4b0-41e9e796d473)

## TUGAS Lab3Web
- Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Form Mahasiswa</h1>
    </header>
<form action="proses.php" method="post">
    <fieldset>
        <legend>Data Mahasiswa</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>
        <p>
            <label for="NIM">NIM</label>
            <textarea id="NIM" name="NIM" cols="20" rows="1"></textarea>
        </p>
        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
            <input id="jk_p" type="radio" name="kelamin" value="P" /><label
for="jk_p">Perempuan</label>
    
    <h2>Pilih Fakultas Anda:</h2>
    <form action="proses_form.php" method="post">
        <label for="Fakultas">Pilih Fakultas:</label>
        <select id="Studi" name="Studi">
            <option value="Teknik Informatika">Teknik Informatika</option>
            <option value="Teknik Industri">Teknik Industri</option>
            <option value="Teknik Lingkungan">Teknik Lingkungan</option>
        </select>

        <h2>Pilih Mata Kuliah Anda:</h2>
        <label for="Mata Kuliah">Pilih Mata Kuliah:</label>
        <select id="Mata Kuliah" name="Mata kuliah[]" multiple="multiple">
            <option value="Pemograman Web 1">Pemograman Web</option>
            <option value="Probabilitas dan Statistika">Probabilitas dan Statistika</option>
            <option value="Pemograman Mobile 1">Pemograman Mobile</option>
            <option value="Agama">Agama</option>
            <option value="Pemrograman Orientasi Objek">Pemrograman Orientasi Objek</option>
            <option value="Jaringan Komputer">Jaringan Komputer</option>
            <option value="Rekayasa Prangkat Lunak">Rekayasa Perangkat Lunak</option>
        </select>
    </fieldset>


    <style>
        form p > label {
        display: inline-block;
        width: 100px;
        }
        form input[type="text"], form textarea {
        border: 1px solid #197a43;
        }
        form input[type="submit"] {
        border: 1px solid #197a43;
        background-color: #197a43;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
        }
    </style>
    <input type="submit" value="Submit">
</form>
</body>
</html>
```
### Hasilnya
![Tugas Form](https://github.com/RizjkyDitoRidwansyah/Lab3Web/assets/116090827/77a5bca1-f9b4-4a39-b34b-9610b49762e1)
