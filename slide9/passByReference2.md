
# Problem Description

You are given an array of numbers `arr`, a number `index`, and a number `ele` as arguments. You need to implement the function `replaceElement` which will modify the number at index `index` of the array to `ele`. Please note if the index is greater than (length of the array - 1), insert the element at the end of the array. But we don’t have to return anything, remember how arrays are passed and if any changes are made in the passed array does it reflect in the original array? Think about it.

## Hint
Objects and Arrays are passed by reference, meaning if any changes are made in the passed Object / Array those will be reflected in the original Object / Array.

## Sample Input 1
```javascript
[7, 3, 8, 4], 2, 7
```

## Sample Output 1
```javascript
7, 3, 7, 4
```

## Explanation
The initial element at the index 2 is 8 which is replaced by the number 7.

## Sample Input 2
```javascript
[2, 4, 6, 8], 5, 10
```

## Sample Output 2
```javascript
2, 4, 6, 8, 10
```

## Explanation
Index 5 is greater than (length of array - 1). Thus we will add the number 10 to the end of the array.


## Implement the below function :

```Javascript
  function replaceElement(arr, index, ele) {
    // You only need to implement this function.
    
       
    return arr
  }

  var arr = [9, 1, 7, 4];
  console.log(replaceElement([9, 1, 3, 4], 2, 7))
```
