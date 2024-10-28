# Lab5Web
# Dita Tiara Putri (312310131)
# TI 23 A1

# 1. membuat dokumen HTML dengan nama file lab5_javascript.html   
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/e77dd2a9-42bb-483c-a8c0-33a78659e1f1)   

Tag ``<script>`` digunakan untuk menuliskan JavaScript yang menambahkan interaktivitas pada halaman, seperti ``document.write("Hello World")`` yang menampilkan teks secara langsung di halaman web dan ``console.log("Hello World")`` yang mencetak teks ke konsol browser untuk keperluan debugging atau pemeriksaan kode.   

# 2 Javascrip Dasar.   
Pemakaian Alert sebagai property window.   
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>alert box</title>
</head>
<body>
    <script language = "Javascript">
        window.alert("ini merupakan pesan untuk anda");
    </script>
</body>
</html>
```   
Kode HTML ini menggunakan JavaScript di dalam tag ``<script>`` untuk menampilkan alert box berisi pesan "ini merupakan pesan untuk anda" pada halaman web, yang muncul ketika halaman dimuat.   
![image](https://github.com/user-attachments/assets/7d234132-3fc5-4523-bcc7-606c3cd568ce)  

# 3 Pemakaian method dalam objek   
```sh   
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>skrip javascript</title>
</head>
<body>
    percobaan memakai javascript:<br>
    <script>
        document.write("selamat mencoba javascript<br>");
        document.write("semoga sukses");
    </script>
