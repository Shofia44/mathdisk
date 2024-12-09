---
title: Algoritma

---

# Algoritma
## Definisi Algoritma

Algoritma adalah metode atau langkah yang direncanakan secara tersusun dan berurutan untuk menyelesaikan permasalahan dengan sebuah intruksi atau kegiatan.

Algoritma dipelajari secara abstrak, terlepas dari sistem komputer atau bahasa pemrograman yang dipergunakan.

### Algoritm sequential Search
Sequential search adalah teknik pencarian data yang dilakukan dengan cara membandingkan setiap elemen data satu per satu, mulai dari elemen pertama hingga elemen yang dicari ditemukan. Proses ini terus berlanjut hingga data ditemukan atau seluruh elemen telah diperiksa.

Sequential Search bekerja dengan melakukan perhitungan satu persatu secara beruntun dalam kumpulan data dengan data yang dicari sampai data tersebut ditemukan atau tidak ditemukan.

### Algoritm Binary Search
Binary Search merupakan algoritma pencarian yang membagi data menjadi dua bagian dan mencari elemen yang dicari di salah satu bagian tersebut. Algoritma ini mengasumsikan bahwa data sudah terurut, entah itu dalam urutan menaik atau menurun.

Jika elemen yang dicari lebih besar dari elemen tengah data, maka pencarian dilanjutkan ke bagian kanan data. Sebaliknya, jika elemen yang dicari lebih kecil dari elemen tengah, pencarian dilanjutkan ke bagian kiri data. Proses ini diulangi sampai elemen yang dicari ditemukan atau seluruh data telah diperiksa.
## Pseudocode 
Pseudocode adalah cara penulisan kode algoritma menggunakan bahasa umum yang digunakan sehari-hari sehingga lebih mudah dipahami.
Biasanya bahasa yang digunakan dalam pseudocode adalah bahasa Inggris sederhana, tapi bisa juga dengan bahasa Indonesia atau bahasa lain. Tujuannya agar siapapun yang tidak memiliki latar belakang programming bisa memahami sebuah program dan menjalankannya dengan benar.
## Big O algoritma
Big-O Notation adalah sebuah cara atau metode untuk melakukan analisa terhadap sebuah algoritma pemrograman terhadap waktu eksekusi. Tentang seberapa efisien dan kompleksitas barisan kode dalam dimensi waktu.

Notasi Big-O bergantung pada ukuran input, jumlah loop, dan loop dalam. Notasi ini dapat digunakan untuk menganalisis kecepatan algoritma dengan tujuan membuat fungsi yang lebih efisien.
## Hitung Big O dar Algoritm sequential search

* Waktu kompleksitas (time komplexity)
* Ruang kompleksitas (space komplexity)

Sejauh ini, kita hanya membahas kompleksitas waktu dari algoritma. Artinya, kita hanya peduli tentang berapa banyak waktu yang dibutuhkan program untuk menyelesaikan tugas. Yang juga penting adalah ruang yang dibutuhkan program untuk menyelesaikan tugas. Kompleksitas ruang terkait dengan berapa banyak memori yang akan digunakan program, dan karenanya juga merupakan faktor penting untuk dianalisis.

Kompleksitas ruang bekerja mirip dengan kompleksitas waktu. Misalnya, sortir pilihan memiliki kompleksitas ruang O(1), karena hanya menyimpan satu nilai minimum dan indeksnya untuk perbandingan, ruang maksimum yang digunakan tidak bertambah seiring dengan ukuran input.

Beberapa algoritme, seperti bucket sort, memiliki kompleksitas ruang O(n), tetapi mampu memangkas kompleksitas waktu menjadi O(1). Bucket sort mengurutkan array dengan membuat daftar yang diurutkan dari semua elemen yang mungkin dalam array, lalu menambah jumlahnya setiap kali elemen tersebut ditemukan. Pada akhirnya array yang diurutkan akan menjadi elemen daftar yang diurutkan yang diulangi jumlahnya.