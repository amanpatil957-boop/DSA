# Two Sum (LeetCode)

## Problem
Given an array of integers and a target value, find the indices of two numbers whose sum equals the target.

## Approach
Use an `unordered_map` to store numbers and their indices. For each number, calculate its complement (`target - nums[i]`). If the complement exists in the map, return both indices. Otherwise, store the current number and its index.

## Example
- **Input:** `nums = [2, 7, 11, 15]`, `target = 9`
- **Output:** `[0, 1]`
- **Explanation:** `nums[0] + nums[1] = 2 + 7 = 9`

## Complexity
- **Time Complexity:** O(n)
- **Space Complexity:** O(n)

## Language
C++