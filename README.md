# Lab9Web

## Langkah-langkah Praktikum

### **Buat file baru dengan nama header.php*
```php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
    </nav>
```

### *Buat file baru dengan nama footer.*php
```php
<footer>
<p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
</footer>
</div>
</body>
</html>
```

### *Buat file baru dengan nama home.*php
```php
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

### *Buat file baru dengan nama about.php*
```php
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

## *Hasil OUTPUT*
![image](https://github.com/ZahraNurhaliza/Lab9Web/blob/main/screenshot/ss.1.png)



## Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang
database, sehingga setiap halamannya memiliki template tampilan yang sama. 

*HOME
![image](https://github.com/ZahraNurhaliza/Lab9Web/blob/main/screenshot/ss.2.png)


*UBAH*
![image](https://github.com/ZahraNurhaliza/Lab9Web/blob/main/screenshot/ss.3.png)


*HAPUS*
![image](https://github.com/ZahraNurhaliza/Lab9Web/blob/main/screenshot/ss.4.png)

## SELESAI