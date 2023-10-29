# Lab5Web

| Nama                            | NIM       | 
| :--------                       | :-------  |
| Maulana Zidan Perdana           | 312210463 |

<h2>Instruksi Praktikum</h2>

1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab5_javascript.
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
4. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

<h1>Pertanyaan dan Tugas</h1>

<h2>Buat Script untuk Melakukan Validasi pada Isian Form.</h2>

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/3d5e62ec-1219-4bb2-90ec-49a5357fc126)

<h1>Langkah-Langkah Praktikum</h1>
<h2>Persiapan Membuat Dokumen HTML dengan Nama File lab5_javascript.html</h2>

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

Hasilnya:

![Screenshot 2023-10-27 203605](https://github.com/GilarSumilar/Lab5Web/assets/116040175/61d0cf6f-bb03-498c-8113-be09846589a3)

<h1>Javascrip Dasar</h1>
<h2>Pemakaian Alert sebagai Property Window</h2>

    <!DOCTYPE html>
    <html> 
      <head>
        <title>Alert Box</title>    
      </head>
      <body>
        <script language = "javascript">
        <!--Pemakaian Alert-->
            window.alert("This is a Message for You!!!")
        </script>
      </body>
    </html>
Berikut adalah hasilnya:

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/5e54ad42-856c-443c-a1b9-dc3fee34e506)

<h2>Pemakaian Method dalam Objek</h2>

    <!DOCTYPE html>
    <html>
        <head>
            <title>Skrip JavaScript</title>
        </head>
        <body>
            Percobaan memakai javascript:<br>
            <script language = "javascript">
                document.write("Good luck trying JavaScript<br>");
                document.write("Good luck:)!");
            </script>
        </body>
    </html>
    
Inilah hasilnya:

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/270b5e9b-7c37-4a72-9a46-ea18c22fa691)

<h2>Pemakaian Prompt</h2>

    <!DOCTYPE html>
    <html>
      <head>
        <title>pemasukan data</title>
      </head>
      <body>
        <script language = "javascript">
            var nama = prompt("What is Your Name?", "Enter Your Name");
            document.write("Hey, " + nama);
        </script>
      </body>
    </html>

Seperti ini tampilan dalam web nya:

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/0a4e4d59-91f4-4f4c-be6e-b15a1a4fb07a)

Setelah memasukkan nama

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/6e3f6071-83f0-4119-b47f-57f72f7029ea)

Akan tampil seperti ini

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/a14701ad-74fb-485e-98d5-6671dc65c089)

<h2>Pembuatan Fungsi dan Cara Pemanggilannya</h2>

    <!DOCTYPE html>
    <html>
      <head>
      <title>Contoh Program JavaScript</title>
      <script language = "javascript">
        function pesan(){
            alert("Calling JavaScript Via Body Onload")
        }
      </script>
      </head>
      <body 
        onload=pesan()>    
      </body>
    </html>

Tampilan di Web nya:

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/9e93fdc6-6208-4de0-a392-1cf239f0e8a7)

<h1>Dasar Pemrograman Di Javascript</h1>
<h2>Operasi Dasar Aritmatika</h2>

    <!DOCTYPE html>
    <html>
      <head>
        <title>Contoh Program JavaScript</title>
        <script language = "javascript">
          function test (val1, val2){
            document.write("<br>" + "multiplication : val1 * val2" + "<br>")
            document.write(val1*val2)
            document.write("<br>" + "distribution : val1 / val2" + "<br>")
            document.write(val1/val2)
            document.write("<br>" + "summation : val1 + val2" + "<br>")
            document.write(val1+val2)
            document.write("<br>" + "subtraction : val1 - val2" + "<br>")
            document.write(val1-val2)
            document.write("<br>" + "modulus : val1 % val2" + "<br>")
            document.write(val1%val2)
          }
        </script>
      </head>
      <body>
        <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
      </body>
    </html>

Tampilan dalam Webnya:

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/da9f5954-0b6d-46c7-9a07-928f9e24a5fe)

<h2>Seleksi Kondisi (If..Else)</h2>

    <!DOCTYPE html>
    <html>
      <head>
        <title>Condition Selection If-Else</title>
      </head>
      <body>
        <script language="javascript">
          var mark = prompt("mark (0-100): ", 0);
          var results = "";
          if (mark >= 60)
          results = "passed";
          else
          results = "not pass";
          document.write("results: " + results);
        </script>
      </body>
    </html>

