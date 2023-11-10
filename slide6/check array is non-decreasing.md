Problem Description
Given an array arr of numbers as an argument. You have to implement the function checkNonDecreasing such that if the given array is in nondecreasing order return true else return false.

We define an array as non-decreasing if nums[i] <= nums[i + 1] holds for every i (0-based) such that (0 <= i <= n - 2).


Hint 1: Use loops to iterate through all the elements.

Hint 2: If first element is less than or equal to second element, second element is less than or equal to third element, and so on. This condition should hold true for all elements in the array.

Hint 3: At any point, while iterating over the array, if you find that the condition of a non-decreasing array is not satisfied, you can return false.


Sample Input 1

1, 2, 3, 2


Sample Output 1
false


Explanation
Last number 2 is smaller than 3 (the second last number) and thus the array is not non-decreasing. Thus we return false.


Sample Input 2
1, 2, 3, 3


Sample Output 2
true


Explanation
The given array is non-decreasing and thus we return true.