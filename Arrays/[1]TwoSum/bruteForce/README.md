# TwoSum

[Question](https://leetcode.com/problems/two-sum/)

This code, is the solution for the two sum array problem. It solves the problem by looping through the array twice and using I as the first counter used for the index of the first item, and then comparing the value of array[i], to the value of the array[j] which is the counter for the second loop.  
If when added together they equal the target there positions are returned. If no conditon is met in the second loop then I is incremented and the second loop is run again, incrementing aswell.

* BigO(n^2)
