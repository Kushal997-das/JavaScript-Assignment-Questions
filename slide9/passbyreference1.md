# Problem Description

You are given an array of numbers `arr` as an argument. You need to implement the function `manipulatingArray` which will modify the numbers of the array such that if the number is even, it adds 5 else it multiplies 5. But we don’t have to return anything, remember how arrays are passed and if any changes are made in the passed array does it reflect in the original array? Think about it.

**Hint:** Objects and Arrays are passed by reference, meaning if any changes are made in the passed Object / Array those will be reflected in the original Object / Array.

## Sample Input
```javascript
7, 3, 8, 4
```

## Sample Output
```javascript
35, 15, 13, 9
```

**Explanation:**
7 is odd and thus it is multiplied by 5 and the new value becomes 35.

3 is odd and thus it is multiplied by 5 and the new value becomes 15.

8 is even and thus it is added by 5 and the new value becomes 13.

4 is even and thus it is added by 5 and the new value becomes 9.


