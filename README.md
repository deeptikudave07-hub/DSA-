# DSA-
Question on DSA


Two Sum — Hash Map Approach

Problem

Given an array of integers "nums" and an integer "target", return the indices of two numbers whose sum equals the target.

Example

- Input: "nums = [2, 7, 11, 15]", "target = 9"
- Output: "[0, 1]"
- Explanation: "nums[0] + nums[1] = 2 + 7 = 9"

Approach

1. Create an empty dictionary called "seen".
2. Iterate through the array using "enumerate()".
3. Calculate the complement: "target - num".
4. Check whether the complement exists in the dictionary.
5. If found, return both indices; otherwise, store the current number and its index.

Complexity

- Time: O(n) average
- Space: O(n)

Concepts Learned

- Python dictionaries
- Hash maps
- Array traversal
- Time and space complexity
- DSA problem-solving