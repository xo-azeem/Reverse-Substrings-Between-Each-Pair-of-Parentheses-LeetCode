# Reverse Substrings Between Each Pair of Parentheses

LeetCode Q # 1190.

You are given a string s that consists of lower case English letters and brackets.

Reverse the strings in each pair of matching parentheses, starting from the innermost one.

Your result should not contain any brackets.

Example 1:

> Input: s = "(abcd)"</br>
> Output: "dcba"

Example 2:

> Input: s = "(u(love)i)"</br>
> Output: "iloveu"</br>
> Explanation: The substring "love" is reversed first, then the whole string is reversed.

Example 3:

> Input: s = "(ed(et(oc))el)"</br>
> Output: "leetcode"</br>
> Explanation: First, we reverse the substring "oc", then "etco", and finally, the whole string.

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/e6b2ea35-a7a0-4b41-9179-3bc4cf50ecaf)

  Time complexity: O(n^2).</br>Space complexity: O(n).
</div>
