
# Problem Description

If your name starts with a 'T' or 't', today is your lucky day! The city mall is giving away free coupons to every visitor whose name starts with a 'T' or 't'.

You are given a string name as an argument. Implement the function `checkEligibility` to help the mall determine if a person with the given name is eligible for the offer. Return "Eligible" if the name starts with 'T' or 't', else return "Not Eligible".

**Hint:** Use `charAt(i)` to get the character at index i.

**Hint:** Use `toUpperCase()` to convert the string to uppercase.

## Sample Input 1
```plaintext
Tia
```

## Sample Output 1
```plaintext
Eligible
```

**Explanation:**
Tia starts with T, therefore the output is Eligible.

## Sample Input 2
```plaintext
Aagam
```

## Sample Output 2
```plaintext
Not Eligible
```

**Explanation:**
Aagam doesn’t start with T or t, therefore the output is Not Eligible.

## Sample Input 3
```plaintext
tisha
```

## Sample Output 3
```plaintext
Eligible
```

**Explanation:**
tisha starts with t, therefore the output is Eligible.