Berikut tampilan di Web nya:
Jikalau nilai dibawah 60

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/3892f650-ed43-430c-bb5e-46823b873711)

akan di anggap tidak lulus

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/3d5f0d9b-61f5-45bc-9e93-db300a7515dd)

Dan apabila nilai diatas 60

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/a026abaa-f4f0-4e56-9199-15e4083a38d4)

Akan di anggap lulus

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/1decd030-ba2f-4008-930c-19e99530500e)

<h2>Penggunaan Operator Switch untuk Seleksi Kondisi</h2>

    <!DOCTYPE html>
    <html>
      <head>
        <title>Contoh Program JavaScript</title>

        <script language = "javascript">
          function test ()
          {
            val1 = window.prompt("Value Input (1-5)")
            switch (val1)
            {
                case "1" : 
                    document.write("Number One")
                    break
                case "2" : 
                    document.write("Number Two")
                    break
                case "3" : 
                    document.write("Number Three")
                    break
                case "4" : 
                    document.write("Number Four")
                    break
                case "5" : 
                    document.write("Number Five")
                    break
                default : 
                    document.write("Other Numbers")
             }
          }
        </script>
      </head>
      <body>
        <input type="button" name="button1" value="switch" onclick=test()>
      </body>
    </html>
    
Berikut adalah hasilnya:

Jikalau kita menulis angka 1-5

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/62023c8f-fca2-499b-870f-248cd75d4693)

Maka Web akan membaca karena sudah dimasukkan input nya

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/c523d06d-b178-46a2-92ae-8d0935159068)

Ketika memasukkan angka di atas 5

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/b60cf800-31b7-454b-bd56-140fb520054b)

Maka akan keluar

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/7202ab92-8579-4ca3-8a60-8395162c8050)

<h1>Pembuatan Form</h1>
<h2>Form Input</h2>

    <!DOCTYPE html>
    <html>
      <head>
        <title>Form Input</title>

        <script language="javascript">
            function test () {
              var val1 = document.kirim.T1.value
              if (val1%2==0)
                document.kirim.T2.value = "Even Number"
              else   
                document.kirim.T2.value = "Odd Numbers"
            }
          </script>
        </head>
        <body>
          <form method="POST" name="kirim">
            <p>NUMBER <input type="text" name="T1" size="20">
            IS A NUMBER <input type="text" name="T2" size="20"></p>
            <p><input type="button" name="B1" value="GUESS" onclick=test()></p>
          </form>
        </body>
      </html>

Jikalau memasukkan angka ganjil

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/c6aef8b0-2bc4-426c-a4fb-3626fa016807)

Jikalau memasukkan angka genap

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/4bc7d900-c53f-46a0-bd6d-31df76c6cdb7)

<h2>Form Button</h2>

    <!DOCTYPE html>
    <html>
      <head>
          <title>Objek Document</title>
      </head>
      <body>
          <script language="JavaScript">
            <!--
            function ubahWarnaLB(warna) {
              document.bgColor = warna;
            }
            function ubahWarnaLD(warna) {
              document.fgColor = warna;
            }
            //
            -->
          </script>

          <h1>Tes</h1>
          <form>
            <input type="button" value="Green Background" onClick="ubahWarnaLB('GREEN')">
            <input type="button" value="White Background" onClick="ubahWarnaLB('WHITE')">
            <input type="button" value="Yellow Text" onClick="ubahWarnaLD('YELLOW')">
            <input type="button" value="Blue Text" onClick="ubahWarnaLD('BLUE')">
          </form>
          <script language="JavaScript">
            <!--
            document.write("Dimodifikasi terakhir pada " +
              document.lastModified);
            //
            -->
          </script>
        </body>
      </html>

Seperti ini hasilnya:

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/380455ba-86f4-431c-ade7-2543227b70cc)


<h1>HTML DOM</h1>
<h2>Pilihan menggunakan checkBox dengan perhitungan otomatis</h2>

    <!DOCTYPE html>
    <html>
      <head>
        <title>Menu List</title>
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
          <h1>Food Menu</h1>
          <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />Fried Chicken Rp. 5.000</label><br />
          <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />Fried Tempe Rp. 500</label><br />
          <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />Tempe Omelette Rp. 2.500</label><br />
          <strong>Total Payment: Rp. <input id="total" type="text" /></strong>
      </body>
    </html>

Berikut Hasilnya:

![image](https://github.com/zidanperdana/Lab5Web/assets/116040175/1eb42103-c9be-40f1-a175-b66159590fdd)
