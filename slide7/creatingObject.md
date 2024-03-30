# Problem Description

You are given `firstName`, `middleName`, and `lastName` as arguments. You have to implement the function `createObject` to create an object with `fullName` as a key and the concatenation of `firstName`, `middleName`, and `lastName` as a value and return the object.

**Hint:** Use the '+' operator to concatenate strings and separate them using " ".

## Sample Input

```plaintext
"Alex", "P", "John"
```

## Sample Output

```plaintext
{ fullName: 'Alex P John' }
```

**Explanation:**
Concatenate the strings ‘Alex’, ‘P’ and ‘Jhon’ to get the full name as 'Alice P John' which is the property of an object returned.

```javascript
function createObject(firstName, middleName, lastName) {
 // Write your code here
}

console.log(createObject("Alex", "P", "John")); // Output: { fullName: 'Alex P John' }
```
