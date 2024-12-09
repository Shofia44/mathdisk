---
title: Teorema Bayes

---

# Teorema Bayes

---


**Teorema Bayes** merupakan salah satu konsep dasar statistika yang membantu memperbarui hipotesis berdasarkan informasi baru. Teorema ini berguna untuk mengetahui peluang suatu kejadian bersyarat yang sulit diprediksi angkanya. Sederhananya, semakin banyak bukti yang diterima akan semakin akurat hipotesis yang ada.

* **Prior**
Keyakinan awal tentang suatu parameter atau hipotesis sebelum mempertimbangkan data baru. Contohnya, keyakinan awal berdasarkan pengalaman atau pengetahuan sebelumnya.
* **Likelihood**
Probabilitas data yang diamati diberikan parameter tertentu. Likelihood digunakan untuk mengukur seberapa cocok model dengan data yang tersedia.
* **Posterior**
Keyakinan yang diperbarui tentang parameter setelah mempertimbangkan data baru, dihitung menggunakan Bayes' Theorem.

***Contohnya:***
Bagaimana kemungkinan/probabilitas usia paruh baya tekanan darah sangat tinggi  kemungkinan penyakit Hipertensi (H) atau Tidak (T)
|No|Usia|Tekanan Darah|Penyakit(H/T)
|--|-------|-------- |-----|
|1.| Muda  | Normal | T |
|2.| Muda  | Tinggi | T |
|3.| Paruh baya| Normal | T |
|4.| Paruh baya| Tinggi | H |
|5.| Tua  | Normal | H |
|6.| Tua  | Sangat Tinggi| H |
|7.| Muda | Normal | T |
|8.| Tua  | Tinggi | H |

Dari tabel diatas tentukan:
* Hitunglah probabilitas Hipertensi terhadapa usia paruh baya tekanan darah sangat tinggi  
* Hitunglah probabilitas Tidak  Hipertensi terhadap usia paruh baya tekanan darah sangat tinggi  

Sehingga penggunaan teorema bayes adalah menghubungkan antara prior, likelihood dan posterior yang dapat ditulis sebagai berikut:

$P( H| X) = \frac{P(X|H) \cdot P(H)}{P(X)}$

- $P(H | X)$ adalah posterior probabilitas dari parameter $H$ setelah melihat data $X$.
- $P(X | H)$ adalah likelihood dari data $X$ dengan parameter $H$.
- $P(H)$ adalah prior probabilitas dari parameter $H$.
* $P(X)$ adalah probabilitas dari data $X$.

**Jawaban:**
1. $P(H | X)$ = $P(X_1| H)$ *.* $P(X_2 | H)$ *.* $P(H)$
= $P(\frac{1}{4})$ *.* $P(\frac{1}{4})$ *.* $P(\frac{4}{8})$
= $0.03125$

2. $P(T | X)$ = $P(X_1| T)$ *.* $P(X_2 | T)$ *.* $P(T)$
= $P(\frac{1}{4})$ *.* $(0)$ *.* $P(\frac{4}{8})$
= $0$