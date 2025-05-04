**Transformasi Linier dan Buktinya**

Transformasi linier adalah fungsi yang mengubah satu vektor ke vektor lain dengan memenuhi dua sifat dasar: 

1. **Additivitas**: \( T(u + v) = T(u) + T(v) \) untuk setiap vektor \( u \) dan \( v \).
2. **Homogenitas**: \( T(cu) = cT(u) \) untuk setiap skalar \( c \) dan vektor \( u \).

Dalam konteks rotasi di \( \mathbb{R}^2 \), kita menggunakan matriks:

\[
A = \begin{bmatrix}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{bmatrix}
\]

### **1. Tambahan Vektor**
Misalkan \( u = \begin{bmatrix} x_1 \\ y_1 \end{bmatrix} \) dan \( v = \begin{bmatrix} x_2 \\ y_2 \end{bmatrix} \).

- Hitung \( T(u + v) \):

\[
T(u + v) = T\left(\begin{bmatrix} x_1 + x_2 \\ y_1 + y_2 \end{bmatrix}\right) = A\begin{bmatrix} x_1 + x_2 \\ y_1 + y_2 \end{bmatrix}
\]

\[
= A\begin{bmatrix} x_1 \\ y_1 \end{bmatrix} + A\begin{bmatrix} x_2 \\ y_2 \end{bmatrix} = T(u) + T(v)
\]

### **2. Homogenitas**
- Hitung \( T(cu) \):

\[
T(cu) = T\left(c\begin{bmatrix} x \\ y \end{bmatrix}\right) = A\begin{bmatrix} cx \\ cy \end{bmatrix}
\]

\[
= cA\begin{bmatrix} x \\ y \end{bmatrix} = cT(u)
\]

### **Kesimpulan**
Karena transformasi ini memenuhi kedua sifat di atas, maka \( T : \mathbb{R}^2 \to \mathbb{R}^2 \) yang didefinisikan oleh matriks \( A \) adalah transformasi linier. 

Silakan upload penjelasan ini ke GitHub Anda!