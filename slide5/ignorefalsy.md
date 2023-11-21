# Problem Description

Sam is a very optimistic lad. He does not like anything which is false in nature. You will be given an array `arr` as an argument. You have to implement the function `removeFalsyValues` which removes all the elements and returns a new array that does not contain any falsy values.

**Hint 1:** Falsy values in JavaScript are false, null, 0, "", '', undefined, and NaN.

**Hint 2:** Create a new array, use a conditional statement along logical operators to check if the element is falsy or not, and accordingly push that element into the array.

## Sample Input 1

```plaintext
7, "ate", "", false, 9
```

## Sample Output 1

```plaintext
[7, "ate", 9]
```

**Explanation:**
"" and false are falsy values. Thus the returned array is [7, "ate", 9].

## Sample Input 2

```plaintext
"a", "b", "c"
```

## Sample Output 2

```plaintext
["a", "b", "c"]
```

**Explanation:**
None of the values in the array are falsy. Thus the returned array is the same as the given array, i.e ["a", "b", "c"].
