# Problem Description

Given `len` and `bre` as arguments denoting the length and breadth respectively, you need to implement the function `calculateArea` to find the area of a rectangle. If the arguments passed are negative numbers, convert them to their absolute values, and if either of them is 0, return "Not Possible".

**Note:** You are given the function to implement in the form of an arrow function. Notice the syntax.

**Hint 1:** The area of a rectangle is calculated using the formula: `Area = length * breadth`.

**Hint 2:** `Math.abs()` function returns the absolute value of a number.

**NOTE:** Solve this using `Arrow` function.

## Sample Input 1
```plaintext
2, 3
```

## Sample Output 1
```plaintext
6
```

**Explanation:**
The area of the rectangle is `length * breadth`, i.e., `2 * 3 = 6`.

## Sample Input 2
```plaintext
10, 0
```

## Sample Output 2
```plaintext
Not Possible
```

**Explanation:**
Since breadth is given as 0, we can’t calculate the area.

## Sample Input 3
```plaintext
-5, 8
```

## Sample Output 3
```plaintext
40
```

**Explanation:**
The area of the rectangle is length * breadth, i.e., 5 * 8 = 40. Negative value for length is converted to its absolute value.
