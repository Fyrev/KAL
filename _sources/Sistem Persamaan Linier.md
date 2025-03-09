---
title: Sistem Persamaan Linier

---

# Sistem Persamaan Linier
Sistem persamaan linear adalah kumpulan persamaan linear yang terdiri dari beberapa variabel. Sistem persamaan linear merupakan salah satu materi dalam ilmu matematika. 

berikut adalah materi" yang saya akan lampirkan :

# Sistem Persamaan linier

## Definisi Sistem Persamaan Linier

## Solusi Persamaan Linier

### Eliminasi

### Eliminasi Gaus
Definisi Eliminasi Gauss
Eliminasi Gauss adalah proses mengubah matriks augmented (matriks koefisien yang diperluas dengan vektor konstanta) dari sistem persamaan linear menjadi bentuk eselon baris atau eselon baris tereduksi menggunakan operasi baris elementer, sehingga solusi sistem dapat ditentukan.

Contoh Sistem Persamaan Linear dengan Solusi Tunggal, Banyak, dan Tidak Ada Solusi:


2x+y−z=3
x−y+2z=4
3x+y+z=5
​
Berikut adalah contoh sistem persamaan linear dengan **solusi tunggal, banyak, dan tidak ada solusi**.



1. Sistem dengan Solusi Tunggal
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

2. Sistem dengan Banyak Solusi (Tak Hingga Solusi) 
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



 3. Sistem Tanpa Solusi
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