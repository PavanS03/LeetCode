# Valid Anagram

## Problem
Given two strings `s` and `t`, return `true` if `t` is an anagram of `s`, otherwise return `false`.

## Approach
- First check if lengths are equal.
- Use a dictionary to count character frequencies.
- Increase count for characters in the first string.
- Decrease count for characters in the second string.
- If any character is missing or count becomes negative, return `False`.

## Example

Input:
s = "anagram"
t = "nagaram"

Output:
True

Explanation:
Both strings contain the same characters with the same frequencies.

## Time Complexity
O(n)

## Space Complexity
O(1)
