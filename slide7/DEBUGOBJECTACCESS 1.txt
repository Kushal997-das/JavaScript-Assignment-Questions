Problem Description
You have been given a function getAge which should return the age of the object obj but there is an error in the code, please debug this problem. You can start by uncommenting the code given in the function and make sure we are using bracket notation to access the property of the object.

Assumption: There will always age property associated with the object obj which is passed as an argument.


Hint: When using square brackets, the expression between the brackets is evaluated to get the property name.

function getAge(obj) {
    // check the below line there is an error
   return obj.1
}

console.log(getAge({ name: "Kushal", 1: 23 }) )

