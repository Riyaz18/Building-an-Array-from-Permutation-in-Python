# Building-an-Array-from-Permutation-in-Python
## Overview
This repository contains a Python solution for a coding problem where we construct a new array ans from a given permutation array nums. Each element in ans is determined by the value at the index specified by the corresponding element in nums.

## Problem Statement
Given a zero-based permutation array nums, construct an array ans such that ans[i] = nums[nums[i]] for each 0 <= i < len(nums).

## Solution Approach
Initialize an empty list ans.
Iterate through each element in nums.
Append nums[nums[i]] to ans.
Return ans.
## Example
For example, if nums = [5, 0, 1, 2, 3, 4], the output should be ans = [4, 5, 0, 1, 2, 3].

## Implementation
The solution is implemented in Python using a straightforward approach to iterate through the array and build the required ans array based on the given permutation nums.

# Usage
Feel free to explore the code and adapt it for similar problems or learning purposes.

