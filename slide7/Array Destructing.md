# Problem Description

You are given an array of strings `str` as an argument. You have to implement the function `mergedString` which returns the merged string formed by only the first three elements of the array. We have to use the destructuring syntax to extract the first three array values.

**Note:** The length of the array will always be greater than or equal to three.

**Hint:** The destructuring assignment syntax is a JavaScript expression that makes it possible to unpack values from arrays into distinct variables.

## Sample Input

```plaintext
["code", "for", "good", "vibes", "only"]
```

## Sample Output

```plaintext
code for good
```

**Explanation:**
The output string contains the first three elements of the array along with space to separate them.

```javascript
function mergedString(str) { // You only need to implement this function.
  const [m, n, l] = str;
  
}

console.log(mergedString(['code', 'for', 'good', 'intent']));
