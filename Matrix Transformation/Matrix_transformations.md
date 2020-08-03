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


