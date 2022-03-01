# TwoSum

## One pass

[Question](https://leetcode.com/problems/two-sum/)

This code, is the solution for the two sum array problem. It solves the problem by initializing an empty hashmap. Then analysing the first element in parsed array, and subtracting it from the target value to get a value in which if added to the element would equal the target value. The program then loops through to the next value, adding the previously analysed value to the hashtable, so it can be compared with the next value.

This is done until a pair is found in which then they are returned in order.
