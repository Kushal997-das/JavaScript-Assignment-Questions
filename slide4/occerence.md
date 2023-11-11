# Problem Description

You are given a string `str` and a substring `k` as arguments.

Find the index of the first occurrence of that substring in the actual string.

Find the index of the last occurrence of that substring in the actual string.

If both these indexes are the same, then return true. Otherwise, return false.

**Hint:** Use `indexOf()` to get the index of the first occurrence of the substring.

**Hint:** Use `lastIndexOf()` to get the index of the last occurrence of the substring.

## Sample Input 1
```plaintext
Next time there won’t be a next time , time
```

## Sample Output 1
```plaintext
false
```

**Explanation:**
"time" is present twice; hence the answer is false.

## Sample Input 2
```plaintext
Now is the time, time
```

## Sample Output 2
```plaintext
true
```

**Explanation:**
"time" is present only once; hence the answer is true.
