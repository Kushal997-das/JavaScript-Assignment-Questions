## Problem Description

You are given a function `copy` which performs copying one object to another, and if any changes are made in the copied object, the original object is also changed. We don't want our original object to be modified. You can assume that all the objects will have the `name` property, which is changed with the string `str` passed in as the argument of the function. 

Please modify the code to ensure that any changes made in the copied object do not reflect in the original object.

**Hint:** Instead of directly copying, use the spread operator (`...`) to create a shallow copy of the object.

```javascript
function copy(data, str) {
    
  // debug this 
  //     const data_copy = data;
      
  //   data_copy.name = str;
  //   if (data === data_copy)
  //      return true;
  //   else
  //      return false;
}
console.log(copy({name: "Kevin", age: 40 }, "Allen"))


```

