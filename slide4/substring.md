# Problem Description

You are given a string `str`, a start position `startInd`, and an end position `endInd` as arguments. You have to implement the function `getSubstr` which trims the string and then returns the substring of that string starting from the start position, and ending 1 before the end position (0-based indexing is followed).

**Hint:** Use the `substring(startIndex, endIndex)` function to get a substring of a string starting from the `startIndex` index and ending at one less than the `endIndex` index.

## Sample Input 1
```plaintext
Hello world!, 1, 4
```

## Sample Output 1
```plaintext
ell
```

**Explanation:**
Substring from index 1 to index 3 is "ell". Note that we are taking till index 3 as it is mentioned in the question that we have to take the substring excluding the second index, i.e., excluding 4.

## Sample Input 2
```plaintext
fiirst, 2, 5
```

## Sample Output 2
```plaintext
irs
```

**Explanation:**
Substring from index 2 to index 4 is "irs".
