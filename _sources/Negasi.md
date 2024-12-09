---
title: Negasi

---


## Negasi
Negasi adalah penyangkalan, peniadaan, atau kata sangkalan seperti kata 'tidak' dan 'bukan'. Istilah negasi digunakan dalam sejumlah bidang, antara lain bahasa dan matematika.


kalimat negasi adalah kalimat negatif yang disusun dengan menambahkan kata tidak, belum, bukan, tanpa, dan jangan.

| Pernyataan ( p) | Negasi ($\neg p$)     |
|----------------|------------------|
| Benar (True)   | Salah (False)    |
| Salah (False)  | Benar (True)     |





## Konjungsi

Konjungsi adalah operasi logika yang menghasilkan nilai benar hanya jika kedua pernyataan yang terlibat bernilai benar. Dalam simbol logika, konjungsi dilambangkan dengan simbol "$\wedge$" (dan). Misalnya, jika p dan q adalah dua pernyataan, maka konjungsi dari p dan q ditulis sebagai "$p \wedge q$".

**Tabel Konjungsi:**

| Pernyataan ( p) | Pernyataan (q) | Konjungsi ($p  \wedge q$)  |
|----------------|----------------|--------------------|
| Benar (True)   | Benar (True)   | Benar (True)       |
| Benar (True)   | Salah (False)  | Salah (False)      |
| Salah (False)  | Benar (True)   | Salah (False)      |
| Salah (False)  | Salah (False)  | Salah (False)      |


## Disjungsi
Disjungsi adalah operasi logika yang menghasilkan nilai benar jika salah satu atau kedua pernyataan yang terlibat bernilai benar. Dalam simbol logika, disjungsi dilambangkan dengan simbol "$\vee$" (atau). Misalnya, jika p dan q adalah dua pernyataan, maka disjungsi dari p dan q ditulis sebagai "$p\ \vee q$".

**Tabel Disjungsi:**

| Pernyataan (p ) | Pernyataan (q) | Disjungsi ($p\ \vee q$) |
|----------------|----------------|-------------------|
| Benar (True)   | Benar (True)   | Benar (True)      |
| Benar (True)   | Salah (False)  | Benar (True)      |
| Salah (False)  | Benar (True)   | Benar (True)      |
| Salah (False)  | Salah (False)  | Salah (False)     |

## Implikasi
Implikasi adalah operasi logika yang menyatakan hubungan sebab-akibat antara dua pernyataan. Implikasi bernilai salah hanya jika pernyataan pertama (p ) benar dan pernyataan kedua (q) salah. Dalam simbol logika, implikasi dilambangkan dengan simbol "$\to$". Implikasi dari p ke q ditulis sebagai "$p \to\ q$", yang berarti "jika p maka q".

**Tabel Implikasi:**

| Pernyataan ( p) | Pernyataan (q) | Implikasi ($p \to\ q$) |
|----------------|----------------|-------------------|
| Benar (True)   | Benar (True)   | Benar (True)      |
| Benar (True)   | Salah (False)  | Salah (False)     |
| Salah (False)  | Benar (True)   | Benar (True)      |
| Salah (False)  | Salah (False)  | Benar (True)      |


## Biimplikasi
Bi-implikasi adalah operasi logika yang menyatakan bahwa dua pernyataan memiliki nilai kebenaran yang sama (keduanya sama benar atau sama salah). Bi-implikasi dilambangkan dengan simbol "↔". Bi-implikasi dari p dan q ditulis sebagai "p ↔ q", yang berarti "p jika dan hanya jika q".

**Tabel Bi-Implikasi:**

| Pernyataan (p ) | Pernyataan (q) | Bi-Implikasi (p ↔ q) |
|----------------|----------------|----------------------|
| Benar (True)   | Benar (True)   | Benar (True)         |
| Benar (True)   | Salah (False)  | Salah (False)        |
| Salah (False)  | Benar (True)   | Salah (False)        |
| Salah (False)  | Salah (False)  | Benar (True)         |

## Tugas
Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{}\end{array}$$