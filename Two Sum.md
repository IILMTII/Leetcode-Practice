Given an array of integers, return indices of the two numbers such that they add up to a specific target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

Example:

Given nums = [2, 7, 11, 15], target = 9,

Because nums[0] + nums[1] = 2 + 7 = 9,
return [0, 1].


modified the line if(hash.find{|key,val| key == value}) to if(hash.key?(value)) to find if a specific key is 
present in the hash and this solved the issue.
