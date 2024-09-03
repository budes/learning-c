Arrays are kind of different from what i saw on js

To make an array of something -> type name[size] 
- Type -> Type of the elements you will put inside the array
	- Int, float, bool, string, char
- [size] -> The size of the array, it's got an specified size and it won't exceed it

To add things to the array -> name[index] = value
- 0 <= index < size

--------------------------

To multidimensional arrays you would thing it's redundant, and mostly from what i've seen it really is.

Basically, it's the same thing: type name[[x][y]
- x -> The number of arrays inside each array
	- It can also just be []
- y -> The number of type elements inside of each array

--------------------------

If we want to put values straight onto them, we can use the following notations
- type array[n] = {element⁰, element¹ ... , element^n-1} 
- type array[[x][n] ] = {
  {element⁰, element¹ ... , element^n-1},     \\
  {element⁰, element¹ ... , element^n-1},      | -> x times
  {element⁰, element¹ ... , element^n-1}      / 
  }
- type array[[x][n] ] = {element⁰, element¹ ... , element^n-1, element⁰, element¹ ... , element^n-1, element⁰, element¹ ... , element^n-1} -> x times

