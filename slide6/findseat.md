
## Problem Description

You are given 2 arrays of strings `arr1` and `arr2`. You have to implement the function `findSeatNumber` which returns the seat number of the person standing in front of Mridula after they take their seat in the theatre.

`arr1` represents the names of the people who are standing in a queue.

In `arr2`, the index denotes the seat number (seat numbers start from 0) and the value gives the name of the person in that seat.

It's guaranteed that there will always be someone before Mridula.

Return -1 if that person doesn't have a seat number.

**Hint 1:** Iterate over the first array, find and store the friend’s name in a variable.

**Hint 2:** Iterate over the second array to find the friend’s name and their corresponding seat number.

### Sample Input

```
["Raghu", "Goli", "Farhat", "Mridula", "Rahul"]
["Mridula", "Raghu", "Goli", "Farhat"]
```

### Sample Output

```
3
```

### Explanation

The person standing in front of Mridula is Farhat, and his seat number is 3 (considering 0-based indexing).
