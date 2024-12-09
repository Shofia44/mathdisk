---
title: Analisa Graph

---

# Analisa Graph
## Pengertian Graph
Graph adalah jenis struktur data umum yang susunan datanya tidak berdekatan satu sama lain (non-linier). Graph terdiri dari kumpulan simpul berhingga untuk menyimpan data dan antara dua buah simpul terdapat hubungan yang saling keterkaitan.
## Social Network Analysis
Social Network Analysis adalah pendekatan metodologis yang digunakan untuk mempelajari hubungan dan pola interaksi antara aktor (node) dalam suatu jaringan. Node bisa berupa individu, organisasi, atau entitas lainnya yang dihubungkan oleh ikatan (edges) seperti komunikasi, kerjasama, atau pengaruh.

Dalam SNA, jaringan sosial direpresentasikan sebagai graf, yang terdiri dari:

- Node (Simpul): Representasi dari individu atau entitas dalam jaringan.
- Edges (Tepi): Hubungan atau interaksi antara node. Edges bisa bersifat langsung (directed) atau tidak langsung (undirected).

Beberapa pengukuran centrality yang populer digunakan dalam analisis jejaring sosial yaitu degree centrality, betweenness centrality, closeness centrality, eigenvector centrality, pagerank centrality, serta hub & authority.

### 1. Degree Centrality
Degree centrality adalah jumlah edge yang terkoneksi pada suatu node yang mewakili interaksi.

### 2. Betweenness Centrality
Perhitungan yang mewakili seberapa banyak sebuah node dilewati node lain untuk menuju ke sebuah node di dalam jaringan. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan. Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam luasnya penyebaran informasi. Berikut merupakan formula perhitungan Betweenness Centrality.

![Screenshot 2024-11-24 184309](https://hackmd.io/_uploads/B1Si-9eXkg.png)

### 3. Closeness Centrality

Closenes centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.

## Karakteristik Jejaring Sosial
### 1. Network Density

Network Density dengan kata lain kerapatan jaringan merupakan perbandingan antara jumlah hubungan yang ada pada suatu jaringan dibandingkan dengan total keseluruhan hubungan yang mungkin terjadi pada jejaring tersebut. Network Density memiliki nilai diantara 0 dan 1. Semakin mendekati nol maka hubungan semakin renggang.

Secara matematis, network density diukur melalui persamaan berikut
![Screenshot 2024-11-24 184844](https://hackmd.io/_uploads/BJyhzqg7ye.png)
Dimana T menyatakan jumlah edges dan N menyatakan jumlah nodes

### 2. Path Length

Path Length dapat dianalogikan seperti berikut “berapakah jarak antara si A dan si B untuk dapat saling berkenalan?”. Pada konteks ini, jarak fisik tidak relevan. Dua individu yang berada di satu bangunan secara fisik dikatakan dekat, namun mungkin tidak saling mengenal.



https://aemfariz.medium.com/mengenal-konsep-social-network-analysis-sna-5ee36c485b6b
https://putrialutfi.medium.com/gephi-social-network-visualization-fdf87ca5188a