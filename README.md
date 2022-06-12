# matrix

This is a module to replicate matrix object to python and all its mathematical operators

## Installation

>pip install matrix_object

## Documentation

Available methods
-   `.rows()`
-   `.cols()`
-   `.minor(row,col)`
-   `.cofactor(row,col)`
-   `.determinant()`
-   `.transpose()`
-   `.adjoint()`
-   `.inverse()`

Available operators
-   \+
-   \-
-   \*
-   ==
  

**NOTE:** Index of row and col start from 1

## creating a matrix object

```x=matrix(row,col,val)```

allows null and identity instead of val in object creation

>Allows value assignment using `matrix[row,col]=val`

>returns value at current index using `val=matrix[row,col]`

## .rows() 

returns number of rows in the matrix

## .cols()

returns number of columns in the matrix

## .minor(row,col)

returns the minor of element at given row,col

## .cofactor(row,col)

returns the cofactor of element at given row,col

## .determinant()

returns determinant of the matrix

## .transpose()

returns transpose of the given matrix

## .adjoint

returns adjoint of the given matrix

## .inverse()

returns inverse of the given matrix


## using operators

> x+y

returns addition of 2 matrix x and y


>x-y

returns subtraction of 2 matrix x and y


> x*y

returns multiplication of 2 matrix x and y


>x/y

raises exception *operator not available*