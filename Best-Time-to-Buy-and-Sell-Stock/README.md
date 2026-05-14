# Best Time to Buy and Sell Stock

## Problem
Given an array where `prices[i]` represents the stock price on the `i-th` day, find the maximum profit by buying on one day and selling on a future day.



## Approach
- Track the minimum stock price seen so far.
- Calculate profit for each day.
- Update maximum profit whenever a better profit is found.


## Example

Input:
prices = [7,1,5,3,6,4]

Output:
5

Explanation:
Buy at price `1` and sell at price `6`.

Profit = 6 - 1 = 5



## Time Complexity
O(n)

## Space Complexity
O(1)

