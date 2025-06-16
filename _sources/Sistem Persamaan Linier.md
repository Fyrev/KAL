---
title: Sistem Persamaan Linier

---


# Sistem Persamaan linier

Sistem persamaan linear adalah kumpulan persamaan linear yang terdiri dari beberapa variabel. Sistem persamaan linear merupakan salah satu materi dalam ilmu matematika. 

berikut adalah materi" yang saya akan lampirkan :

Sistem Persamaan Linear (SPL)

Definisi:

Sistem Persamaan Linear (SPL) adalah kumpulan dua atau lebih persamaan linear yang memiliki satu atau lebih variabel.

**Jenis-Jenis SPL**

Berdasarkan jumlah solusi, SPL dapat dikategorikan menjadi tiga jenis:

SPL dengan Solusi Tunggal (Konsisten dan Determinan ≠ 0)
Sistem memiliki satu solusi unik, artinya ada satu nilai untuk setiap variabel yang memenuhi semua persamaan.

SPL dengan Tak Hingga Banyak Solusi (Konsisten, tetapi Dependensi Linier)
Sistem memiliki lebih dari satu solusi karena ada variabel bebas yang dapat bernilai sembarang.

SPL Tanpa Solusi (Inkonsisten)
Sistem tidak memiliki solusi karena terdapat kontradiksi dalam persamaan.




## Definisi Sistem Persamaan Linier

## Solusi Persamaan Linier

### penyelesaian sistem persamaan linier 

Mari kita selesaikan setiap sistem persamaan linier menggunakan **Operasi Baris Elementer (OBE)** dan periksa apakah sistem memiliki solusi unik, tak hingga solusi, atau tidak ada solusi.

---

### **Soal 1:**

  x1 + 2x2 +3x3 = 6
​
 
  2x1 + 4x2 + 6x3 = 12
​
 
  x3 − x2 = 2
​
 
​
  

​


**Matriks Augmented:**

[
1  2  3  |6 
2  4  6  |12 
0  -1  1  |2
]

- Baris 2 dikurangi 2 kali Baris 1:

[
1  2  3  |6 
0  0  0  |0 
0  -1  1  |2
]

- Karena Baris 2 semuanya nol (tidak berkontribusi ke solusi), kita eliminasi:

[
1  2  3  |6 
0  -1  1  |2
]

- Substitusi dari baris terakhir:  x3 = x2 + 2 
- Substitusi ke baris pertama:


x1 + 2x2 + 3(x2 + 2) = 6



x1 + 2x2 + 3x2 + 6 = 6



x1 + 5x2 = 0


**Solusi Umum:**

x1 = -5t,  x2 = t,  x3 = t + 2


**Kesimpulan:** Tak hingga solusi (satu variabel bebas,  t ).

---

### **Soal 2:**

[
x1 + x2 + x3 = 3 
2x1 + x3 = 5 
x1 + 2x2 = 3
]

**Matriks Augmented:**

[
1  1  1  |3 
2  0  1  |5 
1  2  0  |3
]

- Baris 2 dikurangi 2 kali Baris 1:

[
1  1  1  |3 
0  -2  -1  |-1 
1  2  0  |3
]

- Baris 3 dikurangi Baris 1:
[
1  1  1  |3 
0  -2  -1  |-1 
0  1  -1  |0
]

- Baris 3 ditambah  1/2  Baris 2:

[
1  1  1  |3 
0  -2  -1  |-1 
0  0  3/2 & |-1/2
]

- Dari baris terakhir,  x3 = 1/3
- Substitusi ke baris 2:

-2x2 - x3 = -1



-2x2 - 1/3 = -1



-2x2 = -2/3



x2 = 1/3


- Substitusi ke baris pertama:

x1 + 1/3 + 1/3 = 3



x1 = 3 - 2/3 = 7/3


**Solusi Unik:**  x1 = 7/3, x2 = 1/3, x3 = 1/3 .

---

### **Soal 3:**

[
2x1 + 2x2 = 4 
x1 + x2 = 2
]

**Matriks Augmented:**

[
2  2  |4 
1  1  |2
]

- Baris 1 dikurangi 2 kali Baris 2:
[
1  1  |2 
0  0  |0
]

-  x1 + x2 = 2 > x2 = t, x1 = 2 - t 

**Solusi Umum:**  x1 = 2 - t, x2 = t  (tak hingga solusi).

---

### **Soal 4:**

[
x1 + x2 = 5 
x1 + x3 = 6
]

**Matriks Augmented:**
[

1  1  0  |5 
1  0  1  |6
]

