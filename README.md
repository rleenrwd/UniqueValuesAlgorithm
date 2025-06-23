# 🔢 Count Unique Values – Two-Pointer Pattern
## 📌 Why I Built This
This exercise was part of my effort to master the Two-Pointer Pattern, a powerful technique for solving array problems efficiently. I built this function to strengthen my skills in space and time optimization—two key topics in technical interviews and real-world problem-solving.

## 📖 Problem Statement
Write a function called countUniqueValues that accepts a sorted array (which may contain negative numbers), and returns the number of unique values in the array.

📌 The input array will always be sorted in non-decreasing order.

💡 Examples

countUniqVals([1, 1, 1, 2, 3, 3, 4, 4, 5, 6]) // Output: 6

countUniqVals([1, 1, 1, 1, 1])               // Output: 1

countUniqVals([-3, -2, -1, 0, 1, 2, 2])       // Output: 6

countUniqVals([])                            // Output: 0

## 🧠 Approach & Time Complexity
This solution uses the Two-Pointer Pattern, which is especially effective for sorted arrays.

## ✅ How It Works:
Use two pointers (i and j):

i tracks the position of the last unique value.

j scans through the array.

When arr[i] !== arr[j], increment i and set arr[i] = arr[j].

By the end, i + 1 will represent the count of unique values.

## ⏱️ Time Complexity:
O(n) – Linear time (single pass through array)

## 🧮 Space Complexity:
O(1) – Constant space (in-place algorithm, no extra data structures used)

## 🧠 What I Learned
How to use the Two-Pointer Pattern effectively for in-place updates

The importance of leveraging sorted input for optimization

Difference between mutating an array vs. returning new values

How to achieve O(1) space complexity by avoiding extra storage
