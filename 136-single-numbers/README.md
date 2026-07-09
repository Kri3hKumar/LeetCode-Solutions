# 136. Single Number

## Problem Statement

Given a non-empty array of integers `nums`, every element appears twice except for one. Find that single element.

**LeetCode:** 136. Single Number

## Approach

This solution uses the **Bitwise XOR (`^`)** operator.

### Key Idea

The XOR operator has two important properties:

- `a ^ a = 0`
- `a ^ 0 = a`

Since every number except one appears twice, all duplicate numbers cancel each other out when XORed together. The remaining value is the unique element.

## Algorithm

1. Initialize `ans = 0`.
2. Traverse the array.
3. XOR each element with `ans`.
4. Return `ans`.
