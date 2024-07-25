## Problem Description

Implement the function `remove()` that:

- Accepts three arguments: an array of strings `fruits`, a number `startIndex`, and a number `deleteCount`.
- Removes the elements starting from `startIndex` until the number of elements to be removed is equal to `deleteCount`.
- Returns the new array after modification.

**Note:** You need to implement this problem using the `.splice()` method.

**Hints:** The `.splice()` method changes the contents of an array by removing or replacing existing elements and/or adding new elements.

### Sample Input

```
["Banana", "Orange", "Apple", "Mango", "Kiwi"], 2, 2
```

### Sample Output

```
["Banana", "Orange", "Kiwi"]
```

### Explanation

"Apple" and "Mango" are removed from the original array.
