---
title: Deretan dan Rekursi

---

# Deretan dan Rekursi 
# Deretan 
Deretan adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu. Selain itu, deret aritmatika dapat diartikan sebagai barisan yang nilai seluruh sukunya didapatkan dari penjumlahan atau pengurangan suku sebelumnya dengan suatu bilangan.

## Definisi Deretan 
Secara matematis, deretan dapat dianggap sebagai fungsi yang memetakan setiap bilangan bulat non-negatif 𝑛 ke dalam elemen tertentu dari himpunan. Deretan biasanya ditulis dengan tanda kurung atau koma antara anggota-anggota dalam urutan tersebut.

### Contoh Sederhana Deretan 
1. Deretan Bilangan Bulat Positif:
1,2,3,4,5,6,…
1,2,3,4,5,6,…
Ini adalah deretan yang terdiri dari bilangan bulat positif yang dimulai dari angka 1 dan bertambah 1 pada setiap elemen berikutnya.

2. Deretan Bilangan Genap:
2,4,6,8,10,12,…
2,4,6,8,10,12,…
Deretan ini terdiri dari angka-angka yang merupakan kelipatan dari 2.

2. Deretan Bilangan Ganjil:
1,3,5,7,9,11,…
1,3,5,7,9,11,…
Deretan ini terdiri dari angka-angka yang merupakan kelipatan dari 2 yang ditambah 1.

### contoh-contoh deretan dan formulanya yang umum digunakan dalam matematika

1. Deret Aritmetika
Deret aritmetika adalah deret yang setiap sukunya diperoleh dengan menambahkan bilangan tetap (selisih yang sama) pada suku sebelumnya.

Contoh Deret Aritmetika:

2,5,8,11,14,17,…
2,5,8,11,14,17,…
Formulanya: Untuk deret aritmetika, suku ke-n (dengan 𝑛≥1) dapat dihitung menggunakan rumus:
𝑎𝑛=𝑎1+(𝑛−1)⋅𝑑

di mana:

𝑎𝑛 = suku ke-n
𝑎1 = suku pertama
𝑑 = beda antara dua suku berturut-turut (selisih)
𝑛 = urutan suku (indeks)

2. Deret Geometri
Deret geometri adalah deret yang setiap sukunya diperoleh dengan mengalikan bilangan tetap (rasio yang sama) pada suku sebelumnya.

Contoh Deret Geometri:
3,6,12,24,48,96,…
3,6,12,24,48,96,…
Formulanya: Untuk deret geometri, suku ke-n (dengan n≥1) dapat dihitung menggunakan rumus:
𝑎𝑛=𝑎1⋅𝑟(𝑛−1)
 
di mana:
𝑎𝑛 = suku ke-n
𝑎1 = suku pertama
𝑟 = rasio antara dua suku berturut-turut
𝑛 = urutan suku (indeks)

3. Deret Bilangan Kuadrat
Deret bilangan kuadrat adalah deret yang terdiri dari bilangan yang merupakan kuadrat dari bilangan bulat positif.

Contoh Deret Bilangan Kuadrat:
1,4,9,16,25,36,…
1,4,9,16,25,36,…
Formulanya: Untuk deret bilangan kuadrat, suku ke-n dapat dihitung menggunakan rumus:
𝑎𝑛=𝑛2

di mana:
𝑎𝑛 = suku ke-n
𝑛 = urutan suku (indeks)

4. Deret Bilangan Kubik
Deret bilangan kubik adalah deret yang terdiri dari bilangan yang merupakan kubus dari bilangan bulat positif.

Contoh Deret Bilangan Kubik:
1,8,27,64,125,216,…
1,8,27,64,125,216,…
Formulanya: Untuk deret bilangan kubik, suku ke-n dapat dihitung menggunakan rumus:
𝑎𝑛=𝑛3

di mana:
𝑎𝑛 = suku ke-n
𝑛 = urutan suku (indeks)

5. Deret Fibonacci
Deret Fibonacci adalah deret yang dimulai dengan dua angka 0 dan 1, dan setiap angka berikutnya diperoleh dengan menjumlahkan dua angka sebelumnya.

Contoh Deret Fibonacci:
0,1,1,2,3,5,8,13,21,…
0,1,1,2,3,5,8,13,21,…
Formulanya: Deret Fibonacci dapat dituliskan dengan rumus rekursif:
𝐹𝑛=𝐹𝑛−1+𝐹𝑛−2

# Rekursi

Rekursi adalah metode pengulangan yang melibatkan penggunaan diri sendiri. Istilah ini memiliki makna yang beragam, tergantung pada disiplin ilmu yang digunakan, seperti linguistik, logika, matematika, dan ilmu komputer.
Dalam pemrograman, rekursi adalah konsep di mana fungsi memanggil dirinya sendiri untuk menyelesaikan masalah yang lebih kecil dari masalah awal. Rekursi sering digunakan untuk melintasi struktur data seperti pohon atau daftar tertaut.

## Fungsi Rekursi

Rekursi memiliki beberapa fungsi atau kegunaan dalam pemrograman dan matematika:

1. Sederhana dan elegan: Rekursi memungkinkan untuk memecahkan masalah yang kompleks dengan cara yang lebih sederhana dan lebih mudah dipahami.
2. Penyelesaian masalah berbasis pembagian: Rekursi berguna ketika suatu masalah dapat dipecah menjadi sub-masalah yang lebih kecil dan mirip dengan masalah awal.
3. Penghematan kode: Rekursi memungkinkan penulisan kode yang lebih ringkas dibandingkan dengan pendekatan iteratif (menggunakan perulangan).
4. Fleksibel dalam pemecahan masalah: Banyak algoritma, terutama dalam struktur data seperti pohon dan grafik, dapat lebih mudah diselesaikan menggunakan rekursi.

## Contoh Sederhana Rekursi 

Berikut adalah contoh rekursi sederhana dalam pemrograman untuk menghitung faktorial dari suatu angka:

Contoh: Menghitung Faktorial
Faktorial dari angka 
𝑛 (ditulis sebagai 𝑛!) adalah hasil perkalian dari semua bilangan bulat positif dari 1 hingga 𝑛. Faktorial didefinisikan sebagai:
𝑛!=𝑛×(𝑛−1)×(𝑛−2)×⋯×1
Dengan kasus dasar:
0!=1dan1!=1

Contoh Lain Rekursi: Deret Fibonacci
Deret Fibonacci adalah deret angka di mana setiap angka adalah hasil penjumlahan dari dua angka sebelumnya, dimulai dengan 0 dan 1:
0,1,1,2,3,5,8,13,…
Secara matematis, deret Fibonacci didefinisikan sebagai:
𝐹0=0, 𝐹1=1, 𝐹𝑛=𝐹𝑛−1+𝐹𝑛−2 untuk 𝑛≥2

# Tugas Pembuktian 3 Rumus

## Rumus 1
![Capture30](https://hackmd.io/_uploads/BkrUt4l7ye.png)

## rumus 2 
![Capture31](https://hackmd.io/_uploads/SJMI3El7yg.png)

## rumus 3
![Capture32](https://hackmd.io/_uploads/HkJa0Elm1x.png)
