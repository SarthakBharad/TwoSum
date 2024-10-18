# TwoSum
Solving the problem of finding two indices in an array of integers (nums) that sum up to a given target using Java.

**Problem Breakdown**

Input: An array of integers (nums) and an integer (target).
Output: An array of two integers representing the indices of the two numbers in nums that add up to target.
Goal: You need to find two distinct indices in an array of integers such that the values at these indices sum up to a given target value.
Input Assumption: The problem guarantees that there is exactly one solution for every input, meaning there are two numbers in the array that will meet the requirement.

Solution: There are four solutions possible and each method has its advantages and disadvantages, and the best choice depends on the context and constraints of the problem. For this specific problem, the hash map method is usually preferred for its efficiency and simplicity.

1. Brute Force: Simple but inefficient (O(n²)).
2. Hash Map: Optimal solution (O(n) time, O(n) space).
3. Sorting + Two-Pointer: Slightly slower due to sorting (O(n log n)).
4. Using a Set: Similar to hash map, good for space efficiency but slightly more cumbersome to get indices.
