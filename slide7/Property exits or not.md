# Problem Description

You are given an object `obj` and `propName` as arguments. You have to implement the function `checkProperty` which checks whether a given property exists or not, returning true or false.

**Hint:** Use the `hasOwnProperty` method which returns a boolean indicating whether the object has the specified property as its own property.

## Sample Input

```javascript
{ firstName: 'Alex', lastName: 'Powell' }, 'firstName'
```

## Sample Output

```javascript
true
```

**Explanation:**
`firstName` property exists in the object so the output is true.

```javascript
function checkProperty(obj, propName) {
  // You only need to implement this function.
 
}

console.log(checkProperty({ firstName: 'Kushal' }, "firstName"));
