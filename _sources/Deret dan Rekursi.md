---
title: Deret dan Rekursi

---


# Deret dan Rekursi
## Pengertian Deret 
Deret adalah jumlah suku-suku dari suatu barisan. Barisan dan deret "hingga" mempunyai elemen pertama dan terakhir yang terdefinisi, sedangkan barisan dan deret "tak terhingga" berlangsung terus menerus tak terbatas.
### 1. Deret Aritmatika
Deret aritmatika (Sn) merupakan jumlah suku ke-n dalam barisan aritmatika. Pada dasarnya, barisan aritmatika adalah barisan bilangan sedemikian rupa sehingga selisih antara suku-suku yang berurutan tetap. Sementara deret aritmatika dapat dideskripsikan sebagai jumlah keseluruhan dari suku-suku yang ada pada barisan aritmatika.
##### Rumus Deret Aritmatika
![Cuplikan layar 2024-12-01 084124](https://hackmd.io/_uploads/ryE8Llc71e.png)
![Cuplikan layar 2024-12-01 084253](https://hackmd.io/_uploads/By0DUecXke.png)


![Screenshot 2024-11-24 234249](https://hackmd.io/_uploads/r1BswRe7kg.png)
Keterangan:
Sn adalah jumlah n suku pertama deret aritmatika
Un adalah suku ke-n deret aritmatika
a adalah suku pertama
b adalah beda
n adalah banyaknya suku


### 2. Deret Geometri
Deret geometri dapat disebut sebagai jumlah dari barisan bilangan yang suku-sukunya membentuk barisan geometri, sehingga deret geometri mudah untuk dibedakan dari yang lainnya.

Pada deret geometri, suku-sukunya memiliki rasio yang tetap. Rasio adalah perbandingan antar suku-suku pada deret tersebut.
Misalnya perbandingan antara suku kedua dengan suku pertama akan sama dengan suku ketiga dengan suku kedua, begitu pula yang lainnya.
##### Rumus Deret Geometri
Deret geometri disimbolkan dengan Sn. Deret geometri dapat dirumuskan sebagai:

![Screenshot 2024-11-24 233000](https://hackmd.io/_uploads/r1GsVRlQyl.png)
![image](https://hackmd.io/_uploads/BJ3eO0eQJe.png)

Keterangan:

Sn : jumlah suku pada deret geometri
a : suku pertama pada deret geometri
r : rasio pada deret geometri
n : banyaknya suku pada deret geometri

Dan adapun juga deret geometri tak hingga.


### Deret Geometri Tak Hingga
Deret geometri tak hingga merupakan deret geometri yang memiliki tak hingga banyak suku atau banyak sukunya mendekati tak hingga (infinite). Perhatikan contoh deret geometri tak hingga berikut.
![Screenshot 2024-11-24 233358](https://hackmd.io/_uploads/HyT5B0gm1g.png)

Deret tersebut memiliki rasio yang tetap yaitu r = 1/3 dan memiliki tak hingga banyak suku sehingga disebut sebagai deret geometri tak hingga.

Untuk menentukan jumlah suku dari deret geometri tak hingga dapat menggunakan rumus deret geometri tak hingga berikut ini.
![Screenshot 2024-11-24 233408](https://hackmd.io/_uploads/BkCiH0gQyg.png)
Keterangan:


S∞ : jumlah suku pada deret geometri tak hingga
a : suku pertama deret geometri tak hingga
r : rasio deret geometri tak hingga

### Jenis Barisan Lainnya
Selain kedua jenis barisan dasar di atas, ada juga jenis barisan lainnya sebagai berikut.

### 1. Barisan Bilangan Kuadratik
Angka dalam barisan bilangan kuadratik nilainya berupa hasil kuadrat nilai n. Contoh : 1, 4, 9, 16, 25, 36, … sehingga U10 = (10)2 = 100.
### 2. Barisan Bilangan Segitiga
Beda suku-suku barisannya memiliki pertambahan nilai tertentu.
Contoh : 3, 6, 10, 15, 21 dimana 6-3 = 3, 10-6 =4, 15-10 = 5, artinya nilai b bertambah 1 setiap kenaikan satu tingkat.
Contoh : 4, 6, 10, 16, 24 dengan besarnya pertambahan nilai b adalah 2.
### 3. Barisan Fibonacci
Merupakan nama untuk barisan khusus dimana besarnya Un adalah penjumlahan 2 (dua) angka sebelumnya.
Barisan Fibonacci = 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, … Un.
### 4. Barisan Campuran
Dimana selisih antara suku-sukunya memiliki beda (b) serta rasio.
Contoh : 2, 9, 30, 93, 282 dimana 282 = 3(93) + 3, 93 = 3(30) + 3, sehingga diperoleh r = 3 sedangkan b = 2.

## Rekursi
### Pengertian Rekursi
Rekursi adalah suatu proses dengan salah satu langkah dalam prosedur tersebut menjalankan prosedur itu sendiri. Prosedur yang melakukan rekursi disebut dengan 'rekursif'.

### Teorema Rekursi
Dalam teori himpunan, ini adalah teorema yang menjamin bahwa fungsi yang terdefinisi secara rekursif itu ada. Diberikan suatu himpunan X, sebuah elemen a dari X dan sebuah fungsi f:X→X, teorema menyatakan bahwa ada fungsi unik F:N→X
(dengan N menunjukkan himpunan dari bilangan asli termasuk nol) sehingga:
![Screenshot 2024-11-24 235500](https://hackmd.io/_uploads/BJ_dqAl7kl.png)
untuk setiap bilangan asli n.
#### Pembuktian Keunikan 
Ambil dua fungsi F:N→X dan G:N→X sehingga:
![Screenshot 2024-11-24 235633](https://hackmd.io/_uploads/HJo-sAlQke.png)
dengan a adalah elemen dari X.
Ia dapat dibuktikan dengan induksi matematika bahwa F(n) = G(n) untuk semua bilangan asli _n_

**Kasus Dasar :** _F_(0) = a = _G_(0)sehingga persamaan memenuhi untuk **n = 0**
**Langkah Induktif :** Misalkan F(k) = G(k) untuk beberapa k elemen _N_. Maka F(k+1) = f(F(k)) = f(G(k)) = G(k+1)
Karena F(k) = G(k) menyiratkan F(k+1) = G(k+1)
Dengan induksi, F(n) = G(n) untuk semua n elemen N

#### Beberapa relasi perulangan umum yaitu:
![Screenshot 2024-11-25 001154](https://hackmd.io/_uploads/B16w0RlQkx.png)

https://id.wikipedia.org/wiki/Deret_(matematika)
https://www.detik.com/edu/detikpedia/d-6019213/deret-aritmatika-rumus-contoh-soal-dan-bedanya-dengan-barisan
https://rumuspintar.com/deret-geometri/
https://www.kursiguru.com/contoh-soal-deret-dan-barisan/
https://id.wikipedia.org/wiki/Rekursi

# TUGAS Pembuktian dari 3 Rumus

### Soal no. 2
![Screenshot 2024-11-25 001406](https://hackmd.io/_uploads/ryieykWXye.png)
##### Penyelesaian : 
- Ruas kanan 
![Screenshot 2024-11-25 002623](https://hackmd.io/_uploads/S1DlGJWQyg.png)
- Ruas kiri
![Screenshot 2024-11-25 002637](https://hackmd.io/_uploads/r1jGGy-m1x.png)


### Soal no. 3
![Screenshot 2024-11-25 001618](https://hackmd.io/_uploads/SkYOky-m1e.png)
##### Penyelesaian : 
- Ruas kanan
![Screenshot 2024-11-25 003417](https://hackmd.io/_uploads/SkPkVkb71g.png)
- Ruas kiri
![Screenshot 2024-11-25 003440](https://hackmd.io/_uploads/HJceVyWQ1l.png)