# Merge Sorted Array

## Problem
You are given two sorted arrays `nums1` and `nums2`.

Merge both arrays into a single sorted array inside `nums1`.

The first array `nums1` contains extra space at the end to store all elements from `nums2`.


## Approach
- Use three pointers:
  - `i` for the last valid element in `nums1`
  - `j` for the last element in `nums2`
  - `k` for the last position in `nums1`
- Compare elements from the back.
- Place the larger element at the end of `nums1`.
- Continue until all elements are merged.


## Example

Input:
nums1 = [1,2,3,0,0,0]
nums2 = [2,5,6]

Output:
[1,2,2,3,5,6]

Explanation:
Both arrays are merged into one sorted array.


## Time Complexity
O(m + n)

## Space Complexity
O(1)


