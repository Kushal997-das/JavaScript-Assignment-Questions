# Problem Description

You are given `obj` and `propName` as arguments. You have to implement the function `deleteProperty` which will return the object after deleting the property. The property that needs to be deleted is given in the `propName`.

**Hint 1:** The delete operator removes a property from an object.

**Hint 2:** When using a dot, the part after the dot must be a valid variable name, and it directly names the property. When using square brackets, the expression between the brackets is evaluated to get the property name.

## Sample Input

```javascript
{ firstName: 'Sachin', middleName: 'Ramesh', lastName: 'Tendulkar'}, 'middleName'
```

## Sample Output

```javascript
{ firstName: 'Sachin', lastName: 'Tendulkar' }
```

**Explanation:**
`middleName` property is deleted. Therefore, the output is { firstName: 'Sachin', lastName: 'Tendulkar' }.

```javascript
function deleteProperty(obj, propName) {
  // You only need to implement this function.
  
  return obj;
}

console.log(deleteProperty({ firstName: 'Sachin', middleName: 'Ramesh', lastName: 'Tendulkar'}, 'middleName'));




