<h1>Vectors and Spaces</h1>

__Vector__: ![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D) a quantity that has both direction and magnitude.

__Real Coordinate Space__: ![equation](https://latex.codecogs.com/gif.latex?%5Cmathbb%7BR%7D%5E%7Bn%7D) all possible real-valued n-tuples (*n* ordered list of elements)
 e.g.  ![equation](https://latex.codecogs.com/gif.latex?%5Cmathbb%7BR%7D%5E%7B3%7D) :

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20x%5C%5C%20y%5C%5C%20z%20%5Cend%7Bbmatrix%7D%20x%2C%20y%2C%20z%20%5Cepsilon%20%5Cmathbb%7BR%7D)

<br>
<br>

__Vector Addition__: if vectors ![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D) and ![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7By%7D) are of the same dimension, they may be added algebraically: ![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D) + ![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7By%7D) = 

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20x_%7B1%7D&plus;y_%7B1%7D%5C%5C%20x_%7B2%7D&plus;y_%7B2%7D%20%5C%5C%20...%20%5C%5C%20x_%7Bn%7D&plus;y_%7Bn%7D%20%5Cend%7Bbmatrix%7D)

Graphical representation: 

![grid](https://user-images.githubusercontent.com/68278907/88667100-37c38180-d0e1-11ea-845d-3a75d6400502.png)

<br>
<br>

__Vector Scalar Multiplication__: 

![equation](https://latex.codecogs.com/gif.latex?%5Calpha%20%5Cbegin%7Bbmatrix%7D%20x%5C%5Cy%5C%5Cz%20%5Cend%7Bbmatrix%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20%5Calpha%20x%5C%5C%5Calpha%20y%5C%5C%5Calpha%20z%20%5Cend%7Bbmatrix%7D)

<br>
<br>

__Unit Vector__: a vector of magnitude 1 pointing in a specific direction. e.g.:

![equation](https://latex.codecogs.com/gif.latex?%5Cwidehat%7Bi%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%201%5C%5C%200%20%5Cend%7Bbmatrix%7D%2C%20%5Cwidehat%7Bj%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%200%5C%5C%201%20%5Cend%7Bbmatrix%7D) 

<br>
<br>

__Parametric representation of lines__: ![equation](https://latex.codecogs.com/gif.latex?S%20%3D%20%5C%7B%20c%5Coverrightarrow%7Bv%7D%7Cc%5Cepsilon%20%5Cmathbb%7BR%7D%20%5C%7D) *S* is a set of colinear vectors (All possible vectors that may be formed by the scalar multiplication of *c* and ![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bv%7D)):

![set](https://user-images.githubusercontent.com/68278907/88681073-78c39200-d0f1-11ea-95cd-ddda14a32301.png)

<br>
<br>

__Linear Combination__: the sum of the scalar multiples of the vectors within a set.

![equation](https://latex.codecogs.com/gif.latex?Linear%20%5C%20Combination%20%5C%20of%20%5C%20%5Coverrightarrow%7Bv%7D_%7B1%7D%2C%5Coverrightarrow%7Bv%7D_%7B2%7D%2C...%2C%5Coverrightarrow%7Bv%7D_%7Bn%7D%20%5C%20in%20%5C%20%5Cmathbb%7BR%7D%20%5C%20%5Cnewline%20%3D%20%5C%20c_%7B1%7D%5Coverrightarrow%7Bv%7D_%7B1%7D&plus;c_%7B2%7D%5Coverrightarrow%7Bv%7D_%7B2%7D&plus;...&plus;c_%7Bn%7D%5Coverrightarrow%7Bv%7D_%7Bn%7D%20%5C%20for%20%5C%20c_%7B1%7D%5Crightarrow%20c_%7Bn%7D%20%5C%20%5Cepsilon%20%5C%20%5Cmathbb%7BR%7D)

<br>
<br>

__Span__: the set of all linear combinations of a set of vectors. 

<br>
<br>

__Colinear__: a set of vectors lying upon the same line.

<br>
<br>

__Linearly Dependent__: The set of vectors ![equation](https://latex.codecogs.com/gif.latex?%5C%7B%20%5Coverrightarrow%7Bx%7D_%7B1%7D%2C%20%5Coverrightarrow%7Bx%7D_%7B2%7D%2C%20...%2C%20%5Coverrightarrow%7Bx%7D_%7Bn%7D%20%5C%7D) is linearly dependent if ![equation](https://latex.codecogs.com/gif.latex?c_%7B1%7D%5Coverrightarrow%7Bx%7D_%7B1%7D&plus;%20c_%7B2%7D%5Coverrightarrow%7Bx%7D_%7B2%7D&plus;%20...&plus;%20c_%7Bn%7D%5Coverrightarrow%7Bx%7D_%7Bn%7D%3D%5Coverrightarrow%7B0%7D) for some ![equation](https://latex.codecogs.com/gif.latex?c_%7B1%7D%2C%20c_%7B2%7D%2C%20...%2Cc_%7Bn%7D%20%5C%20%5Cepsilon%20%5C%20%5Cmathbb%7BR%7D) where at least one of ![equation](https://latex.codecogs.com/gif.latex?c_%7B1%7D%2C%20c_%7B2%7D%2C%20...%2Cc_%7Bn%7D) is non–zero.


Example: 

![equation](https://latex.codecogs.com/gif.latex?are%20%5C%20%5Cbegin%7Bbmatrix%7D%202%5C%5C1%20%5Cend%7Bbmatrix%7D%20%5C%20and%20%5C%20%5Cbegin%7Bbmatrix%7D%203%5C%5C2%20%5Cend%7Bbmatrix%7D%5C%20linearly%20%5C%20dependent%3F)

Solution:

![equation](https://latex.codecogs.com/gif.latex?Test%20%5C%20if%20%5C%20c_%7B1%7D%5Cbegin%7Bbmatrix%7D%202%5C%5C1%20%5Cend%7Bbmatrix%7D%20&plus;%20c_%7B2%7D%5Cbegin%7Bbmatrix%7D%203%5C%5C2%20%5Cend%7Bbmatrix%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%200%5C%5C0%20%5Cend%7Bbmatrix%7D)

![equation](https://latex.codecogs.com/gif.latex?c_%7B1%7D2&plus;c_%7B2%7D3%3D0%20%5C%20%5C%26%20%5C%20c_%7B1%7D1&plus;c_%7B2%7D2%3D0)

![equation](https://latex.codecogs.com/gif.latex?c_%7B1%7D&plus;c_%7B2%7D%5Cfrac%7B3%7D%7B2%7D%3D0%20%5C%20%5C%26%20%5C%20c_%7B1%7D&plus;c_%7B2%7D2%3D0)

![equation](https://latex.codecogs.com/gif.latex?c_%7B1%7D%20%3D%20-%5Cfrac%7B3%7D%7B2%7Dc_%7B2%7D%20%5C%20%5C%26%20%5C%20c_%7B1%7D%20%3D%20-2c_%7B2%7D%20%5Cnewline%20%5Ctherefore%20c_%7B1%7D%20%3D%20c_%7B2%7D%20%3D%200%20%5Cnewline%20%5Ctherefore%20linearly%20%5C%20independent)

<br>
<br>

__Subspace__: a vector space that is contained within another vector space: Suppose that *V* and *W* are two vector spaces that have identical definitions of vector addition and scalar multiplication, and that *W* is a subset of *V*, *W ⊆ V*. Then *W* is a subspace of *V*.

Above may be simplified under 3 conditions:
1. 0&#8407; needs to be within the subspace.
2. It must be closed under addition.
3. It must be closed under scalar multiplication.

<br>
<br>

__Closure under scalar multiplication__: suppose x&#8407; is a subset of *V*. *c*x&#8407; for *c* a constant is therefore also a subset of *V*.

<br>
<br>

__Closure under addition__: suppose a&#8407; and b&#8407; is in *V*, then a&#8407; + b&#8407; is also in *V*.

<br>
<br>

__Basis__: a set *S* of vectors in a vector space *V* is called a basis, if the vector set *S* is linearly independent. This may interpreted as the minimum set of vectors needed to span the subspace.

<br>
<br>


__Dot Product__:  scalar sum of the products of the corresponding entries of the vectors.

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Ba%7D%20%5Ccdot%20%5Coverrightarrow%7Bb%7D%20%3D%20a_%7B1%7Db_%7B1%7D&plus;a_%7B2%7Db_%7B2%7D&plus;...&plus;a_%7Bn%7Db_%7Bn%7D)

<br>
<br>

__Vector Length__: The length of a vector may be determined by:

![equation](https://latex.codecogs.com/gif.latex?%5Cleft%20%5C%7C%20%5Coverrightarrow%7Ba%7D%20%5Cright%20%5C%7C%20%3D%20%5Csqrt%7Ba_%7B1%7D%5E%7B2%7D&plus;a_%7B2%7D%5E%7B2%7D&plus;...&plus;a_%7Bn%7D%5E%7B2%7D%7D)

I.t.o. the Dot Product, length of a vector may be found by:

![equation](https://latex.codecogs.com/gif.latex?%5Cleft%20%5C%7C%20%5Coverrightarrow%7Ba%7D%20%5Cright%20%5C%7C%5E%7B2%7D%20%3D%20%5Coverrightarrow%7Ba%7D%5Ccdot%20%5Coverrightarrow%7Ba%7D)

<br>
<br>

__Properties of the Dot Product__: 

1. ![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Ba%7D%5Ccdot%20%5Coverrightarrow%7Bb%7D%20%3D%20%5Coverrightarrow%7Bb%7D%5Ccdot%20%5Coverrightarrow%7Ba%7D)

2. ![equation](https://latex.codecogs.com/gif.latex?%5C%28%20%5Coverrightarrow%7Ba%7D%20&plus;%20%5Coverrightarrow%7Bb%7D%20%5C%29%20%5Ccdot%20%5Coverrightarrow%7Bc%7D%20%3D%20%5Coverrightarrow%7Ba%7D%20%5Ccdot%20%5Coverrightarrow%7Bc%7D%20&plus;%20%5Coverrightarrow%7Bb%7D%20%5Ccdot%20%5Coverrightarrow%7Bc%7D)

3. ![equation](https://latex.codecogs.com/gif.latex?%5C%28%20c%5Coverrightarrow%7Ba%7D%20%5C%29%5Ccdot%20%5Coverrightarrow%7Bb%7D%20%3D%20c%5C%28%20%5Coverrightarrow%7Ba%7D%20%5Ccdot%20%5Coverrightarrow%7Bb%7D%20%5C%29)

<br>
<br>

__Cauchy_Schwarz inequality__: suupose we have two non-zero vectors x&#8407; and y&#8407; such that:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D%2C%5Coverrightarrow%7By%7D%20%5C%20%5Cepsilon%20%5C%20%5Cmathbb%7BR%7D%5E%7Bn%7D). Then the Cauchy-Schwarz inequality states that:

![equation](https://latex.codecogs.com/gif.latex?%5Cleft%20%7C%20%5Coverrightarrow%7Bx%7D%20%5Ccdot%20%5Coverrightarrow%7By%7D%20%5Cright%20%7C%20%5Cleq%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bx%7D%20%5Cright%20%5C%7C%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7By%7D%20%5Cright%20%5C%7C)