</body>
</html>
```
Kode ini menunjukkan cara dasar untuk menggunakan JavaScript untuk menghasilkan konten di halaman web dengan menggunakan metode ``document.write()``     
![image](https://github.com/user-attachments/assets/12f4ab45-7e0d-4306-9ece-ba5972cbe3bd) 

# 4 Pemakaian Prompt
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pemasukan data</title>
</head>
<body>
    <script language = "JavaScript">
<!--
    var nama = prompt("siapa nama anda?","masukkan nama anda");
    document.write("hai, "+ nama);
    //-->
    </script>
</body>
</html>
```
Kode ini menunjukkan cara menggunakan metode prompt() untuk mendapatkan input dari pengguna dan menampilkannya di halaman web dengan ``document.write()``   
![image](https://github.com/user-attachments/assets/506734c1-bcff-4c19-8017-8af7d9c4dfd1)   
![image](https://github.com/user-attachments/assets/174c5f85-1c0e-4155-aee1-6f29a260dab9)   
![image](https://github.com/user-attachments/assets/de0638b9-6785-41ac-aa05-adf9822f2b80)  

# 5 Pembuatan fungsi dan cara pemanggilannya   
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contoh program JavaScript</title>
    <script language = "JavaScript">
        function pesan(){
            alert ("memanggil javascript lewat body onload")
        }
        </script>
</head>
<body onload=pesan()>
</body>
</html>
```   
![image](https://github.com/user-attachments/assets/e9edd39b-b90a-4a20-b085-f7352307c204) 

# 6 Dasar Pemrograman Di Javascript
Operasi dasar aritmatika   
```sh   
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contoh program java JavaScript</title>
    <script language = "JavaScript">
    function test (val1,val2)
    {
        document.write("<br>"+"perkalian : val1*val2"+"<br>")
        document.write(val1*val2)
        document.write("<br>"+"pembagian : val1/val2"+"<br>")
        document.write(val1/val2)
        document.write("<br>"+"penjumlahan : val1+val2"+"<br>")
        document.write(val1+val2)
        document.write("<br>"+"pengurangan : val1-val2"+"<br>")
        document.write(val1-val2)
        document.write("<br>"+"modulus : val1%val2"+"<br>")
        document.write(val1%val2)
    }  
        </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
</body>
</html>
```
Kode ini mendemonstrasikan cara melakukan operasi dasar aritmatika menggunakan JavaScript dan menampilkan hasilnya di halaman web. Pengguna dapat mengklik tombol untuk menjalankan fungsi yang menghitung dan menampilkan hasil perkalian, pembagian, penjumlahan, pengurangan, dan modulus dari dua angka yang ditentukan (9 dan 4).   
![image](https://github.com/user-attachments/assets/b70b5249-9d62-4073-ac72-6fa2e3efa371)    
![image](https://github.com/user-attachments/assets/02c69446-6302-49fd-b8f0-912943c0a037) 

# 7 Seleksi kondisi ``(if..else)`` 
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contoh if-else</title>
</head>
<body>
    <script language = "JavaScript">
    <!--
    var nilai = prompt("nilai (0-100): ",0);
    var hasil = "";
    if (nilai >= 60)
    hasil = "lulus";
    else
    hasil = "tidak lulus";
    document.write("hasil:" + hasil);
        //-->
    </script>
</body>
</html>
```
Kode ini menunjukkan bagaimana menggunakan prompt untuk mengambil input dari pengguna, memeriksa kondisi menggunakan struktur ``if-else``, dan menampilkan hasilnya di halaman web. Jika pengguna memasukkan nilai 60 atau lebih, maka hasil yang ditampilkan adalah "lulus"; jika kurang dari 60, hasil yang ditampilkan adalah "tidak lulus".    
![image](https://github.com/user-attachments/assets/96e3762f-2bd2-4a18-8e52-6b47151148f9)   
![image](https://github.com/user-attachments/assets/32d05bb8-0694-4179-b6af-8455b48cf929)   
![image](https://github.com/user-attachments/assets/5f44a0cb-779b-4177-8165-76c344ca27b7)   
![image](https://github.com/user-attachments/assets/ab2af393-5fab-435d-9938-d4a1be1aa964) 

# 8 Penggunaan operator switch untuk seleksi kondisi 
```sh   
<!DOCTYPE html>
<html>
<head>
    <script language="javascript">
        function test() {
            let val = window.prompt("Input nilai (1-5):");
            switch (val) {
                case "1":
                    document.write("Bilangan satu");
                    break;
                case "2":
                    document.write("Bilangan dua");
                    break;
                case "3":
                    document.write("Bilangan tiga");
                    break;
                case "4":
                    document.write("Bilangan empat");
                    break;
                case "5":
                    document.write("Bilangan lima");
                    break;
                default:
                    document.write("Bilangan lainnya");
       }
}
</script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```   
Kode ini menunjukkan bagaimana menggunakan struktur ``switch`` untuk melakukan seleksi kondisi berdasarkan input pengguna. Pengguna diminta untuk memasukkan angka dari 1 hingga 5, dan berdasarkan input tersebut, pesan yang sesuai akan ditampilkan di halaman. Jika pengguna memasukkan nilai di luar rentang yang ditentukan, maka akan ditampilkan pesan "Bilangan lainnya".   
![image](https://github.com/user-attachments/assets/c4108264-f1be-4761-b101-ddd9b7045220)   
![image](https://github.com/user-attachments/assets/cd239f32-599c-402d-8e8e-b64e8a036272)   
![image](https://github.com/user-attachments/assets/e4eca6b6-c28e-4d33-a75b-30efcfca676e)   
![image](https://github.com/user-attachments/assets/846cc41b-bb7d-4d37-bc6a-4450e71886f8)   
![image](https://github.com/user-attachments/assets/667695f6-cef3-4d6b-be0b-039c4ec9d9bb)  

# 9 Pembuatan Form 
Form Input   
```sh
<html>
<head>
    <title>contoh if-else</title>
    <script language="javascript">
    function test() {
        var val1 = document.kirim.T1.value; 
        if (val1 % 2 == 0)
            document.kirim.T2.value = "bilangan genap"; 
            document.kirim.T2.value = "bilangan ganjil"; 
    }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BILANGAN <input type="text" name="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" size="20" readonly></p>
        <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p>
    </form>
</body>
</html>
```
Kode ini adalah contoh sederhana untuk menggunakan JavaScript dalam mengolah input pengguna dan memberikan umpan balik langsung. Ini memperlihatkan penggunaan struktur kontrol ``if-else`` dan interaksi dasar dengan DOM melalui formulir HTML.   
![image](https://github.com/user-attachments/assets/8270507a-7be4-469f-8391-e69e567946c6)   
![image](https://github.com/user-attachments/assets/9393c835-af8b-472d-8722-e93a275c5cc5)   
![image](https://github.com/user-attachments/assets/2c10231d-1114-46de-9a18-58f8b02180d2)   
![image](https://github.com/user-attachments/assets/86ef0f70-cad5-489e-a67e-414289373075)  

# 10 Form Button. 
```sh
<!DOCTYPE html>
<html>
<head>
    <title>objek document</title>
    <style>
        body {
            background-color: white; 
            color: black; 
        }
    </style>
    <script language="javascript">
        function ubahWarnaLB(warna) {
            document.body.style.backgroundColor = warna; 
        }
        
        function ubahWarnaLD(warna) {
            document.body.style.color = warna; 
        }
    </script>
</head>
<body>
    <h1>tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>
    <script language="javascript">
        document.write("Dimodifikasi terakhir pada " + document.lastModified);
    </script>
</body>
</html>
```   
Saya menggunakan ``document.body.style.backgroundColor = warna;``. Fungsi ini mengubah warna latar belakang halaman dengan menggunakan document.bgColor = warna;. Ini akan berfungsi dengan baik.   
Fungsi ini berusaha mengubah warna teks dengan menggunakan ``document.fgColor`` = warna;. Namun, karena ``fgColor`` tidak didukung di banyak browser modern, tidak ada efek yang terlihat.   
Ketika tombol untuk mengubah latar belakang ditekan, fungsi ``ubahWarnaLB`` dipanggil dengan parameter warna yang sesuai. Fungsi ini akan mengubah warna latar belakang halaman.   
Saat tombol untuk mengubah warna teks ditekan, fungsi ``ubahWarnaLD`` dipanggil, yang mengubah warna teks halaman sesuai dengan warna yang dipilih.   

![image](https://github.com/user-attachments/assets/1255333b-4165-402a-b38b-25911f04d2c8) 
![image](https://github.com/user-attachments/assets/7b7a2954-46f5-4d53-9af4-81ac8fee211d) 
![image](https://github.com/user-attachments/assets/59a086d3-3a9a-48a6-adb0-bbfe9734efb6) 
![image](https://github.com/user-attachments/assets/edb00674-81f6-4320-a75a-eefef6e089e3) 
![image](https://github.com/user-attachments/assets/0ac54abb-0f71-4895-8c33-3fe649a80900) 

# 11 HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis
```sh
<!--
File: daftar_menu.html
-->
<html>
<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
            var total = document.getElementById('total').value;
            total = (total ? parseInt(total) : 0);
            var harga = 0;

            if (ele.checked) {
                harga = ele.value;
                total += parseInt(harga);
            } else {
                harga = ele.value;
                if (total > 0)
                    total -= parseInt(harga);
            }

            document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"> Ayam Goreng Rp. 5.000</label><br />
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"> Tempe Goreng Rp. 500</label><br />
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"> Telur Dadar Rp. 2.500</label><hr />
    <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
</body>
</html>
```
Pengguna dapat mencentang atau menghapus centang pada pilihan menu makanan.   
Setiap kali sebuah checkbox diklik, fungsi ``hitung()`` akan menghitung total harga berdasarkan menu yang dipilih.  
Hasil perhitungan akan ditampilkan dalam input ``Total Bayar``, memberikan pengguna gambaran jelas tentang total belanja mereka.   

![image](https://github.com/user-attachments/assets/e85bed5a-0654-47aa-83e6-aa4c52ecbfe4) 
![image](https://github.com/user-attachments/assets/b145780c-8c20-41e4-b3ad-610167db0641) 

# TUGAS 
1. Buat script untuk melakukan validasi pada isian form.
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Validasi Form</title>
    <script>
        function validateForm() {
            var name = document.getElementById("name").value;
            var email = document.getElementById("email").value;
            var emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/; 

            if (name === "") {
                alert("Nama tidak boleh kosong.");
                return false; 
            }

            if (!emailPattern.test(email)) {
                alert("Masukkan email yang valid.");
                return false; 
            }

            alert("Form berhasil disubmit!");
            return true; 
        }
    </script>
</head>
<body>
    <h1>Form Pendaftaran</h1>
    <form onsubmit="return validateForm()">
        <label for="name">Nama:</label><br>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label><br>
        <input type="text" id="email" name="email"><br><br>
        <input type="submit" value="Daftar">
    </form>
</body>
</html>
```
``<form onsubmit="return validateForm()">``: Menghubungkan form dengan fungsi validasi saat disubmit. Jika fungsi mengembalikan false, form tidak akan dikirim.   
``var emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/``; Pola regex untuk validasi email
HTML Struktur Form:   
Terdapat dua input: satu untuk nama dan satu untuk email.   
Form menggunakan atribut ``onsubmit`` untuk memanggil fungsi validasi saat disubmit.   
Fungsi Validasi (validateForm):   
Mengambil nilai dari input nama dan email.   
Memeriksa apakah nama kosong. Jika kosong, menampilkan peringatan dan menghentikan pengiriman form.   
Menggunakan regex untuk memeriksa format email. Jika format tidak valid, menampilkan peringatan dan menghentikan pengiriman form.   
Jika semua validasi berhasil, menampilkan pesan sukses dan mengizinkan pengiriman form.   
![image](https://github.com/user-attachments/assets/081240cf-b6f7-412c-a845-ea9048f42a36)
![image](https://github.com/user-attachments/assets/0ca076a5-2c84-4983-971e-5114b95fab57) 
![image](https://github.com/user-attachments/assets/7af95b1d-cfef-4a0e-811c-923138858911) 











































