---
title: Aljabar Boolean dan Gerbang Logika

---

## Aljabar Boolean

Aljabar Boolean menggunakan tiga operasi dasar:
   - *NOT (Negasi)*: Mengubah nilai logika, dari benar menjadi salah, dan sebaliknya. Dilambangkan dengan garis di atas variabel (misalnya, \(\overline{A}\)).
   - *AND (Konjungsi)*: Operasi yang menghasilkan benar hanya jika kedua operand bernilai benar. Simbol yang digunakan adalah titik (A·B atau AB).
   - *OR (Disjungsi)*: Menghasilkan benar jika salah satu atau kedua operand bernilai benar. Simbol yang digunakan adalah \(+\) (A + B).

Beberapa identitas dasar dari aljabar Boolean meliputi:
   - *Identitas (Identity)*: A + 0 = A dan A·1 = A
   - *Komplementasi (Complementation)*: A + \(\overline{A}\) = 1 dan A·\(\overline{A}\) = 0
   - *Asosiatif (Associative)*: (A + B) + C = A + (B + C)
   - *Komutatif (Commutative)*: A + B = B + A
   - *Distribusi (Distributive)*: A·(B + C) = (A·B) + (A·C)

*3. Gerbang Logika*

Gerbang logika adalah komponen dasar dari sirkuit digital yang digunakan untuk melakukan operasi logika Boolean. Ada beberapa jenis gerbang logika yang digunakan dalam sirkuit digital:

   - *Gerbang NOT*: Gerbang ini menghasilkan output yang merupakan kebalikan dari input. Jika input adalah 1, output akan 0, dan sebaliknya.
   - *Gerbang AND*: Menghasilkan output 1 hanya jika semua inputnya adalah 1. Jika salah satu input adalah 0, maka output akan 0.
   - *Gerbang OR*: Menghasilkan output 1 jika salah satu inputnya adalah 1. Jika semua input adalah 0, outputnya akan 0.
   - *Gerbang NAND (NOT AND)*: Adalah negasi dari AND. Outputnya akan 0 jika semua inputnya 1, dan outputnya 1 jika ada satu input 0.
   - *Gerbang NOR (NOT OR)*: Adalah negasi dari OR. Outputnya adalah 1 hanya jika semua inputnya adalah 0.
   - *Gerbang XOR (Exclusive OR)*: Menghasilkan output 1 hanya jika jumlah input bernilai benar ganjil. Jika jumlah input benar genap, outputnya 0.
   - *Gerbang XNOR (Exclusive NOR)*: Adalah kebalikan dari XOR, menghasilkan output 1 jika jumlah input bernilai benar genap.

*4. Aplikasi Aljabar Boolean dan Gerbang Logika*

Dalam dunia digital, gerbang logika digunakan untuk mendesain sirkuit yang dapat melakukan operasi perhitungan, pengendalian, dan penyimpanan data. Sirkuit kombinasi seperti multiplexer, demultiplexer, encoder, dan decoder semua dibangun dengan menggunakan gerbang logika.

Contoh praktis lainnya adalah dalam desain prosesor komputer, di mana operasi aritmatika, logika, dan memori diimplementasikan menggunakan kombinasi gerbang logika untuk memproses bit-bit data. Selain itu, aljabar Boolean digunakan dalam analisis rangkaian, seperti dalam pemrograman mikrokontroler dan perancangan algoritma logika.

