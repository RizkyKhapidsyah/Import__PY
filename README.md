# Import__PY
Bahan Ajar Fundamental Pemrograman Python. Mengenal Penggunaan Import Untuk Menjadi Library Pada Program.<br><br>
<img src="https://github.com/RizkyKhapidsyah/Import__PY/blob/master/results/001.PNG"><br><br>
Lihat :<br>
- <a href="https://github.com/RizkyKhapidsyah/Import__PY/blob/master/Import__PY.py">Main Source Code.</a><br>
- <a href="https://github.com/RizkyKhapidsyah/Import__PY/blob/master/Module_Bagian1.py">Module Bagian 1.</a><br>
- <a href="https://github.com/RizkyKhapidsyah/Import__PY/blob/master/Module_Bagian2.py">Module Bagian 2.</a><br><br>

-----

Modul memungkinkan Anda mengatur kode Python secara logis. Mengelompokkan kode terkait ke dalam modul membuat kode lebih mudah dipahami dan digunakan. Modul adalah objek Python dengan atribut yang diberi nama yang bisa Anda bind dan dijadikan referensi. Secara sederhana modul adalah file yang terdiri dari kode Python. Modul dapat mendefinisikan fungsi, kelas dan variabel. Modul juga bisa menyertakan kode yang bisa dijalankan “runable”.

Berikut adalah contoh modul sederhana pada Python :

      def print_func( par ):
         print "Halo : ", par
         return

# Import Statement

Anda dapat menggunakan file sumber Python apapun sebagai modul dengan mengeksekusi pernyataan impor di file sumber Python lainnya. Impornya memiliki sintaks berikut. Ketika interpreter menemukan sebuah pernyataan import, ia mengimpor modul jika modul tersebut ada di jalur pencarian. Jalur pencarian adalah daftar direktori yang ditafsirkan juru bahasa sebelum mengimpor modul. Misalnya, untuk mengimpor modul hello.py, Anda perlu meletakkan perintah berikut di bagian atas script.

## Import module support

      import support

## Anda bisa memanggil fungsi defined sebagai berikut

      support.print_func("FunctionSaya")

# Modul

Modul adalah sebuah file yang berisi kode pemrograman python. Sebuah file yang berisi kode python, misalnya: example.py, disebut modul dan nama modulnya adalah example. Modul digunakan untuk memecah sebuah program besar menjadi file – file yang lebih kecil agar lebih mudah dimanage dan diorganisir. Modul membuat kode bersifat reusable, artinya satu modul bisa dipakai berulang dimana saja diperlukan. Modul tidak lain adalah program python biasa. Berikut ini kita mencoba membuat sebuah modul. Kita akan menyimpannya sebagai example.py

## Contoh Modul Python

      def jumlah(a, b):
          """Fungsi ini menambahkan dua bilangan
          dan mengembalikan hasilnya"""
         result = a + b
         return result

# Mengimpor Modul

Kita bisa mengimpor modul python ke dalam program yang kita buat. Dengan mengimpor modul, maka definisi, variabel, fungsi dan yang lainnya yang ada di dalam modul itu bisa kita pergunakan. Kita mengimpor modul dengan menggunakan kata kunci import. Misalnya, kita akan mengimpor modul example yang sudah kita buat di atas, maka kita bisa mengetikkan perintah berikut di IDLE maupun di command prompt.

<text> >>> import example</text>

Setelah kita import, maka kita bisa mengakses isi dari modul example. Kita bisa mengakses fungsi maupun variabel global di dalam modul dengan menggunakan operasi titik (.). Misalnya adalah sebagai berikut:

<text> >>> example.jumlah(5,6)</text>
11

Python memiliki banyak modul bawaan, misalnya modul math, os, sys dan lain sebagainya. Modul – modul tersebut berada di dalam direktori Lib ditempat Python terinstall. Python juga memiliki ribuan modul siap pakai yang tersedia luas di internet, salah satunya di pypi.python.org.

# Cara Lain Mengimpor Modul

Ada beberapa sintaks yang bisa digunakan untuk mengimpor modul, yaitu sebagai berikut:

- Cara import standard, formatnya <code>import module_name</code>
- Cara import dengan rename (alias), formatnya <code>import module_name as alias</code>
- Cara mengimport sebagian, formatnya <code>from...import something</code>
- Cara mengimport semua isi modul, formatnya <code>import *</code>

# Impor Module Dengan import

Kita bisa mengimpor modul menggunakan pernyataan import dan mengakses isinya dengan menggunakan operator titik. Berikut adalah contohnya:

Saat program di atas dijalankan, hasilnya adalah seperti berikut:

      # contoh statement menggunakan import 
      # import modul standar math 
      import math 
      print("Nilai pi adalah:", math.pi) 

Hasil:

> Nilai pi adalah: 3.141592653589793

# Impor Dengan Module Rename

Kita bisa mengimpor modul dengan menamainya. Hal ini biasanya kita lakukan untuk menyingkat nama modul yang panjang. Contohnya adalah sebagai berikut:

      import math as m
      print("Nilai pi adalah:",math.pi)

# Import Sebagian Menggunakan from ... import ...

Format from…import digunakan untuk mengimpor sebagaian isi modul dan bukan keseluruhan isi modul.

      from math import pi
      print("Nilai pi adalah", pi)

Kita juga bisa mengimpor beberapa atribut seperti contoh berikut:

      from math import pi, e
      pi

Hasil:

3.141592653589793

      e

Hasil:

2.718281828459045

# Import Semua Isi Modul Dengan import *

Bila kita menggunakan format import *, maka semua isi modul akan dimuat. Bedanya dengan format import standar adalah di sini kita dapat menggunakan semua isi modul tanpa menggunakan operator titik.

      from math import *<br>
      print("Nilai e adalah:", e)<br>
      
Hasil: 

> Nilai e adalah 2.718281828459045<br>

Catatan: Menggunakan import * bukan cara yang baik. Hal ini bisa menciptakan duplikasi nama pengenal dalam program dan bisa memicu bug (error).



-----
Referensi Artikel:<br>
- <a href="https://belajarpython.com">BelajarPython</a><br>
- <a href="https://www.pythonindo.com">PythonIndo</a><br>

<br>
Referensi Source Code:<br>
<a href="https://www.youtube.com/user/faqihzamukhlish"> Kelas Terbuka </a> dan <a href="https://github.com/kelasterbuka"> Kelas Terbuka (Repository)</a>. Created by <a href="https://github.com/faqihza">Faqihza Mukhlish.</a> Thanks To: <a href="https://www.youtube.com/channel/UCRGHjysoCemh4y7tCJQs30w/about">Faqihza Mukhlish.</a><br>

-----
All Source Code is Modified.

