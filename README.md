# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs because the loop condition `i <= arr.length` causes an attempt to access an index outside the array bounds, leading to an `ArrayIndexOutOfBoundsException`.

The solution involves correcting the loop condition to `i < arr.length` to ensure the loop iterates only within the valid index range of the array.