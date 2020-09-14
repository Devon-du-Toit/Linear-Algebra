<h1>Alternate Coordinate Systems</h1>
<br>
<br>

__Orthogonal Complement__: Let V be be some subspace of R<sup>n</sup>, then:

![equation](https://latex.codecogs.com/gif.latex?V%5Cperp%20%3D%5C%7B%20%5Coverrightarrow%7Bx%7D%20%5C%20%5Cepsilon%20%5C%20%5Cmathbb%7BR%7D%5E%7Bn%7D%20%5C%20%7C%20%5C%20%5Coverrightarrow%7Bx%7D%5Ccdot%20%5Coverrightarrow%7Bv%7D%20%3D%200%20%5C%20%5Cforall%20%5C%20%5Coverrightarrow%7Bv%7D%20%5C%20%5Cepsilon%20%5C%20V%20%5C%7D)

The nullspace of a matrix is the orthogonal complement of its rowspace:

![equation](https://latex.codecogs.com/gif.latex?N%28A%29%3D%5Cleft%28%20C%28A%5E%7BT%7D%29%20%5Cright%29%5E%7B%5Cperp%7D)

similarly:

![equation](https://latex.codecogs.com/gif.latex?N%28B%5E%7BT%7D%29%3DC%28B%29%5E%7B%5Cperp%7D)

We may find the number of rows of a matrix by:

![equation](https://latex.codecogs.com/gif.latex?dim%28V%29&plus;dim%28V%5E%7B%5Cperp%7D%29%3Dn)

Any vector within R<sup>n</sup> may be represented as a sum of a vector in the subspace and the subspace's complement:

![equation](https://latex.codecogs.com/gif.latex?%5Coverrightarrow%7Ba%7D%20%3D%20%5Coverrightarrow%7Bv%7D&plus;%5Coverrightarrow%7Bx%7D)

For *x&#8407;* the orthogonal complement of *v&#8407;* .

<br>
<br>

__Unique Solution to Ax=b__: If *b&#8407;* ∈ C(A) there exists a unique member of the rowspace of A ( C(A<sup>T</sup>) ), *r&#8407;<sub>0</sub>* : *r&#8407;<sub>0</sub>* is the shortest length solution to A*x&#8407;*=*b&#8407;*.

![equation](https://latex.codecogs.com/gif.latex?Let%5C%20%5Coverrightarrow%7Br%7D_%7B0%7D%5C%20%5Cepsilon%20%5C%20C%28A%5E%7BT%7D%29)

then:

![equation](https://latex.codecogs.com/gif.latex?A%5Coverrightarrow%7Br%7D_%7B0%7D%20%3D%20%5Coverrightarrow%7Bb%7D)

<br>
<br>

__Eigenvectors and Eigenvalues__: consider the transformation: 

![equation](https://latex.codecogs.com/gif.latex?T%28%5Coverrightarrow%7Bv%7D%29%20%3D%20%5Clambda%5Coverrightarrow%7Bv%7D)

where:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Balign*%7D%20%5Coverrightarrow%7Bv%7D%20%3D%20eigenvector%20%5C%5C%20%5Clambda%20%3D%20eigenvalue%20%5Cend%7Balign*%7D)

<br>
<br>

__Determining Eigenvalues__: 

![equation](https://latex.codecogs.com/gif.latex?A%28%5Coverrightarrow%7Bv%7D%29%20%3D%20%5Clambda%5Coverrightarrow%7Bv%7D%20%5C%20for%20%5C%20non-zero%20%5C%20%5Coverrightarrow%7Bv%7D%20%5C%20iff.%20%5C%20%5Cdet%28%5Clambda%20I_%7Bn%7D-A%29%3D0)

This would imply:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bvmatrix%7D%20a_%7B11%7D-%20%5Clambda%20%26a_%7B12%7D%26...%20%26a_%7B1n%7D%20%5C%5C%20a_%7B21%7D%20%26a_%7B22%7D-%20%5Clambda%26...%20%26a_%7B2n%7D%20%5C%5C%20...%26...%26...%26...%20%5C%5C%20a_%7Bm1%7D%20%26a_%7Bm2%7D%20%26...%26a_%7Bmn%7D%20%5Clambda%20%5Cend%7Bvmatrix%7D%3D0)

<br>
<br>

__Eigenspace__: for any eigenvalue, λ:

![equation](https://latex.codecogs.com/gif.latex?E_%7B%5Clambda%7D%20%3D%20N%28%5Clambda%20I_%7Bn%7D-A%29)

<br>
<br>

__Determining Eigenvectors__: 

![equation](https://latex.codecogs.com/gif.latex?%28%5Clambda%20I_%7Bn%7D-A%29%5Coverrightarrow%7Bv%7D%3D%5Coverrightarrow%7B0%7D)

<br>
<br>

__Projection onto subspace__: Let V be a subspace of R<sup>n</sup>, tus V<sup>⊥</sup> is also a subspace. If *x&#8407;* ∈ R<sup>n</sup>: *x&#8407;*=*v&#8407;*+*w&#8407;* where *v&#8407;* ∈ V and *w&#8407;* ∈ V<sup>⊥</sup>, then:

![equation](https://latex.codecogs.com/gif.latex?Proj_%7BV%7D%5Coverrightarrow%7Bx%7D%3D%5Coverrightarrow%7Bv%7D)

and 

![equation](https://latex.codecogs.com/gif.latex?Proj_%7BV%5E%7B%5Cperp%7D%7D%5Coverrightarrow%7Bx%7D%3D%5Coverrightarrow%7Bw%7D)

The transformation of a projection may be found by:

![equation](https://latex.codecogs.com/gif.latex?Proj_%7BV%7D%5Coverrightarrow%7Bx%7D%3DA%28A%5E%7BT%7DA%29%5E%7B-1%7DA%5E%7BT%7D%5Coverrightarrow%7Bx%7D)

<br>
<br>

__Least Squares Approximation__:  To find x* where Ax*=b is as close to b as possible, if Ax=b has no solution:

![equation](https://latex.codecogs.com/gif.latex?Ax%5E%7B*%7D%3DProj_%7BC%28A%29%7D%5Coverrightarrow%7Bb%7D)

or simpler put:

![equation](https://latex.codecogs.com/gif.latex?A%5E%7BT%7DAx%5E%7B*%7D%3DA%5E%7BT%5Coverrightarrow%7Bb%7D%7D)

