# Maximum Subarray

## Problem
Given an integer array `nums`, find the contiguous subarray with the largest sum and return its sum.

## Approach
- Traverse through the array.
- Keep track of the current subarray sum.
- At each step:
  - either continue the current subarray
  - or start a new subarray
- Update the maximum sum whenever a better sum is found.

This approach is called Kadane’s Algorithm.

## Example

Input:
nums = [-2,1,-3,4,-1,2,1,-5,4]

Output:
6

Explanation:
The subarray `[4,-1,2,1]` has the largest sum.

4 + (-1) + 2 + 1 = 6


## Time Complexity
O(n)

## Space Complexity
O(1)
