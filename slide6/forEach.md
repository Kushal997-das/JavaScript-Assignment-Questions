## Problem Description

Implement the function `halfValues()` that:

- Accepts an array of numbers `arr` as an argument
- Returns a new array after dividing every element in the given array `arr` by its index + 1 and storing the value in the new array.

### Hints

- Use `for..each` to iterate through the array.
- Use the `.push()` method to store the elements in the new array.

### Sample Input

```javascript
[2, 3, 4]
```

### Sample Output

```javascript
[2, 1.5, 1.3333333333333333]
```

### Explanation

- The element at index 0 is 2, so `element/index+1` is `2/1 = 2`.
- Similarly, `3/2 = 1.5` and `4/3 = 1.3333333333333333`.

Hence, the result array is: `[2, 1.5, 1.3333333333333333]`.
