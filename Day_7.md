# scalars and vectors
Scalars are used to represent quantities that are one-dimensional, such as single values of data points, model parameters, or results of calculations. 
A vector is a one-dimensional array or list of numbers, and it represents a collection of related features or values in multiple dimensions. Vectors are used extensively to represent data points, model parameters, and intermediate calculations in algorithms.

# L1 Norm:
The L1 norm of a vector is the sum of the absolute values of its components. 

Example of L1 Norm:

For x=[3,−4,2], the L1 norm is:

∥
𝑥
∥
1
=
∣
3
∣
+
∣
−
4
∣
+
∣
2
∣
=
3
+
4
+
2
=
9
∥x∥ 
1
​
 =∣3∣+∣−4∣+∣2∣=3+4+2=9

 # L2 Norm:
 
The L2 norm of a vector is the square root of the sum of the squares of its components 

Example of L2 Norm:
For
x=[3,−4,2], the L2 norm is:

∥
𝑥
∥
2
=
3
2
+
(
−
4
)
2
+
2
2
=
9
+
16
+
4
=
29
≈
5.39
∥x∥ 
2
​
 = root(
3^ 
2
 +(−4)^ 
2
 +2^ 
2
 )
​
 = 
9+16+4
​
 = 
29
​
 ≈5.39


# Eigenvalue:

An eigenvalue is a scalar 
λ that tells you how much a matrix stretches or compresses vectors when the matrix is applied to them. More formally:

For a given square matrix 
𝐴, an eigenvalue 
𝜆 is a scalar that satisfies the equation:
𝐴
𝑣
=
𝜆
𝑣
Av=λv
where:
𝐴 is a square matrix (e.g., 
𝑛
×
𝑛
n×n),
𝑣 is a vector (called an eigenvector),
λ is the eigenvalue

# Eigenvector:

An eigenvector is a non-zero vector 
𝑣 that remains in the same direction (or opposite direction) after the matrix transformation. Essentially, applying the matrix 
𝐴 to the eigenvector 
𝑣 only scales it by a factor of 
λ, without changing its direction.

Mathematically, the eigenvector 
𝑣
v satisfies the equation:
𝐴
𝑣
=
𝜆
𝑣
Av=λv
where 
v is a vector that is not the zero vector. 

# Types of matrix

Square Matrix: Same number of rows and columns.

Row Matrix: One row, multiple columns.

Column Matrix: One column, multiple rows.

Zero Matrix: All elements are zero.

Identity Matrix: Square matrix with ones on the diagonal and zeros elsewhere.

Diagonal Matrix: Square matrix with non-zero elements only on the diagonal.

Scalar Matrix: A diagonal matrix with identical diagonal elements.

Symmetric Matrix: A square matrix equal to its transpose.

Skew-Symmetric Matrix: A matrix whose transpose is the negative of itself.

# General Formula for Determinants (n x n Matrix)

For a general 
𝑛
×
𝑛
n×n matrix, the determinant is defined recursively using cofactor expansion. The determinant is calculated by expanding along any row or column, and for larger matrices, this involves calculating the determinants of smaller submatrices (minors).

Definition:
For an 
𝑛
×
𝑛
n×n matrix 
𝐴
A, the determinant is calculated as:

det
(𝐴)=
∑
(
−
1
)
^(𝑖
+
𝑗)
𝑎
(𝑖
𝑗)
det
(
𝐴
𝑖
𝑗
)

# Steps to Find the Inverse of a 3x3 Matrix:

Calculate the determinant 
det
(
𝐴
).

Find the cofactor matrix of 
𝐴.


Transpose the cofactor matrix to get the adjugate (adjoint) matrix.

Multiply the adjugate by 
1
det
(
𝐴
).


​
 

