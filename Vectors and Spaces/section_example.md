<h1>Vectors and Spaces Examples</h1>

__1. Given the equations:__

![equations](https://latex.codecogs.com/gif.latex?%5Cbegin%7Balign*%7D%20x_%7B1%7D&plus;x_%7B2%7D&plus;x_%7B3%7D&plus;x_%7B4%7D%3D0%5C%5C%202x_%7B1%7D&plus;x_%7B2%7D&plus;4x_%7B3%7D&plus;3x_%7B4%7D%3D0%5C%5C%203x_%7B1%7D&plus;4x_%7B2%7D&plus;x_%7B3%7D&plus;2x_%7B4%7D%3D0%20%5Cend%7Balign*%7D)

find all possible solutions.

__Solution__

Transforming the equation into a matrix yields:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%201%20%26%201%26%201%26%201%20%26%20%7C0%5C%5C%202%26%201%26%204%26%203%26%20%7C0%5C%5C%203%26%204%26%201%26%202%26%20%7C0%20%5Cend%7Bbmatrix%7D)

which in reduced row echelon form is:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%201%260%263%262%26%7C0%5C%5C%200%261%26-2%26-1%26%7C0%5C%5C%200%260%260%260%26%7C0%20%5Cend%7Bbmatrix%7D)

The complete solution to these equations are:

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bbmatrix%7D%20x_%7B1%7D%5C%5C%20x_%7B2%7D%5C%5C%20x_%7B3%7D%5C%5C%20x_%7B4%7D%20%5Cend%7Bbmatrix%7D%20%3D%20x_%7B3%7D%5Cbegin%7Bbmatrix%7D%20-3%5C%5C%202%5C%5C%201%5C%5C%200%20%5Cend%7Bbmatrix%7D%20&plus;%20x_%7B4%7D%20%5Cbegin%7Bbmatrix%7D%20-2%5C%5C%201%5C%5C%200%5C%5C%201%20%5Cend%7Bbmatrix%7D)