- Baris 2 dikurangi Baris 1:

[
1  1  0  |5 
0 -1  1  |1
]

- Dari baris kedua,  x3 = x2 + 1 
- Dari baris pertama,  x1 = 5 - x2 

**Solusi Umum:**  x1 = 5 - t, x2 = t, x3 = t + 1  (tak hingga solusi).

---

 **Kesimpulan:**
| Soal | Jenis Solusi |
|------|-------------|
| Soal 1 | Tak hingga solusi |
| Soal 2 | Solusi unik |
| Soal 3 | Tak hingga solusi |
| Soal 4 | Tak hingga solusi |



### operasi baris elementer 

1. Jenis-Jenis Operasi Baris Elementer
OBE terdiri dari tiga jenis operasi dasar:

Pertukaran Baris (Ri ↔ Rj)

Menukar posisi dua baris dalam matriks.

Contoh: Tukar Baris 1 dan Baris 2


R1↔R2

Perkalian Baris dengan Skalar (k ≠ 0)

Mengalikan satu baris dengan konstanta tak nol.

Contoh: Kalikan Baris 2 dengan 

 

𝑅2→1/2𝑅2

​Penjumlahan atau Pengurangan Baris

Menambahkan atau mengurangi kelipatan suatu baris ke baris lain.

Contoh: Baris 2 dikurangi 2 kali Baris 1

𝑅2→𝑅2 − 2𝑅1


​

### Eliminasi

### Eliminasi Gaus
**Definisi Eliminasi Gauss**

Eliminasi Gauss adalah proses mengubah matriks augmented (matriks koefisien yang diperluas dengan vektor konstanta) dari sistem persamaan linear menjadi bentuk eselon baris atau eselon baris tereduksi menggunakan operasi baris elementer, sehingga solusi sistem dapat ditentukan.

Contoh Sistem Persamaan Linear dengan Solusi Tunggal, Banyak, dan Tidak Ada Solusi:


2x+y−z=3

x−y+2z=4

3x+y+z=5
​
Berikut adalah contoh sistem persamaan linear dengan **solusi tunggal, banyak, dan tidak ada solusi**.



1. **Sistem dengan Solusi Tunggal**
Sistem memiliki solusi tunggal jika memiliki jumlah persamaan yang cukup dan semua barisnya **tidak saling bertentangan**.

2x+y−z=3

x−y+2z=4

3x+y+z=5



Eliminasi Gauss :

2 1 -1 | 3

1 -1 2 | 4

3 1 1  | 5


Kesimpulan: Sistem ini memiliki solusi unik karena setelah eliminasi, diperoleh tiga persamaan independen yang tidak bertentangan.

---

2. **Sistem dengan Banyak (Solusi Tak Hingga Solusi)**

Sistem memiliki tak hingga banyak solusi jika terdapat baris yang menjadi nol seluruhnya, menunjukkan adanya variabel bebas.

x+y+z=4

2x+2y+2z=8

3x+3y+3z=12
​​
 


Eliminasi Gauss:

Bentuk matriks augmented:

​
  
1 1 1 ∣ 4

2 2 2 ∣ 8

3 3 3 ∣ 12
​


Kurangkan baris kedua dengan 2 × baris pertama, dan baris ketiga dengan 3 × baris pertama:

1 1 1 | 1

0 0 0 | 0

0 0 0 | 2

Baris kedua dan ketiga menjadi nol, artinya hanya ada satu persamaan dengan tiga variabel, sehingga sistem memiliki tak hingga banyak solusi.

 Kesimpulan: Karena ada variabel bebas, solusinya dapat diekspresikan dalam bentuk parameter seperti:


x=4−y−z 

 y dan z sebagai variabel bebas.



 3. **Sistem Tanpa Solusi**

Sistem tidak memiliki solusi jika terjadi kontradiksi saat eliminasi, misalnya dua persamaan bertentangan.

x+y+z     =1

2x+2y+2z  =2

x+y+z     =3
​
  ​


Eliminasi Gauss:

Bentuk matriks augmented:


1  1  1  | 1 

2  2  2  | 2 

1  1  1  | 3


Kurangkan baris kedua dengan 2 × baris pertama, dan baris ketiga dengan baris pertama:



1  1  1  | 1 

0  0  0  | 0 

0  0  0  | 2



Baris terakhir menghasilkan persamaan 0=2 yang jelas tidak mungkin terjadi.

 Kesimpulan: Sistem ini tidak memiliki solusi karena terdapat pertentangan dalam persamaan.



### Solusi Grafik