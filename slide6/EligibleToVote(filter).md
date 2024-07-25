## Problem Description

You are given an array of numbers `ages` as an argument. You need to implement a function `canVote` which returns an array of ages that can vote. If the age is greater than or equal to 18, it's considered a valid age to vote; otherwise, it is not valid. Please note that you need to implement this using the `filter` method.

**Hint:** The `filter()` method takes each element in an array and applies a conditional statement against it. If this conditional returns true, the element gets pushed to the output array; otherwise, it will not be included.

### Sample Input

```
[33, 32, 16, 40]
```

### Sample Output

```
[33, 32, 40]
```

### Explanation

16 is less than 18 so can’t vote. All others can vote. Therefore, the output is 33, 32, and 40.
