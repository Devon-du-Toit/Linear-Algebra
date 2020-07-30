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

4. ![equation](https://latex.codecogs.com/gif.latex?if%20%5C%20%5Coverrightarrow%7Ba%7D%20%5Cperp%20%5Coverrightarrow%7Bb%7D%20%5C%20then%20%5C%20%5Coverrightarrow%7Ba%7D%20%5Ccdot%5Coverrightarrow%7Bb%7D%20%3D%200)

<br>
<br>

__Cauchy_Schwarz inequality__: suppose we have two non-zero vectors x&#8407; and y&#8407; such that:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D%2C%5Coverrightarrow%7By%7D%20%5C%20%5Cepsilon%20%5C%20%5Cmathbb%7BR%7D%5E%7Bn%7D). Then the Cauchy-Schwarz inequality states that:

![equation](https://latex.codecogs.com/gif.latex?%5Cleft%20%7C%20%5Coverrightarrow%7Bx%7D%20%5Ccdot%20%5Coverrightarrow%7By%7D%20%5Cright%20%7C%20%5Cleq%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bx%7D%20%5Cright%20%5C%7C%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7By%7D%20%5Cright%20%5C%7C)

The only case where ![equation](https://latex.codecogs.com/gif.latex?%5Cleft%20%7C%20%5Coverrightarrow%7Bx%7D%20%5Ccdot%20%5Coverrightarrow%7By%7D%20%5Cright%20%7C%20%3D%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bx%7D%20%5Cright%20%5C%7C%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7By%7D%20%5Cright%20%5C%7C)

will be when:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D%20%3D%20c%5Coverrightarrow%7By%7D)

<br>
<br>

__Vector Triangle Inequality__: 

![equation](https://latex.codecogs.com/gif.latex?%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bx%7D&plus;%5Coverrightarrow%7By%7D%20%5Cright%20%5C%7C%5Cleq%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bx%7D%20%5Cright%20%5C%7C&plus;%5Cleft%20%5C%7C%20%5Coverrightarrow%7By%7D%20%5Cright%20%5C%7C)


![tri](https://user-images.githubusercontent.com/68278907/88816735-fef8da80-d1bc-11ea-871c-f932b6773958.png)

The only case where:

![equation](https://latex.codecogs.com/gif.latex?%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bx%7D&plus;%5Coverrightarrow%7By%7D%20%5Cright%20%5C%7C%3D%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bx%7D%20%5Cright%20%5C%7C&plus;%5Cleft%20%5C%7C%20%5Coverrightarrow%7By%7D%20%5Cright%20%5C%7C)

is when:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D%3Dc%5Coverrightarrow%7By%7D%20%5C%20for%20%5C%20c%20%5C%20%5Cepsilon%20%5C%20%5Cmathbb%7BR%7D_%7B%5Cgeq%200%7D)

<br>
<br>

__Angle between vectors__: let a&#8407; and b&#8407; be nonzero vectors such that:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Ba%7D%2C%20%5Coverrightarrow%7Bb%7D%20%5C%20%5Cepsilon%20%5C%20%5Cmathbb%7BR%7D%5E%7Bn%7D)

![tri_neg](https://user-images.githubusercontent.com/68278907/88819711-a62b4100-d1c0-11ea-8c92-e345d4756848.png)

then:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Ba%7D%20%5Ccdot%20%5Coverrightarrow%7Bb%7D%20%3D%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Ba%7D%20%5Cright%20%5C%7C%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bb%7D%20%5Cright%20%5C%7C%20cos%5CTheta)

<br>
<br>

__Plane in R<sup>3</sup>__: A plane in 3-dimensions may be represented by a point on the plane and a vector normal (perpendicular) to the plane:

![equation](https://latex.codecogs.com/gif.latex?n_%7B1%7D%5C%28%20x-x_%7B0%7D%5C%29&plus;n_%7B2%7D%5C%28%20y-y_%7B0%7D%5C%29&plus;n_%7B3%7D%5C%28%20z-z_%7B0%7D%5C%29%3D0)

![equation](https://latex.codecogs.com/gif.latex?for%20%5C%20%5Coverrightarrow%7Bn%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20n_%7B1%7D%5C%5Cn_%7B2%7D%5C%5Cn_%7B3%7D%20%5Cend%7Bbmatrix%7D%20%5C%20the%20%5C%20normal%20%5C%20vector%20%5C%20and%20%5C%20point%20%5C%20%5Coverrightarrow%7Bp%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20x_%7B0%7D%5C%5Cy_%7B0%7D%5C%5Cz_%7B0%7D%20%5Cend%7Bbmatrix%7D%20%5C%20on%20%5C%20the%20%5C%20plane.)
<br>
__To find the normal vector from a given plane in *R<sup>3</sup>*__:

![equation](https://latex.codecogs.com/gif.latex?if%20%5C%20the%5C%20plane%20%5C%20is%20%5C%20given%5C%20by%5C%20Ax&plus;By&plus;Cz%3DD%2C%20%5C%20the%20%5C%20normal%20%5C%20vector%20%5C%20is%20%5C%20%5Cnewline%20%5Coverrightarrow%7Bn%7D%3D%5Cbegin%7Bbmatrix%7D%20A%5C%5C%20B%5C%5CC%5Cend%7Bbmatrix%7D)

<br>
<br>

__Distance of a point from a plane in *R<sup>3</sup>__: 

![equation](https://latex.codecogs.com/gif.latex?given%20%5C%20point%20%5C%20%5Coverrightarrow%7Bp%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20x_%7B0%7D%5C%5Cy_%7B0%7D%20%5C%5Cz_%7B0%7D%20%5Cend%7Bbmatrix%7D%20%5C%20and%20%5C%20plane%20%5C%20Ax&plus;By&plus;Cz%3DD%2C%20%5C%20the%20%5C%20distance%20%5C%20is%20%5C%20given%20%5C%20by%3A%20%5Cnewline%20d%3D%5Cfrac%7BAx_%7B0%7D&plus;By_%7B0%7D&plus;Cz_%7B0%7D-D%7D%7B%5Csqrt%7BA%5E%7B2%7D&plus;B%5E%7B2%7D&plus;C%5E%7B2%7D%7D%7D)

<br>
<br>

__Cross Product__: a binary operation on two vectors in three-dimensional space.

![equation](https://latex.codecogs.com/gif.latex?if%20%5C%20%5Coverrightarrow%7Ba%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20a_%7B1%7D%5C%5Ca_%7B2%7D%5C%5Ca_%7B3%7D%20%5Cend%7Bbmatrix%7D%20%5C%20and%20%5C%20%5Coverrightarrow%7Bb%7D%20%3D%5Cbegin%7Bbmatrix%7D%20b_%7B1%7D%5C%5Cb_%7B2%7D%5C%5Cb_%7B3%7D%20%5Cend%7Bbmatrix%7D%20%5C%20the%20%5C%20cross%20%5C%20product%20%5C%20%5C%28%20%5C%20%5Coverrightarrow%7Ba%7D%5Ctimes%20%5Coverrightarrow%7Bb%7D%20%5C%29%20%5C%20is%3A)

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20a_%7B2%7Db_%7B3%7D-a_%7B3%7Db_%7B2%7D%5C%5C-a_%7B1%7Db_%7B3%7D&plus;a_%7B3%7Db_%7B1%7D%5C%5Ca_%7B1%7Db_%7B2%7D-a_%7B2%7Db_%7B1%7D%20%5Cend%7Bbmatrix%7D)

In relation to the angle  between vectors a&#8407; and b&#8407;:

![equation](https://latex.codecogs.com/gif.latex?%5Cleft%20%5C%7C%20%5Coverrightarrow%7Ba%7D%20%5Ctimes%20%5Coverrightarrow%7Bb%7D%5Cright%20%5C%7C%20%3D%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Ba%7D%20%5Cright%20%5C%7C%20%5Cleft%20%5C%7C%20%5Coverrightarrow%7Bb%7D%20%5Cright%20%5C%7Csin%5CTheta)

<br>
<br>

__Triangle Identities__: the angles and lengths of triangles may be found using the identities contained within the phrase:

__*soh cah toa*__

soh: ![equation](https://latex.codecogs.com/gif.latex?sin%5CTheta%20%3D%20%5Cfrac%7Bopposite%7D%7Bhypotenuse%7D)

cah: ![equation](https://latex.codecogs.com/gif.latex?cos%5CTheta%20%3D%20%5Cfrac%7Badjacent%7D%7Bhypotenuse%7D)

toa: ![equation](https://latex.codecogs.com/gif.latex?tan%5CTheta%20%3D%20%5Cfrac%7Bopposite%7D%7Badjacent%7D)

for the triangle:

![tri_id](https://user-images.githubusercontent.com/68278907/88842049-295b8f80-d1df-11ea-8b2d-6098ec00d7e0.png)


<br>
<br>

__Lagrange's Formula__: Also known as the vector triple product:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Ba%7D%20%5Ctimes%20%5C%28%20%5Coverrightarrow%7Bb%7D%20%5Ctimes%20%5Coverrightarrow%7Bc%7D%20%5C%29%20%3D%20%5Coverrightarrow%7Bb%7D%20%5C%28%20%5Coverrightarrow%7Ba%7D%5Ccdot%20%5Coverrightarrow%7Bc%7D%20%5C%29%20-%20%5Coverrightarrow%7Bc%7D%20%5C%28%20%5Coverrightarrow%7Ba%7D%20%5Ccdot%20%5Coverrightarrow%7Bb%7D%20%5C%29)

<br>
<br>

__Row echelon form__: given a system of equations:

![equations](https://latex.codecogs.com/gif.latex?%5Cbegin%7Balign*%7D%20x_%7B1%7D&plus;2x_%7B2%7D&plus;x_%7B3%7D&plus;x_%7B4%7D%7B%7D%26%3D7%20%5C%5C%20x_%7B1%7D&plus;2x_%7B2%7D&plus;2x_%7B3%7D-x_%7B4%7D%7B%7D%26%3D12%20%5C%5C%202x_%7B1%7D&plus;4x_%7B2%7D&plus;6x_%7B4%7D%7B%7D%26%3D4%20%5Cend%7Balign*%7D)

we may represent this as a *m x n* matrix (m = rows, n = columns):

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%201%26%202%20%26%201%20%26%20%5Cleft.%5Cbegin%7Bmatrix%7D%201%20%5Cend%7Bmatrix%7D%5Cright%7C%20%26%207%5C%5C%201%26%202%20%26%202%20%26%20%5Cleft.%5Cbegin%7Bmatrix%7D%20-1%20%5Cend%7Bmatrix%7D%5Cright%7C%20%26%2012%5C%5C%202%26%204%20%26%200%20%26%20%5Cleft.%5Cbegin%7Bmatrix%7D%206%5Cend%7Bmatrix%7D%5Cright%7C%20%264%5C%5C%20%5Cend%7Bbmatrix%7D)

to achive a reduce row-echelon form, we need to have a matrix of the form:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%201%26%200%20%26%200%20...%26%20%5Cleft.%5Cbegin%7Bmatrix%7D%200%20%5Cend%7Bmatrix%7D%5Cright%7C%20%26%20y_%7B1%7D%5C%5C%200%26%201%20%26%200...%20%26%20%5Cleft.%5Cbegin%7Bmatrix%7D%200%20%5Cend%7Bmatrix%7D%5Cright%7C%20%26%20y_%7B2%7D%5C%5C%200%26%200%20%26%201...%20%26%20%5Cleft.%5Cbegin%7Bmatrix%7D%200%5Cend%7Bmatrix%7D%5Cright%7C%20%26y_%7B3%7D%5C%5C%20...%20%26%20...%20%26...%20%26...%20%26...%5C%5C%200%20%26%200%20%26%200...%20%26%20%5Cleft.%5Cbegin%7Bmatrix%7D%201%5Cend%7Bmatrix%7D%5Cright%7C%20%26%20y_%7Bn%7D%20%5Cend%7Bbmatrix%7D)

<br><br>

 __pivot variable__: if a matrix is in reduced row echelon form, each diagonal __1__ is a pivot variable which gives solutions:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Balign*%7D%20x_%7B1%7D%3Dy_%7B1%7D%20%5C%5Cx_%7B2%7D%3Dy_%7B2%7D%20%5C%5C...%20%5C%5Cx_%7Bn%7D%3Dy_%7Bn%7D%20%5Cend%7Balign*%7D)

<br>
<br>

__Free varaible__: if a reduced row echeon form matrix has any values except 0 located in any other place than the diagonal, that varaible is a free variable.

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%201%26%200%26%20...%26%20x_%7Bn%7D%26%20%7C%20%26y_%7B1%7D%5C%5C%200%26%201%26%20...%26%200%26%20%7C%20%26y_%7B2%7D%5C%5C%20...%26%20...%26%20...%26%20...%26%20%7C%20%26...%5C%5C%200%26%200%26%20...%26%200%26%20%7C%20%26y_%7Bn%7D%20%5Cend%7Bbmatrix%7D)

above, x<sub>n</sub> is a free variable. This implies that x<sub>n</sub> has no unique solution.

This gives the solution vectors:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20x_%7B1%7D%5C%5C%20x_%7B2%7D%5C%5C%20...%5C%5C%20x_%7Bn%7D%20%5Cend%7Bbmatrix%7D%20%3D%20x_%7B2%7D%5Cbegin%7Bbmatrix%7D%200%5C%5C%20y_%7B2%7D%5C%5C%20...%5C%5C%200%20%5Cend%7Bbmatrix%7D&plus;%20...%20&plus;%20x_%7Bn%7D%5Cbegin%7Bbmatrix%7D%20y_%7B1%7D-1%5C%5C%200%5C%5C%20...%5C%5C%201%20%5Cend%7Bbmatrix%7D)
<br>
<br>

__Solutionless system__: if an echelon matrix delivers a zero row with an answer:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%201%26%200%26%20...%26%200%26%20%7C%20%26y_%7B1%7D%5C%5C%200%26%201%26%20...%26%200%26%20%7C%20%26y_%7B2%7D%5C%5C%20...%26%20...%26%20...%26%20...%26%20%7C%20%26...%5C%5C%200%26%200%26%20...%26%200%26%20%7C%20%26c_%7B%7D%20%5Cend%7Bbmatrix%7D%20%5C%20for%20%5C%20a%20%5C%20non-zero%20%5C%20constant%2C%20%5C%20c.)

the system has no solution.

<br>
<br>

__Matrix vector product__: given an *m x n* matrix __A__:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20a_%7B11%7D%26%20a_%7B12%7D%26%20...%26%20a_%7B1n%7D%5C%5C%20a_%7B21%7D%26%20a_%7B22%7D%26%20...%26%20a_%7B2n%7D%5C%5C%20...%26%20...%26%20...%26%20...%5C%5C%20a_%7Bm1%7D%26%20a_%7Bm2%7D%26%20...%26%20a_%7Bmn%7D%7B%7D%20%5Cend%7Bbmatrix%7D)

the matrix may be multiplied by a vector __x&#8407;__:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20x_%7B1%7D%5C%5C%20x_%7B2%7D%5C%5C%20...%5C%5C%20x_%7Bn%7D%20%5Cend%7Bbmatrix%7D)

if the number of columns (n) of the matrix __A__ correspond to the number of elements within the vector __x&#8407;__, <br> such that __A__ x&#8407; =

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20a_%7B11%7Dx_%7B1%7D&plus;%20a_%7B12%7Dx_%7B2%7D&plus;%20...&plus;%20a_%7B1n%7Dx_%7Bn%7D%5C%5C%20a_%7B21%7Dx_%7B1%7D&plus;%20a_%7B22%7Dx_%7B2%7D&plus;%20...&plus;%20a_%7B2n%7Dx_%7Bn%7D%5C%5C%20...%5C%5C%20a_%7Bm1%7Dx_%7B1%7D&plus;%20a_%7Bm2%7Dx_%7B2%7D&plus;%20...&plus;%20a_%7Bmn%7Dx_%7Bn%7D%7B%7D%20%5Cend%7Bbmatrix%7D)

which gives a new vector as solution.

<br>
<br>

__Homogeneous equation__: a matrix __A__ vector x&#8407; product is homogeneous if __A__ x&#8407; = __o&#8407;__.

<br>
<br>

__Nullspace__: given a matrix __A__ the nullspace of __A__ is the set of all vectors which solves  __A__ x&#8407; = __o&#8407;__:

![equation](https://latex.codecogs.com/gif.latex?N%5C%28%20A%5C%29%20%3D%5C%7B%20%5Coverrightarrow%7Bx%7D%20%5C%20%5Cepsilon%20%5C%20%5Cmathbb%7BR%7D%5E%7Bn%7D%20%7C%20A%5Coverrightarrow%7Bx%7D%3D%5Coverrightarrow%7B0%7D%20%5C%7D)

The solutions may be found by using a __o&#8407;__ augmented matrix __A__ and solvinving it via the reduced row echelon form:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20a_%7B11%7D%26%20a_%7B12%7D%20%26...%20%26a_%7B1n%7D%7C%20%260%20%5C%5C%20a_%7B21%7D%26%20a_%7B22%7D%20%26...%20%26a_%7B2n%7D%7C%20%260%20%5C%5C%20...%26%20...%26%20...%26%20%5C%20%5C%20%5C%20%5C%20%7C%20%26...%20%5C%5C%20a_%7Bm1%7D%26%20a_%7Bm2%7D%20%26...%20%26a_%7Bmn%7D%7C%20%260%20%5Cend%7Bbmatrix%7D)

If there are free variables such that the solutions are:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20x_%7B1%7D%5C%5C%20x_%7B2%7D%5C%5C%20...%5C%5C%20x_%7Bn%7D%20%5Cend%7Bbmatrix%7D%20%3D%20x_%7B1%7D%5Cbegin%7Bbmatrix%7D%20c_%7B1%7D%5C%5C%20c_%7B2%7D%5C%5C%20...%5C%5C%20c_%7B3%7D%20%5Cend%7Bbmatrix%7D&plus;%20...%20&plus;%20x_%7Bn%7D%5Cbegin%7Bbmatrix%7D%20c_%7B4%7D%5C%5C%20c_%7B5%7D%5C%5C%20...%5C%5C%20c_%7B6%7D%20%5Cend%7Bbmatrix%7D)

then the homogeneous equation of the matrix is a linear combination of these column vectors, therefore:

![equation](https://latex.codecogs.com/gif.latex?N%20%5C%28%20A%20%5C%29%20%3D%20Span%20%5C%28%20%5Cbegin%7Bbmatrix%7D%20c_%7B1%7D%5C%5C%20c_%7B2%7D%5C%5C%20...%5C%5C%20c_%7B3%7D%20%5Cend%7Bbmatrix%7D%2C%5Cbegin%7Bbmatrix%7D%20c_%7B4%7D%5C%5C%20c_%7B5%7D%5C%5C%20...%5C%5C%20c_%7B6%7D%20%5Cend%7Bbmatrix%7D%20%5C%29)


<br>
<br>

