# longest_common_substring

### Problem:
https://www.algoexpert.io/questions/Longest%20Common%20Subsequence

```
Q. Given two strings, return their longest common subsequence.

Note:
• A subsequence of a string is a new string generated from the original string with some characters (can be none) deleted without changing the relative order of the remaining characters. (e.g. "ade" is a subsequence of "abcde" while "aed" is not).
• A common subsequence of two strings is a subsequence that is common to both strings.

Examples:
Given two strings: string1 = "abcde" & string2 = "ade" // returns ["a", "d", "e"]
Given two strings: string1 = "abc" & string2 = "abc" // returns ["a", "b", "c"]
Given two strings: string1 = "" & string2 = "abc" // returns []
Given two strings: string1 = "abc" & string2 = "def" // []

function lcs(str1, str2) {
    // Write your code here.
    return []
}

// Test Cases
test.startProblem("Longest Common Subsequence")
test.testForArrays([], lcs("", ""), 1) 
test.testForArrays([], lcs("", "Formation"), 2)
test.testForArrays(["F", "o", "r", "m"], lcs("Formation", "Form"), 3)
test.testForArrays(["a", "p", "p", "l", "e"], lcs("apple", "pineapple"), 4)
test.testForArrays(["p", "p", "l", "e"], lcs("apple", "Apple"), 5)
test.testForArrays(["2", "2", "2", "2", "2", "2", "7"], lcs("13222323227", "2222222222517"), 6)
test.endProblem()
```
