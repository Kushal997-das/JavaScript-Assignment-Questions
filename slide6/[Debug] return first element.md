## Problem Description

You have been given a function `debugShiftAndPop` which should return the first element of the array. In the case of a multidimensional array, it will return the entire inner array. However, there is an error in the code, please debug this problem. You can start by uncommenting the code given in the function.

**Hint 1:** To remove the first element from an array, we use the `shift` method.

**Hint 2:** To remove the last element from an array, we use the `pop` method.

```javascript
function debugShiftAndPop(arr) {
    let result = arr; // You should uncomment this line
    return result; 
}

console.log(debugShiftAndPop([1,2,3,4,"hello"]));
```

```plaintext
Expected Output:
1
```

```plaintext
Expected Output Explanation:
The first element of the array is 1, so the function should return 1.
