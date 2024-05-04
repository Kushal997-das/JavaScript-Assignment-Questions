## Problem Description

You are given an array of strings `arr` as an argument, representing the names of people in a village. A "Zombie" has sneaked into the village and is also part of the array. The zombie eats the person who is to the right of it. Tell the person who is going to be eaten. It is guaranteed that there will always be at least one person to the right of the zombie. From the given function `zombieAttack` return the name of the person.

Please note: There will be only one "Zombie" in the array.

**Hint 1:** Iterate through the array using a loop and use string comparison to find the Zombie.

**Hint 2:** Once you find the zombie, keep track that you have found it and find the person next to it.

### Sample Input

```
Anil, Zombie, Pulkit, Chinmay
```

### Sample Output

```
Pulkit
```

### Explanation

The first person to the right of "Zombie" is Pulkit. Thus we return Pulkit.
