# Knapsack DP

A Python implementation of the 0/1 Knapsack problem using two Dynamic Programming approaches: bottom-up tabulation and top-down memoization.

## Problem

Given a set of items, where each item has a value and weight, the goal is to select items with maximum total value without exceeding the given capacity.

An item can either be selected completely or left out. It cannot be partially selected.

## Approaches

### Bottom-Up

The bottom-up approach builds a DP table iteratively.

Each table entry stores the maximum value possible for a given number of items and weight capacity.

### Top-Down

The top-down approach uses recursion with memoization.

When a subproblem is solved, its result is stored and reused if the same state is needed again.

## Example

Values:

[60, 100, 120]

Weights:

[10, 20, 30]

Capacity:

50

Output:

Bottom-Up Result: 220

Top-Down Result: 220

## Complexity

Both approaches have:

Time Complexity: O(n × W)

Space Complexity: O(n × W)

where `n` is the number of items and `W` is the knapsack capacity.

## How to Run

Make sure Python 3 is installed.

Run:

python knapsack.py
