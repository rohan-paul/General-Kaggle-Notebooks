# All the basic Matrix Algebra you will need in Data Science

Matrix Basic Definitions

![](https://cdn-images-1.medium.com/max/1200/1*mu1ra3uDo0nrhdo4zwmZIQ.jpeg)

### Matrix Basic Definitions

A matrix A over a field K or, simply, a matrix A (when K is implicit) is a rectangular array of scalars usually presented in the following form:

![](https://cdn-images-1.medium.com/max/800/1*H3wy0MgHS_Ryt8gIP0GVIg.png)
undefined

The rows of such a matrix A are the m horizontal lists of scalars:

![](https://cdn-images-1.medium.com/max/800/1*gSWE0BYuHzjciAODvJQInA.png)
undefined

and the columns of A are the n vertical lists of scalars:

![](https://cdn-images-1.medium.com/max/800/1*lelN81T0HDMhOeRmqsNfng.png)
undefined

A matrix with m rows and n columns is called an m by n matrix, written as m\*n. The pair of numbers m and n is called the size of the matrix. Two matrices A and B are equal, written A = B, if they have the  
same size and if corresponding elements are equal. Thus, the equality of two m\*n matrices is equivalent to a system of mn equalities, one for each corresponding pair of elements.

![](https://cdn-images-1.medium.com/max/800/1*kU3svbZWHV1EAjlGm_cEYw.png)
undefined

**Matrix vs Vectors**

A matrix is simply a rectangular array of numbers and a vector is a row (or column) of a matrix.

vector is one dimension array such a=\[1 2 3 4 5\], but the matrix is more than one dimension array, and has some of operations.

A real system of linear equations

![](https://cdn-images-1.medium.com/max/800/1*0DfbdWTTsxjyEn-Oey7H_g.png)
undefined

can be simply rewritten using real vector and matrix symbols as a real matrix  
equation

![](https://cdn-images-1.medium.com/max/800/1*MmyqOUOZFcEC3DZkouBW2g.png)
undefined

where

![](https://cdn-images-1.medium.com/max/800/1*RlSk5eC84vNJpooPd237ig.png)
undefined![](https://cdn-images-1.medium.com/max/800/1*SRM3-_VgaWWEI6XoRgGE8Q.png)
undefined

### **The rank of a matrix**

![](https://cdn-images-1.medium.com/max/800/1*7qbRiqbh2aDBPF5PJr5Tdw.png)
undefined

### Inverse Matrix

![](https://cdn-images-1.medium.com/max/800/1*CFjuFftHUSH92pdwxYNEew.png)
undefined

The following are properties of the conjugate, transpose, conjugate transpose,  
and inverse matrices.

1.  The matrix conjugate, transpose, and conjugate transpose satisfy the distributive law:

![](https://cdn-images-1.medium.com/max/800/1*jlw3gzFMmCyGMl9fAGeAVA.png)
undefined

2\. The transpose, conjugate transpose, and inverse matrix of product of two matrices satisfy the following relationship:

![](https://cdn-images-1.medium.com/max/800/1*cpnud7mH1CWu19IIT9g_eA.png)
undefined

3\. Each of the symbols for the conjugate, transpose, and conjugate transpose can be exchanged with the symbol for the inverse:

![](https://cdn-images-1.medium.com/max/800/1*HziKyEGph_Jvw1NhnP44YQ.png)
undefined

### Matrix Addition

Let A and B, be two matrices with the same size, say m \*n matrices. The sum of A and B, written A þ B, is the matrix obtained by adding corresponding elements from A and B. That is,

![](https://cdn-images-1.medium.com/max/800/1*AmPGGemAFI59D3fFxhJAwQ.png)
undefined![](https://cdn-images-1.medium.com/max/800/1*7FAGtlxVfaAaBDBMKC_gLw.png)
undefined![](https://cdn-images-1.medium.com/max/800/1*dGz3z3KgFl7pwJLGSL9Mmg.png)
undefined

By using this definition, it is easy to verify that the addition and subtraction of  
two matrices obey the following rules:

![](https://cdn-images-1.medium.com/max/800/1*KU9UmkAYsP_PfBxTC2UCTA.png)
undefined

### The product of the matrix A by a scalar k

The product of the matrix A by a scalar k, written k . A or simply kA, is the matrix obtained by multiplying each element of A by k. That is,

![](https://cdn-images-1.medium.com/max/800/1*aJaI4cVx8PFPEMdls0NUXw.png)
undefined

Observe that A +B and kA are also m\*n matrices. We also define

### Matrix Multiplication

![](https://cdn-images-1.medium.com/max/800/1*t9WobgkZJqw4QZV3Q_lr5A.png)
undefined![](https://cdn-images-1.medium.com/max/800/1*YZ5Z6rdEdQllm7wq55Lfkw.png)
undefined

The product AB of a row matrix A, and a column matrix B, with the same number of elements, is defined to be the scalar (or 1\*1 matrix) obtained by multiplying corresponding entries and adding; that is,

![](https://cdn-images-1.medium.com/max/800/1*P_450HoHTPE62sWOy9zReg.png)
undefined![](https://cdn-images-1.medium.com/max/800/1*MR--oujZ79aAnLhlPTVEvg.png)
undefined![](https://cdn-images-1.medium.com/max/800/1*iFVkOh6U2Gl1JpwRoE49RA.png)
undefined

Suppose A, and B, are matrices such that the number of columns of A is  
equal to the number of rows of B; say, A is an m \* p matrix and B is a p\*n matrix. Then the product AB is the m \* n matrix whose ij-entry is obtained by multiplying the ith row of A by the jth column of B. That is,

![](https://cdn-images-1.medium.com/max/800/1*k0BgXLS7TIfwruAt4oiOWw.png)
undefined![](https://cdn-images-1.medium.com/max/800/1*QHRKStPtWK2KuNzYXVtzZA.png)
undefined![](https://cdn-images-1.medium.com/max/800/1*e9nCdO5eZzV01q3ddnqs9g.png)
undefined

where

![](https://cdn-images-1.medium.com/max/800/1*dCOQPu7RAVezIpuO4LNQUQ.png)
undefined

**There are four simple rules that will help us in multiplying matrices, listed here:**

1\. Firstly, we can only multiply two matrices when the number of columns in matrix A is equal to the number of rows in matrix B.

2\. Secondly, the first row of matrix A multiplied by the first column of matrix B gives us the first element in the matrix AB, and so on.

3\. Thirdly, when multiplying, order matters — specifically, AB ≠ BA.

4\. Lastly, the element at row i, column j is the product of the ith row of matrix A and the jth column of matrix B.

Further read through [this](https://www.mathsisfun.com/algebra/matrix-multiplying.html) for a very nice visual flow of Matrix Multiplication.

Let A; B; C be matrices. Then, whenever the products and sums are defined,

![](https://cdn-images-1.medium.com/max/800/1*-o5K4GuNwMaLEndWkRpj8g.png)
undefined

### Transpose of a Matrix

The transpose of a matrix A, written A^T , is the matrix obtained by writing the columns of A, in order, as rows.

![](https://cdn-images-1.medium.com/max/800/1*bcNnBUfn8HdO_pVUFMQjow.png)
undefined

In other words, if

![](https://cdn-images-1.medium.com/max/800/1*uY0g0Fd3Hf53X2XQnZJJmA.png)
undefined

**Some common Theorems that apply to Matrix Transpose**

Let A and B be matrices and let k be a scalar. Then, whenever the sum and product are defined,

![](https://cdn-images-1.medium.com/max/800/1*r8Crw6R0dFvLRpVDPTsblA.png)
undefined

### Square Matrices

A square matrix is a matrix with the same number of rows as columns. An n \*n square matrix is said to be of order n and is sometimes called an n-square matrix.  
Recall that not every two matrices can be added or multiplied. However, if we only consider square matrices of some given order n, then this inconvenience disappears. Specifically, the operations of addition, multiplication, scalar multiplication, and transpose can be performed on any n\*n matrices, and  
the result is again an n — n matrix.

The following are square matrices of order 3

![](https://cdn-images-1.medium.com/max/800/1*pgznsE5q_ByKBS4rdDSgiA.png)
undefined

And see all the following Matrices obtained after addition of multiplications fo A and B are also of order 3

![](https://cdn-images-1.medium.com/max/800/1*BCZZyk_5VCFyjOV5zh-xtw.png)
undefined

### Diagonal and Trace

Let A, be an n-square matrix. The diagonal or main diagonal of A consists of the elements with the same subscripts — that is,

![](https://cdn-images-1.medium.com/max/800/1*Zsu35rb3xOG7DMSbilYrvg.png)
undefined

The trace of A, written tr(A), is the sum of the diagonal elements. Namely,

![](https://cdn-images-1.medium.com/max/800/1*fpDIflzq8GHzz0BnA8vENw.png)
undefined

The following theorem applies on Trace of Matrices

![](https://cdn-images-1.medium.com/max/800/1*YCRCwGi2LaXFXhI9BIUEtg.png)
undefined

### Eigenvalues and Eigenvectors

For an n × n matrix A, if the linear algebraic equation

![](https://cdn-images-1.medium.com/max/800/1*uPM3zhctpoBHYgcDz2SfTQ.png)
undefined

**has a nonzero n × 1 solution vector u, then the scalar λ is called an eigenvalue of the matrix A, and u is its eigenvector corresponding to λ**

Eigenvalues and eigenvectors are only for square matrices. Non-square matrices do not have eigenvalues. If the matrix A is a real matrix, the eigenvalues will either be all real, or else there will be complex conjugate pairs.

Eigenvectors are _by definition nonzero_. Eigenvalues may be equal to zero.

We do not consider the zero vector to be an eigenvector: since A0=0=λ0 for _every_ scalar λ, the associated eigenvalue would be undefined.

If someone hands you a matrix A and a vector v, it is easy to check if v is an eigenvector of A: simply multiply v by A and see if Av is a scalar multiple of v. On the other hand, given just the matrix A it is not so straightforward to find the eigenvectors. There are few steps involved here.

### MATRIX FACTORIZATION

First note, most of the times “matrix factorization” and “matrix decomposition” are used interchangeably

Suppose we want to express an m \* n matrix A as the product of two matrices A1 and A2 in the form

![](https://cdn-images-1.medium.com/max/800/1*1PhQO1pvURi2FUYopr1XGw.png)
undefined

where A1 and A2 are m \* r and r \* n matrices, respectively. We assume r  m, n. We call this problem matrix factorization.

If no special dependencies exist among columns and rows of a matrix, its rank generally coincides with the smaller of the numbers of columns and rows. Assume that matrices A1 and A2 both have rank r . It is known that the rank of the product of two matrices does not exceed the rank of either one. Namely,

![](https://cdn-images-1.medium.com/max/800/1*SVnvCylnHCYUPgUzG7PrfQ.png)
undefined

for any matrices A and B for which their product can be defined.

### Singular Value Decomposition

Singular value decomposition is a method of decomposing a matrix into three other matrices and its a central matrix decomposition method in linear algebra. It has been referred to as the “fundamental theorem of linear algebra”.

![](https://cdn-images-1.medium.com/max/800/1*XsDWvrcG-Eq_osSmnoMl7Q.png)
undefined

In a slightly detailed form

![](https://cdn-images-1.medium.com/max/800/1*hkpTA1-GP-TQ4ZCApATNEg.png)
undefined

The diagonal entries σi , i = 1, . . . , r, of Σ are called the singular values,  
ui are called the left-singular vectors, and v j are called the right-singular  
vectors. By convention, the singular values are ordered, i.e., σ1 > σ2 >  
σr > 0.

The columns of _U_ are called _left singular vectors,_ while those of _V_ are called _right singular vectors_.

We know that _U_ and _V_ are orthogonal, that is:

![](https://cdn-images-1.medium.com/max/800/1*RvPdO9mPVU5dihZLIO9lNw.png)
undefined

Where _I_ is the _identity matrix_. Only the diagonals of the identity matrix are 1, with all other values being 0. Note that because _U_ is not square we cannot say that _U ^T_ranspose_(U_)=_I,_ so _U_ is only orthogonal in one direction.

In another form for the orthogonality of U and V

![](https://cdn-images-1.medium.com/max/800/1*m_5eQsn9hv1FoqFwtIa9dw.png)
undefined

The SVD is used widely both in the calculation of other matrix operations, such as matrix inverse, but also as a data reduction method in machine learning. SVD can also be used in least squares linear regression, image compression, and denoising data.

Here are the dimensions of the factorization:

![](https://cdn-images-1.medium.com/max/800/1*Z2kjcZ-DFS-IIYUz0hFgDw.png)

**Interpretation of SVD**

The intuition behind the singular value decomposition needs some explanations about the idea of matrix transformation.

**A** is a matrix that can be seen as a linear transformation. This transformation can be decomposed in three sub-transformations: 1. rotation, 2. re-scaling, 3. rotation. These three steps correspond to the three matrices **U**, **Σ**, and **V**.

#### Comparing SVD with Eigenvalues and Eigen Vectors

First noting the formulae of Eigenvalues

![](https://cdn-images-1.medium.com/max/800/1*aTu0veQK0GrXKTf_0BGl4g.png)
undefined

And the one for SVD

![](https://cdn-images-1.medium.com/max/800/1*IztTNA6IPctyjuJmrkY_-g.png)

The key point to note here, that the concept of Singular-Value is a lot like eigenvalues, but different because the matrix A now is more usually rectangular. But for a rectangular matrix, the whole idea of eigenvalues  
is not possible because if I multiply A times a vector x in n dimensions, out will come something in m dimensions and it’s not going to equal lambda x.

So Ax equal lambda x is not even possible if A is rectangular. And here comes SVD and so this is the new word is singular. And in between go the —   
not the eigenvalues, but the singular values. There are two sets of singular vectors, not one. For eigenvectors, we just had one set.

We’ve got one set of left eigenvectors in m dimensions, and we’ve got another set of right eigenvectors in n dimensions. And numbers in between are not eigenvalues, but singular values.

### Derivatives of Scalars with Respect to Vectors; The Gradient

The derivative of a scalar-valued function with respect to a vector is a vector  
of the partial derivatives of the function with respect to the elements of the  
vector. If f (x) is a scalar function of the vector x = (x1 , . . . , xn ),

![](https://cdn-images-1.medium.com/max/800/1*P-RVUTLbeOt0ZJRX2SlEFA.png)
undefined

if those derivatives exist. This vector is called the gradient of the scalar-valued  
function, and is sometimes denoted by

![](https://cdn-images-1.medium.com/max/800/1*mBmntTiyuvQu1XfCPxTuTg.png)
undefined

The notation g\_f or ∇f implies differentiation with respect to “all” arguments  
of f , hence, if f is a scalar-valued function of a vector argument, they represent  
a vector. This derivative is useful in finding the maximum or minimum of a func-  
tion. Such applications arise throughout statistical and numerical analysis.

### Derivatives of Vectors with Respect to Vectors; The Jacobian

The derivative of an m-vector-valued function of an n-vector argument con-  
sists of nm scalar derivatives. These derivatives could be put into various structures. Two obvious structures are an n × m matrix and an m × n matrix.

![](https://cdn-images-1.medium.com/max/800/1*RPPmKn56TBwVodvYuMAzMQ.png)
undefined

**Some more notes on Jacobian and ways to express Jacobian operator**

Jacobian operator with respect to an m × n matrix X is defined as

![](https://cdn-images-1.medium.com/max/800/1*VJZBGAknwpIs_45Y3q810g.png)
undefined

and Jacobian matrix of the real scalar function f (X) with respect to its matrix  
variable X

![](https://cdn-images-1.medium.com/max/800/1*2bPtWFujRMvJzVN01b96BQ.png)
undefined

is given by

![](https://cdn-images-1.medium.com/max/800/1*ORRiok3WawdXJwirpbuxWg.png)
undefined

### Higher-Order Derivatives with Respect to Vectors; The Hessian

Higher-order derivatives are derivatives of lower-order derivatives. As we have seen, a derivative of a given function with respect to a vector is a more complicated object than the original function. The simplest higher-order derivative with respect to a vector is the second-order derivative of a scalar-valued function. Higher-order derivatives may become uselessly complicated.  
In accordance with the meaning of derivatives of vectors with respect to  
vectors, the second derivative of a scalar-valued function with respect to a  
vector is a matrix of the partial derivatives of the function with respect to the  
elements of the vector. This matrix is called the Hessian, and is denoted by  
Hf or sometimes by ∇∇f or ∇^2f :

![](https://cdn-images-1.medium.com/max/800/1*WxwSIFvqPmwRRKF3t3_PSA.png)
undefined

### Formulas for Some Matrix Derivatives

![](https://cdn-images-1.medium.com/max/800/1*X09w10YtlNUQYHMgf247Dg.png)
undefined

By [Rohan Paul](https://medium.com/@paulrohan) on [July 15, 2021](https://medium.com/p/4f333f4dfcd5).

[Canonical link](https://medium.com/@paulrohan/all-the-basic-matrix-algebra-you-will-need-in-data-science-4f333f4dfcd5)

Exported from [Medium](https://medium.com) on July 17, 2021.