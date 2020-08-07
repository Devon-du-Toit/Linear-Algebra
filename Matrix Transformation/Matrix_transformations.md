<h1>Matrix Transformation</h1>
<br>
<br>

__Co-Domain__: Consider the following function:

![equation](https://latex.codecogs.com/gif.latex?h%20%3A%20%5Cmathbb%7BR%7D%5E%7Bm%7D%20%5Cmapsto%20%5Cmathbb%7BR%7D%5En)

The function *h* maps domain R<sup>m</sup> to the co-domain R<sup>n</sup>.

<br>
<br>


__Linear Transformation__: A transformation with domain R_<sup>m</sup> and co-domain R<sup>n</sup> is linear if and only if:

![equation](https://latex.codecogs.com/gif.latex?T%20%5C%28%20%5Coverline%7Ba%7D&plus;%5Coverrightarrow%7Bb%7D%5C%29%3DT%5C%28%5Coverrightarrow%7Ba%7D%5C%29&plus;T%5Coverrightarrow%7Bb%7D)

and 

![equation](https://latex.codecogs.com/gif.latex?T%20%5C%28%20c%5Coverline%7Ba%7D%29%3Dc%20T%5C%28%5Coverrightarrow%7Ba%7D%5C%29)

<br>
<br>

__Identity Matrix__: __I<sub>n</sub>__ a matrix with all zero elements, except 1 elements upon its diagonal:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%201%20%26%200%26%20...%260%20%5C%5C%200%26%201%20%26%20...%260%20%5C%5C%20...%26%20...%26...%20%26%20...%5C%5C%200%26%200%26%20...%261%20%5Cend%7Bbmatrix%7D)

Multiplying any vector with the identity matrix gives the vector as result:

![equation](https://latex.codecogs.com/gif.latex?I_n%5Coverrightarrow%7Bx%7D%3D%5Coverrightarrow%7Bx%7D)

<br>
<br>

__Standard Basis for R<sup>n</sup>__: The set of column vectors of an Identy matrix. 

<br>
<br>

__Image of a subsetunder a transformation__: To find the transformation of a shape, the image produced will merely be the superposition of transformations of it's vectors:

![TRANS_1](https://user-images.githubusercontent.com/68278907/89207381-e9b7ed80-d5ba-11ea-9fd5-7f0fdbe88c62.png)

Applying a transformation to the triangle above:

![TRANS_2](https://user-images.githubusercontent.com/68278907/89207289-cd1bb580-d5ba-11ea-9372-ce9289d99277.png)

Thus:

![equations](https://latex.codecogs.com/gif.latex?T%5C%28Shape%20%5C%29%20%3D%20T%5C%28Point_%7B1%7D%5C%29&plus;T%5C%28Point_%7B2%7D%5C%29&plus;...&plus;T%5C%28P_%7Bn%7D%5C%29)

<br>
<br>

__Pre-image__: given a Transformation T : X → Y and a subset B ⊆ Y, the set T<sup>−1</sup>(B) = {x ∈ X : T(x) ∈ B}. Thus, what subset of the domain maps onto the subset of the co-domain under a specific transformation:

![equation](https://latex.codecogs.com/gif.latex?T%20%3D%20%5Cbegin%7Bbmatrix%7D%20c_%7B1%7D%20%26c_%7B2%7D%20%5C%5C%20c_%7B3%7D%26c_%7B4%7D%20%5Cend%7Bbmatrix%7D%2C%20x%20%3D%20%5Cbegin%7Bbmatrix%7D%20x_%7B1%7D%5C%5C%20x_%7B2%7D%20%5Cend%7Bbmatrix%7D%2C%20S%3D%5Cbegin%7Bbmatrix%7D%20c_%7B5%7D%5C%5C%20c_%7B6%7D%20%5Cend%7Bbmatrix%7D)

Given T and S,(given all c_{1}...c_{n}) find x:


![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20c_%7B1%7D%20%26c_%7B2%7D%20%5C%5C%20c_%7B3%7D%26c_%7B4%7D%20%5Cend%7Bbmatrix%7D%20%5Cbegin%7Bbmatrix%7D%20x_%7B1%7D%5C%5C%20x_%7B2%7D%20%5Cend%7Bbmatrix%7D%20%3D%5Cbegin%7Bbmatrix%7D%20c_%7B5%7D%5C%5C%20c_%7B6%7D%20%5Cend%7Bbmatrix%7D)


<br>
<br>

__Kernel__: the set of vectors in the domain of the mapping which are mapped to the zero vector.That is, given a linear map L : V → W between two vector spaces V and W, the kernel of L is the set of all elements v of V for which L(v) = 0&#8407;  or more symbolically:

*ker( L ) = { v ∈ V ∣ L ( v ) = o&#8407; }*

<br>
<br>

__Scalling and Reflecting Transformations__: any desired transformation may be constructed by multiplying the changes for each variable with the identity matrix:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Balign*%7D%20Flip%20%5C%20about%20%5C%20y-axis%3A%20%5C%20x%20%3D%20-x%20%5C%5C%20Stretch%20%5C%20in%20%5C%20y-direction%20%5C%20with%20%5C%20factor%20%5C%202%3A%20y%3D2y%5C%5C%20This%20%5C%20equates%20%5C%20%5Cbegin%7Bbmatrix%7D%201%260%5C%5C%200%261%20%5Cend%7Bbmatrix%7D%20%5Cbegin%7Bbmatrix%7D%20-1%5C%5C2%20%5Cend%7Bbmatrix%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20-1%260%5C%5C%200%262%20%5Cend%7Bbmatrix%7D%20%3D%20T%20%5Cend%7Balign*%7D)

<br>
<br>

__Rotation Transformations in R<sup>2</sup>__: a Transformation rotating about the origin with angle theta:

![equation](https://latex.codecogs.com/gif.latex?T_%7Brotation%7D%20%3D%20T%5Cbegin%7Bbmatrix%7D%20cos%5CTheta%20%26%20-%20sin%5CTheta%20%5C%5C%20sin%5CTheta%20%26%20cos%5CTheta%20%5Cend%7Bbmatrix%7D)

<br>
<br>

__Rotation Transformation in R<sup>3</sup> about the x-axis__: 

![ROT_1](https://user-images.githubusercontent.com/68278907/89219503-2cd08b80-d5d0-11ea-9594-c2612e8fa863.png)

![equation](https://latex.codecogs.com/gif.latex?T_%7Brotation_%7BX%7D%7D%20%3D%20T%5Cbegin%7Bbmatrix%7D%201%20%26%200%20%26%200%5C%5C%200%26%20cos%5CTheta%20%26%20-%20sin%5CTheta%20%5C%5C%200%20%26%20sin%5CTheta%20%26%20cos%5CTheta%20%5Cend%7Bbmatrix%7D)

<br>
<br>

__Projection__: some vector on line L (span{v&#8407;}) where x&#8407; - Proj<sub>L</sub>(x&#8407;) is orthogonal to L.

![proj](https://user-images.githubusercontent.com/68278907/89222412-4a542400-d5d5-11ea-96d1-c350e8697f9d.png)

![equation](https://latex.codecogs.com/gif.latex?Proj_%7BL%7D%5C%28%5Coverrightarrow%7Bx%7D%20%5C%29%20%3D%20%5Cfrac%7B%5Coverrightarrow%7Bx%7D%5Ccdot%20%5Coverrightarrow%7Bv%7D%7D%7B%5Coverrightarrow%7Bv%7D%5Ccdot%20%5Coverrightarrow%7Bv%7D%7D%5Coverrightarrow%7Bv%7D)

<br>
<br>

__Composition of Linear Transformations__: Considering two Transformations __T__ & __S__, the composition of __T__ with __S__:

![equation](https://latex.codecogs.com/gif.latex?T%5Ccirc%20S%3A%20X%20%5Cmapsto%20Z%20%3D%20T%5C%28S%5C%28%20%5Coverrightarrow%7Bx%7D%5C%29%20%5C%29)

If T = B(x&#8407;) and S = A(x&#8407;), then:

![equation](https://latex.codecogs.com/gif.latex?T%5Ccirc%20S%20%3D%20BA%5Coverrightarrow%7Bx%7D)

Notice that if we have 3 transformations: S=B(x&#8407;), T=A(x&#8407;) and H=C(x&#8407;) then:

![equation](https://latex.codecogs.com/gif.latex?S%5Ccirc%20T%20%5Ccirc%20H%20%3D%20BAC%5Coverrightarrow%7Bx%7D)

<br>
<br>

__Product of two Matrices__: Consider two matrices __A__ (m x n) & __B__ (n x k). The product of these two are:

![equation](https://latex.codecogs.com/gif.latex?BA%20%3D%20%5Cbegin%7Bbmatrix%7D%20B%5Coverrightarrow%7Ba%7D_%7B1%7D%20%26%20B%5Coverrightarrow%7Ba%7D_%7B2%7D%20%26%20...%20%26%20B%5Coverrightarrow%7Ba%7D_%7Bn%7D%20%5Cend%7Bbmatrix%7D)

for a&#8407;<sub>n</sub> the column vectors of __A__.

Thus, if:

![equations](https://latex.codecogs.com/gif.latex?B%20%3D%20%5Cbegin%7Bbmatrix%7D%20b_%7B1%7D%20%26b_%7B2%7D%20%5C%5C%20b_%7B3%7D%26%20b_%7B4%7D%20%5Cend%7Bbmatrix%7D%20A%20%3D%20%5Cbegin%7Bbmatrix%7D%20a_%7B1%7D%20%26a_%7B2%7D%20%26a_%7B3%7D%20%5C%5C%20a_%7B4%7D%26%20a_%7B5%7D%20%26%20a_%7B5%7D%20%5Cend%7Bbmatrix%7D)

then:

![equation](https://latex.codecogs.com/gif.latex?BA%20%3D%20%5Cbegin%7Bbmatrix%7D%20%5Cbegin%7Bbmatrix%7D%20b_%7B1%7D%20%26b_%7B2%7D%20%5C%5C%20b_%7B3%7D%26%20b_%7B4%7D%20%5Cend%7Bbmatrix%7D%5Cbegin%7Bbmatrix%7D%20a_%7B1%7D%5C%5C%20a_%7B4%7D%20%5Cend%7Bbmatrix%7D%26%20%5Cbegin%7Bbmatrix%7D%20b_%7B1%7D%20%26b_%7B2%7D%20%5C%5C%20b_%7B3%7D%26%20b_%7B4%7D%20%5Cend%7Bbmatrix%7D%5Cbegin%7Bbmatrix%7D%20a_%7B2%7D%5C%5C%20a_%7B5%7D%20%5Cend%7Bbmatrix%7D%20%26%20%5Cbegin%7Bbmatrix%7D%20b_%7B1%7D%20%26b_%7B2%7D%20%5C%5C%20b_%7B3%7D%26%20b_%7B4%7D%20%5Cend%7Bbmatrix%7D%5Cbegin%7Bbmatrix%7D%20a_%7B3%7D%5C%5C%20a_%7B6%7D%20%5Cend%7Bbmatrix%7D%20%5Cend%7Bbmatrix%7D)

<br>
<br>

__Properties of matrix products__:

ABC = (AB)C = A(BC)

ABC ≠ ACB ≠ BCA ≠ CBA etc.

A(B+C) = AB+AC

<br>
<br>

__Inverse of a function__: the function __f__ is invertible if and only if there exists a function:

![equation](https://latex.codecogs.com/gif.latex?f%5E%7B-1%7D%3AY%20%5Cmapsto%20X)

such that

![equation](https://latex.codecogs.com/gif.latex?f%5E%7B-1%7D%5Ccirc%20f%20%3D%20I_%7Bx%7D)

for I<sub>x</sub> the identity matrix over x, and

![equation](https://latex.codecogs.com/gif.latex?f%5Ccirc%20f%5E%7B-1%7D%3D%20I_%7By%7D)


for I<sub>y</sub> the identity matrix over y.

<br>
<br>

__Invertibility__: if __f__ is invertible:

![equation](https://latex.codecogs.com/gif.latex?%5Cexists%20%5C%20%28there%20%5C%20exists%29%20%5C%20some%20%5C%20function%20%5C%20f%5E%7B-1%7D%20%3AY%20%5Cmapsto%20X%20%5C%20such%20%5C%20that%20%5C%20f%5E%7B-1%7D%20%5Ccirc%20f%20%3D%20I_%7Bx%7D)

which implies a unique solution to f(x)=y is necessary for __f__ to be invertible.

<br>
<br>

__Linear Invertibility__:

T<sup>-1</sup>(__a__+__b__) = T<sup>-1</sup>(__a__)+T<sup>-1</sup>(__b__)

T<sup>-1</sup>(c__a__) = cT<sup>-1</sup>(__a__)

__Surjective / "onto"__: a function __f__ is surjective/ maps onto if:

![equation](https://latex.codecogs.com/gif.latex?for%20%5C%20every%20%5C%20y%20%5C%20%5Cepsilon%20%5C%20Y%20%5C%20%5Cexists%20%5C%20at%20%5C%20least%20%5C%201%20%5C%20x%20%5C%20%5Cepsilon%20%5C%20X%20%3A%20%28such%5C%20that%29%20%5C%20f%28x%29%3Dy)

Alternatively, a function __f__ is surjective/ maps onto if and only if:

![equation](https://latex.codecogs.com/gif.latex?for%20%5C%20a%20%5C%20matrix%20%5C%20A.%20%5C%20rref%28A%29%20%5C%20has%20%5C%20a%20%5C%20pivot%20%5C%20column%20%5C%20in%20%5C%20every%20%5C%20row%20.)


<br>
<br>

__Injective / "one-to-one"__: the function __f__ is injective/ "one-to-one" if:

![equation](https://latex.codecogs.com/gif.latex?for%20%5C%20every%20%5C%20y%20%5C%20%5Cepsilon%20%5C%20Y%20%5C%20%5Cexists%20%5C%20at%20%5C%20most%20%5C%201%20%5C%20x%20%5C%20%5Cepsilon%20%5C%20X%20%3A%20%5C%20f%28x%29%3Dy)

If a matrix __A__ is injective/ one-to-one, then the columns of __A__ must be linearly independent.

<br>
<br>

__Invertibility i.t.o surjectivity an injectivity__: for function __f__ to be invertible, it needs to be both surjective and injective.

<br>
<br>

__Nonhomogeneous equation__: A set of linear equations for which the solutions isn't the zero vector, consider a matrix __A__ and vectors __x__ & __b__:

![equation](https://latex.codecogs.com/gif.latex?A%5Coverrightarrow%7Bx%7D%3D%5Coverrightarrow%7Bb%7D)

To solve this, reduce A to echelon form and augment it with __b__:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20rref%28A%29%26%7C%20%5C%20%5Coverrightarrow%7Bb%7D%20%5Cend%7Bbmatrix%7D)

This will have the solutions:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D%20%3D%20%5Coverrightarrow%7Bb%7D%20&plus;%20a%5Coverrightarrow%7Bn%7D_%7B1%7D&plus;%20a%5Coverrightarrow%7Bn%7D_%7B2%7D&plus;...&plus;%20a%5Coverrightarrow%7Bn%7D_%7Bn%7D)

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Bx%7D%20%3D%20%5Coverrightarrow%7Bx%7D_%7Bp%7D&plus;%5Coverrightarrow%7Bx%7D_%7Bn%7D)

where __b__ is a particular solution (column vector not related to a free variable = x<sub>p</sub>) and the rest of the equation is a nullspace vector = x<sub>n</sub>.

<br>
<br>

__Invertible matrix__: A matrix may only be inverted if it is an nxn matrix with a reduced echelon form equal to the Identity matrix.

To find a matrix's invers, augment it with the identity matrix and reduce it to echelon form:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20A%20%26%20%7C%20%5C%20I_%7Bn%7D%20%5Cend%7Bbmatrix%7D)

which reduces to:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20rref%28A%29%20%26%20%7C%20%5C%20A%5E%7B-1%7D%20%5Cend%7Bbmatrix%7D)

<br>
<br>

__Determinant__: for a 2x2 matrix:

![equation](https://latex.codecogs.com/gif.latex?For%20%5C%20matrix%20%5C%20A%3D%5Cbegin%7Bbmatrix%7D%20a%20%26b%20%5C%5C%20c%26d%20%5Cend%7Bbmatrix%7D%20%5C%20%2CDet%28A%29%3D%7CA%7C%3D%5Cbegin%7Bvmatrix%7D%20a%20%26%20b%20%5C%5C%20c%20%26%20d%20%5Cend%7Bvmatrix%7D%20%3D%20ad-bc)

for a 3x3 matrix:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bvmatrix%7D%20A%20%5Cend%7Bvmatrix%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%20a_%7B11%7D%20%26%20a_%7B12%7D%20%26%20a_%7B13%7D%20%5C%5C%20a_%7B21%7D%20%26%20a_%7B22%7D%20%26%20a_%7B23%7D%20%5C%5C%20a_%7B31%7D%20%26%20a_%7B32%7D%20%26%20a_%7B33%7D%20%5Cend%7Bvmatrix%7D%20%5C%5C%20%3D%20a_%7B11%7D%5Cbegin%7Bvmatrix%7D%20a_%7B22%7D%20%26a_%7B23%7D%20%5C%5C%20a_%7B32%7D%26a_%7B33%7D%20%5Cend%7Bvmatrix%7D%20-%20a_%7B12%7D%5Cbegin%7Bvmatrix%7D%20a_%7B21%7D%20%26a_%7B23%7D%20%5C%5C%20a_%7B31%7D%26a_%7B33%7D%20%5Cend%7Bvmatrix%7D%20&plus;%20a_%7B13%7D%5Cbegin%7Bvmatrix%7D%20a_%7B21%7D%20%26a_%7B22%7D%20%5C%5C%20a_%7B31%7D%26a_%7B32%7D%20%5Cend%7Bvmatrix%7D)

<br>
<br>


__Determinent when row multiplied by scalar__: the determinent of a matrix row multiplied by a scalar is:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bvmatrix%7D%20kA%20%5Cend%7Bvmatrix%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%20a_%7B11%7D%20%26%20a_%7B12%7D%20%26%20...%20%26%20a_%7B1n%7D%20%5C%5C%20ka_%7B21%7D%20%26%20ka_%7B22%7D%20%26%20...%20%26%20ka_%7B2n%7D%20%5C%5C%20...%26%20%26%26...%20%5C%5C%20a_%7Bn1%7D%20%26%20a_%7Bn2%7D%20%26%20...%20%26%20a_%7Bnn%7D%20%5Cend%7Bvmatrix%7D%20%5C%5C%20%3D%20%28-1%29%5E%7Bi&plus;1%7Da_%7Bi1%7Ddet%28Ai1%29&plus;a_%7Bi2%7Ddet%28Ai2%29&plus;...&plus;a%7Bin%7Ddet%28A_in%29)

<br>
<br>

__Determinent when rows are added__: considering a particular case where two matrices are exactly similar, except for 1 row each, the determinent of the sum of these two matrices are:

![equation](https://latex.codecogs.com/gif.latex?X%3D%20%5Cbegin%7Bvmatrix%7D%20a_%7B11%7D%20%26%20a_%7B12%7D%20%26%20...%26a_%7B1n%7D%20%5C%5C%20x_%7B1%7D%20%26x_%7B2%7D%20%26%20...%26%20x_%7Bn%7D%20%5C%5C%20...%26%20%26%20%26...%5C%5C%20a_%7Bn1%7D%20%26%20a_%7Bn2%7D%20%26%20...%26%20a_%7Bnn%7D%20%5Cend%7Bvmatrix%7D%20%2C%20%5C%20Y%3D%20%5Cbegin%7Bvmatrix%7D%20a_%7B11%7D%20%26%20a_%7B12%7D%20%26%20...%26a_%7B1n%7D%20%5C%5C%20y_%7B1%7D%20%26y_%7B2%7D%20%26%20...%26%20y_%7Bn%7D%20%5C%5C%20...%26%20%26%20%26...%5C%5C%20a_%7Bn1%7D%20%26%20a_%7Bn2%7D%20%26%20...%26%20a_%7Bnn%7D%20%5Cend%7Bvmatrix%7D%20%5C%5C%20%2C%20%5C%20Z%20%3D%20%5Cbegin%7Bvmatrix%7D%20a_%7B11%7D%20%26%20a_%7B12%7D%20%26%20...%26a_%7B1n%7D%20%5C%5C%20x_%7B1%7D&plus;y_%7B1%7D%20%26x_%7B2%7D&plus;y_%7B2%7D%20%26%20...%26%20x_%7Bn%7Dy_%7Bn%7D%20%5C%5C%20...%26%20%26%20%26...%5C%5C%20a_%7Bn1%7D%20%26%20a_%7Bn2%7D%20%26%20...%26%20a_%7Bnn%7D%20%5Cend%7Bvmatrix%7D)

det(Z)=

![equation](https://latex.codecogs.com/gif.latex?%5Csum_%7Bj%3D1%7D%5E%7Bn%7D%28-1%29%5E%7Bi&plus;j%7D%20%28x_%7Bj%7D&plus;y_%7Bj%7D%29%5Cbegin%7Bvmatrix%7D%20A_%7Bij%7D%20%5Cend%7Bvmatrix%7D)

<br>
<br>

__Duplicate row determinant__: Consider a matrix __A__ which has the rows:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bvmatrix%7D%20a_%7B11%7D%20%26a_%7B12%7D%20%26...%20%26a_%7B1n%7D%20%5C%5C%20a_%7B11%7D%20%26a_%7B12%7D%20%26...%20%26a_%7B1n%7D%20%5C%5C%20...%20%26%20%26%20%26%20...%5C%5C%20i_%7B1%7D%20%26i_%7B2%7D%20%26...%20%26i_%7Bn%7D%20%5C%5C%20j_%7B1%7D%20%26j_%7B2%7D%20%26...%20%26j_%7Bn%7D%20%5C%5C%20...%20%26%20%26%20%26%20...%5C%5C%20a_%7B11%7D%20%26a_%7B12%7D%20%26...%20%26a_%7B1n%7D%20%5Cend%7Bvmatrix%7D)

if we denote row 1 by:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Br%7D_%7B1%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20a_%7B11%7D%20%26%20a_%7B12%7D%20%26%20...%20%26%20a_%7B1n%7D%20%5Cend%7Bbmatrix%7D)

then __A__ may be written as:

![equation](https://latex.codecogs.com/gif.latex?A%20%3D%20%5Cbegin%7Bbmatrix%7D%20%5Coverrightarrow%7Br%7D_%7B1%7D%5C%5C%20%5Coverrightarrow%7Br%7D_%7B2%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bi%7D%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bj%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bn%7D%5C%5C%20%5Cend%7Bbmatrix%7D)

if we then have a matrix __B__ such that __B__ is similar to __A__ except for a row switch:

![equation](https://latex.codecogs.com/gif.latex?B%20%3D%20%5Cbegin%7Bbmatrix%7D%20%5Coverrightarrow%7Br%7D_%7B1%7D%5C%5C%20%5Coverrightarrow%7Br%7D_%7B2%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bj%7D%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bi%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bn%7D%5C%5C%20%5Cend%7Bbmatrix%7D)

then:

*det(A) = -det(B)*

this in turns implies:

*matrices with duplicate rows are not invertible* and *the determinant of a matrix with duplicate rows = 0*.

<br>
<br>

__Determinant after row operations__: consider a matrix:

![equation](https://latex.codecogs.com/gif.latex?B%3D%5Cbegin%7Bvmatrix%7D%20%5Coverrightarrow%7Br%7D_%7B1%7D%5C%5C%20%5Coverrightarrow%7Br%7D_%7B2%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bj%7D%5C%5C%20...%5C%5C%20-c%5Coverrightarrow%7Br%7D_%7Bj%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bn%7D%20%5Cend%7Bvmatrix%7D)

According to determinant scalar multlipication:

![equation](https://latex.codecogs.com/gif.latex?B%20%3D%20-c%20%5Cbegin%7Bbmatrix%7D%20%5Coverrightarrow%7Br%7D_%7B1%7D%5C%5C%20%5Coverrightarrow%7Br%7D_%7B2%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bj%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bj%7D%5C%5C%20...%5C%5C%20%5Coverrightarrow%7Br%7D_%7Bn%7D%5C%5C%20%5Cend%7Bbmatrix%7D)

and as there is a duplicate row:

![equation](https://latex.codecogs.com/gif.latex?det%28B%29%3D0)

<br>
<br>

__Upper Triangle Determinant__: Consider an upper nxn triangle matrix:

![equation](https://latex.codecogs.com/gif.latex?A%20%3D%20%5Cbegin%7Bvmatrix%7D%20a_%7B11%7D%20%26%20a_%7B12%7D%26%20...%20%26a_%7B1n%7D%20%5C%5C%200%20%26%20a_%7B22%7D%26%20...%20%26a_%7B2n%7D%20%5C%5C%200%20%26%200%20%26%20...%20%26a_%7B3n%7D%20%5C%5C%20...%26%20...%20%26%20...%20%26%20...%5C%5C%200%26%200%26%20...%26%20a_%7Bnn%7D%20%5Cend%7Bvmatrix%7D)

the determinent will be equal to the product of it's diagonal:


![equation](https://latex.codecogs.com/gif.latex?det%28A%29%20%3D%20a_%7B11%7Da_%7B22%7D...a_%7Bnn%7D)

<br>
<br>

__Row operations and determinants__: performing row operations do not change the determinant:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bvmatrix%7D%201%20%262%20%261%20%5C%5C%201%263%20%262%20%5C%5C%201%264%20%264%20%5Cend%7Bvmatrix%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%201%20%262%20%261%20%5C%5C%200%261%20%261%20%5C%5C%200%260%20%261%20%5Cend%7Bvmatrix%7D%20%3D%201)

Note that switch rows equals the negative of determinant.

<br>
<br>

__Determinant and Area of a Parallelogram__: consider a 2x2 matrix __A__:

![equation](https://latex.codecogs.com/gif.latex?A%20%3D%20%5Cbegin%7Bbmatrix%7D%20a%20%26%20b%5C%5C%20c%26%20d%20%5Cend%7Bbmatrix%7D)

![equation](https://latex.codecogs.com/gif.latex?let%20%5Coverrightarrow%7Bv%7D_%7B1%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20a%20%5C%5C%20c%20%5Cend%7Bbmatrix%7D%20%5C%20and%20%5C%20%5Coverrightarrow%7Bv%7D_%7B2%7D%3D%20%5Cbegin%7Bbmatrix%7D%20b%5C%5C%20d%20%5Cend%7Bbmatrix%7D)

we may consider the matrix's two column vectors as two vectors forming half of a parallelogram:

![parallelogram](https://user-images.githubusercontent.com/68278907/89453413-82876e00-d75f-11ea-96ca-2304945884cc.png)


The area of the parallelogram may be determined with:

![equation](https://latex.codecogs.com/gif.latex?A%20%3D%20b%5Cperp%20h)

for:

![parallelogram_2](https://user-images.githubusercontent.com/68278907/89536525-553ace80-d7f8-11ea-90ee-06158c26ae91.png)


To find 

![equation](https://latex.codecogs.com/gif.latex?%5Cperp%20h%5E%7B2%7D%20%3D%20%5Coverrightarrow%7Bv%7D_%7B1%7D%5E%7B2%7D-Proj_%7BL%7D%5Coverrightarrow%7Bv%7D_%7B2%7D%5E%7B2%7D)

which simplify to:

![equation](https://latex.codecogs.com/gif.latex?A%3D%5Cbegin%7Bvmatrix%7D%20det%28A%29%20%5Cend%7Bvmatrix%7D)

<br>
<br>

__Determinant as scaling factor__: consider a transformation:

![area_2](https://user-images.githubusercontent.com/68278907/89563483-ca6bcb00-d81b-11ea-98e3-a8b4b03c1f04.png)

to:

![area_3](https://user-images.githubusercontent.com/68278907/89563617-ff781d80-d81b-11ea-93a3-2a67271bd921.png)

the relationship between the area of the rectangle and image under T is:

![equation](https://latex.codecogs.com/gif.latex?for%20%5C%20transformation%20%5C%20T%5Coverrightarrow%7Bx%7D%20%3D%20B%5Coverrightarrow%7Bx%7D%5C%5C%20Area_%7Brectangle%7D%20%3D%20%5Cbegin%7Bvmatrix%7DA%20%5C%20det%28B%29%20%5Cend%7Bvmatrix%7D%20%5C%5C)

<br>
<br>

__Transpose of a matrix__: Consider a mxn matrix __A__:

![equation](https://latex.codecogs.com/gif.latex?A%20%3D%20%5Cbegin%7Bbmatrix%7D%20a_%7B11%7D%20%26a_%7B12%7D%20%26%20...%20%26%20a_%7B1n%7D%5C%5C%20a_%7B21%7D%20%26a_%7B22%7D%20%26%20...%20%26%20a_%7B2n%7D%5C%5C%20...%20%26...%20%26%20...%26%20...%5C%5C%20a_%7Bm1%7D%20%26a_%7Bm2%7D%20%26%20...%20%26%20a_%7Bmn%7D%5C%5C%20%5Cend%7Bbmatrix%7D)

The transpose will be a nxm matrix:

![equation](https://latex.codecogs.com/gif.latex?A%5E%7B%5Cdagger%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20a_%7B11%7D%20%26%20a_%7B21%7D%20%26%20...%20%26%20a_%7Bm1%7D%5C%5C%20a_%7B12%7D%20%26a_%7B22%7D%20%26%20...%20%26%20a_%7Bm2%7D%5C%5C%20...%20%26...%20%26%20...%26%20...%5C%5C%20a_%7B1n%7D%26a_%7B2n%7D%20%26%20...%20%26%20a_%7Bmn%7D%5C%5C%20%5Cend%7Bbmatrix%7D)

<br>
<br>

__Transpose Properties__:

![equation](https://latex.codecogs.com/gif.latex?det%28A%5E%7B%5Cdagger%7D%29%20%3D%20det%28A%29)

![equation](https://latex.codecogs.com/gif.latex?%28AB%29%5E%7B%5Cdagger%7D%20%3D%20B%5E%7B%5Cdagger%7DA%5E%7B%5Cdagger%7D)

![equation](https://latex.codecogs.com/gif.latex?%28A&plus;B%29%5E%7B%5Cdagger%7D%20%3D%20A%5E%7B%5Cdagger%7D&plus;B%5E%7B%5Cdagger%7D)

<br>
<br>

__Rowspace__: The columnspace of a transpose matrix:

![equation](https://latex.codecogs.com/gif.latex?C%28A%5E%7B%5Cdagger%7D%29%20%3D%20Rowspace%20%5C%20of%20%5C%20A)

<br>
<br>
