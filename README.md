# iyen-ovita-marpaung
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Halaman HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #4CAF50;
        }
    </style>
</head>
<body>
    <h1>Selamat Datang Di Perpustakaan Iyen Ovita Marpaung!</h1>
    <p>Perkenalkan nama saya Iyen Ovita Marpaung, Nim 222201011 Program Studi D3 Perpustakaan Mata kuliah Pemrograman Web. Ini merupakan perpustakaan homepage pertama saya</p>

    <hr/>

    <h2>Berikut ini gambar dari Perpustakaan iain fattahul muluk papua</h2>
    <img src="https://belajargiat.id/wp-content/uploads/2019/08/profil-iain-papua-1024x576.jpg" >

    <h2>Tautan</h2>
    <p>Klik di sini untuk mengunjungi <a href="https://www.example.com" target="_blank">Example.com</a>.</p>

    <body>
  <h1>Contoh Video YouTube di HTML</h1>
  <iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/on_OgiR0iVk" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
  </iframe>
</body>

    <h2>Audio</h2>
    <audio controls>
        <source src="music.mp3" type="audio/mpeg">
        <source src="music.ogg" type="audio/ogg">
        Browser Anda tidak mendukung tag audio.
    </audio>
<body>
    <h2>Footer</h2>
    <footer>
        <p>&copy; 2024 Hak Cipta Dilindungi. Semua hak dilindungi.</p>
    </footer>
</body>
<h2>Formulir Perpustakaan iain fattahul muluk papua</h2>
    
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th>NIM</th>
                <td><input type="text" name="nim" required></td>
            </tr>
            <tr>
                <th>Alamat</th>
                <td><textarea name="alamat" rows="3" required></textarea></td>
            </tr>
            <tr>
                <th>Jenis Kelamin</th>
                <td>
                    <input type="radio" name="jenis_kelamin" value="Laki-laki" required> Laki-laki
                    <input type="radio" name="jenis_kelamin" value="Perempuan" required> Perempuan
                </td>
            </tr>
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No HP</th>
                <td><input type="text" name="no_hp" required></td>
            </tr>
            <tr>
                <th>Tempat Lahir</th>
                <td><input type="text" name="tempat_lahir" required></td>
            </tr>
            <tr>
                <th>Tanggal Lahir</th>
                <td><input type="date" name="tanggal_lahir" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
    </form>

</body>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabel Bahan Buku</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Daftar Bahan Buku</h1>
    <table>
        <thead>
            <tr>
                <th>No</th>
                <th>Judul Buku</th>
                <th>Pengarang</th>
                <th>Penerbit</th>
                <th>Tahun Terbit</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Pemrograman Web Dasar</td>
                <td>Andi Saputra</td>
                <td>Media Press</td>
                <td>2020</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Pengenalan HTML dan CSS</td>
                <td>Budi Santoso</td>
                <td>Ilmu Komputer</td>
                <td>2021</td>
            </tr>
            <tr>
                <td>3</td>
                <td>JavaScript untuk Pemula</td>
                <td>Siti Rahmawati</td>
                <td>Edu Books</td>
                <td>2019</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Database dan SQL</td>
                <td>Joko Widodo</td>
                <td>Tech Press</td>
                <td>2022</td>
            </tr>
        </tbody>
    </table>
</body>
<body>
<h2>Formulir Pemesanan Buku</h2>
    
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th>Nomor Anggota Perpustakaan</th>
                <td><input type="text" name="nomor anggota perpustakaan" required></td>
            </tr>
            <tr>
                <th>Tanggal Pemesanan</th>
                <td><textarea name="Tanggal Pemesanan" rows="3" required></textarea></td>
            </tr>
            <tr>
                <th>Jenis Kelamin</th>
                <td>
                    <input type="radio" name="jenis_kelamin" value="Laki-laki" required> Laki-laki
                    <input type="radio" name="jenis_kelamin" value="Perempuan" required> Perempuan
                </td>
            </tr>
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No HP</th>
                <td><input type="text" name="no_hp" required></td>
            </tr>
            <tr>
                <th>Penulis Buku</th>
                <td><input type="text" name="Penulis Buku" required></td>
            </tr>
            <tr>
                <th>No ISBN</th>
                <td><input type="date" name="no isbn" required></td>
            </tr>
             <tr>
                <th>Judul Buku Yang Dipesan</th>
                <td><input type="date" name="judul buku yang dipesan" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
    </form>

</body>
<body>
<h2>Formulir Perpanjangan Peminjaman Buku</h2>
    
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th><body>Nomor Anggota Perpustakaan</th>
                <td><input type="text" name="Nomor Anggota Perpustakaan" required></td>
            </tr>
            <tr>
                <th>Tanggal Peminjaman</th>
                <td><textarea name="Tanggal Peminjaman" rows="3" required></textarea></td>
            </tr>
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No HP</th>
                <td><input type="text" name="no_hp" required></td>
            </tr>
            <tr>
                <th>No ISBN</th>
                <td><input type="text" name="No ISBN" required></td>
            </tr>
            <tr>
                <th>Tanggal Perpanjangan Buku</th>
                <td><input type="date" name="tanggal_lahir" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
    </form>

</body>
</html>
