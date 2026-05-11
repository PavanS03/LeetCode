# Contains Duplicate

## Problem
Given an integer array `nums`, return `true` if any value appears at least twice in the array, and return `false` if every element is distinct.


## Approach
- Used a HashSet (`set()`) to store elements.
- Traversed through the array one by one.
- If an element already exists in the set, return `True`.
- Otherwise add the element to the set.


## Time Complexity
O(n)

## Space Complexity
O(n)
