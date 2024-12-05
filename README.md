# Off-by-One Error in Java
This example demonstrates a common off-by-one error in Java when iterating through an array. The error occurs because the loop condition `i <= arr.length` attempts to access an element beyond the array's valid index range. 

The solution corrects the loop condition to ensure that it only iterates within the bounds of the array, preventing the `ArrayIndexOutOfBoundsException`. 