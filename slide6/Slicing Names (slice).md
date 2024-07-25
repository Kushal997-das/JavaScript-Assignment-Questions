## Problem Description

Implement the function `getName()` that:

- Accepts three arguments: an array of strings `names`, a number `start`, and a number `end`.
- Returns the elements from `start` to `end` (where the `end` index is exclusive) in the form of an array.

**Note:** You need to implement this problem using the `.slice()` method.

**Hints:** The `.slice()` method returns selected elements in an array, as a new array.

### Sample Input

```
["Ravi", "Faizan", "Kiran", "Shashwat", "Pulkit"], 2, 4
```

### Sample Output

```
["Kiran", "Shashwat"]
```

### Explanation

"Kiran" (index = 2) and "Shashwat" (index = 3) are returned. The element at index 4 ("Pulkit") is excluded as `end` index is exclusive.
