# Problem Description

You are given a nested object `obj` and a number `num` as arguments. You have to implement the function `modifyNestedObject` which will modify the `streetNumber` property to `num` in the nested object `address` and return the modified object.

**Hint 1:** Nested objects are the objects that are inside another object.

**Hint 2:** To access nested objects, we use dot or bracket notation. For example, if there is an object named A inside this, we have another object B with property x. To access x, we write `A.B.x`.

## Sample Input

```javascript
{ address: { streetNumber: 5 } }, 8
```

## Sample Output

```javascript
{ address: { streetNumber: 8 } }
```

**Explanation:**
We have modified the `streetNumber` from 5 to 8.

```javascript
function modifyNestedObject(obj, num) {
  // You only need to implement this function.
  
  return obj;
}

console.log(modifyNestedObject({ address: { streetNumber: 5 } }, 8));
