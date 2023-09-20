Problem Description
You are given a 2D array of numbers arr as an argument. You have to implement the function transpose that returns the transpose of the array.


Hint 1: Transposing the array means each row will become a column, and each column will become a row.

Hint 2: First, you create an empty array let’s say "result". Next, traverse over the matrix column-wise and keep on pushing all the values in a column to new array let’ say “col". When you are done with one column, we push the “col" array to our “result" array.


Sample Input
[ [ 1, 1, 1, 1 ], [ 2, 2, 2, 2 ], [ 3, 3, 3, 3 ], [4, 4, 4, 4]]


Sample Output
[ [ 1, 2, 3, 4 ], [ 1, 2, 3, 4 ], [ 1, 2, 3, 4 ], [ 1, 2, 3, 4 ] ]


Explanation
In transpose of a matrix the rows and columns exchange their positions. For example, a number at arr[1][2] will be at position transposedArray[2][1] where transposedArray is the transpose of the array arr.