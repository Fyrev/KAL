### Bukti Transformasi Linier

**Definisi Transformasi Linier:**
Transformasi T: R² → R² adalah linier jika berlaku:
1. T(v + w) = T(v) + T(w) untuk semua v, w ∈ R²
2. T(cv) = cT(v) untuk semua v ∈ R² dan c ∈ R

**Matriks untuk Rotasi:**
Transformasi rotasi dinyatakan dengan matriks A:
A = [ cosθ  -sinθ ]
       [ sinθ   cosθ ]

**Langkah 1: Verifikasi Penjumlahan**
- Ambil dua vektor v = (x₁, y₁) dan w = (x₂, y₂).
- Hitung T(v + w):
  T(v + w) = T((x₁ + x₂, y₁ + y₂))
  = A * [(x₁ + x₂), (y₁ + y₂)]

- Hitung T(v) + T(w):
  T(v) = A * [(x₁), (y₁)]
  T(w) = A * [(x₂), (y₂)]
  T(v) + T(w) = A * [(x₁), (y₁)] + A * [(x₂), (y₂)]

- Dengan sifat distribusi matriks, kedua hasil di atas akan sama, maka T(v + w) = T(v) + T(w).

**Langkah 2: Verifikasi Skalar**
- Ambil vektor v = (x, y) dan skalar c.
- Hitung T(cv):
  T(cv) = T((cx, cy))
  = A * [(cx), (cy)]

- Hitung cT(v):
  T(v) = A * [(x), (y)]
  cT(v) = c * (A * [(x), (y)])

- Dalam hal ini, hasil T(cv) juga akan sama dengan cT(v).

### Kesimpulan
Karena kedua syarat transformasi linier telah terpenuhi, maka transformasi rotasi yang didefinisikan oleh matriks A adalah transformasi linier.