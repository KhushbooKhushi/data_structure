# Arrays — 10 LeetCode Problems

> **Note:** LeetCode officially uses **Easy / Medium / Hard**, not Beginner / Intermediate / Advanced / Expert. Here, the four levels represent learning difficulty, while the problems are selected to create a deliberate learning progression.

## 🎯 Learning Objective

After completing these 10 problems, you should be able to:

- Traverse and modify arrays confidently.
- Search and manipulate elements efficiently.
- Use in-place techniques.
- Recognize two-pointer patterns.
- Apply prefix/suffix reasoning.
- Handle rotated and specially structured arrays.
- Optimize array algorithms from brute force toward **O(n)** or **O(log n)**.
- Recognize advanced array patterns involving state tracking, index mapping, and in-place algorithms.

---

# 🟢 Beginner — 3 Problems

## 🟢 Problem 1 — Move Zeroes

- **LeetCode:** #283
- **Difficulty:** Beginner
- **Pattern:** Array Traversal + In-Place Modification + Two Pointers
- **Prerequisites:** Arrays, Loops, Basic Swapping
- **Why this problem:** Excellent first exercise for learning how to traverse an array while modifying it in-place. It develops the idea of maintaining a useful region of the array while processing elements.
- **LeetCode:** https://leetcode.com/problems/move-zeroes/

## 🟢 Problem 2 — Majority Element

- **LeetCode:** #169
- **Difficulty:** Beginner
- **Pattern:** Array Traversal + Frequency/Counting
- **Prerequisites:** Arrays, Loops, Basic Counting
- **Why this problem:** Moves beyond simple traversal and asks you to identify a dominant value efficiently. It introduces the idea that a problem may have a better approach than simply maintaining a frequency table.
- **LeetCode:** https://leetcode.com/problems/majority-element/

## 🟢 Problem 3 — Find Pivot Index

- **LeetCode:** #724
- **Difficulty:** Beginner
- **Pattern:** Prefix Sum / Left-Right Traversal
- **Prerequisites:** Arrays, Traversal, Basic Arithmetic
- **Why this problem:** Introduces an important array optimization: instead of repeatedly calculating the left and right portions, maintain the necessary information while traversing.
- **LeetCode:** https://leetcode.com/problems/find-pivot-index/

---

# 🟡 Intermediate — 3 Problems

## 🟡 Problem 4 — Rotate Array

- **LeetCode:** #189
- **Difficulty:** Intermediate
- **Pattern:** In-Place Array Manipulation
- **Prerequisites:** Arrays, Traversal, Reverse, Swapping
- **Why this problem:** Directly builds on the core **reverse** operation. It forces you to think about how an entire array can be reorganized efficiently while using constant extra space.
- **LeetCode:** https://leetcode.com/problems/rotate-array/

## 🟡 Problem 5 — Search in Rotated Sorted Array

- **LeetCode:** #33
- **Difficulty:** Intermediate
- **Pattern:** Binary Search + Rotated Array
- **Prerequisites:** Arrays, Searching, Sorted Arrays, Binary Search
- **Why this problem:** Takes ordinary array searching and adds structural complexity. Although the array is rotated, part of it remains sorted, enabling **O(log n)** searching.
- **LeetCode:** https://leetcode.com/problems/search-in-rotated-sorted-array/

## 🟡 Problem 6 — Product of Array Except Self

- **LeetCode:** #238
- **Difficulty:** Intermediate
- **Pattern:** Prefix/Suffix + Array Traversal
- **Prerequisites:** Arrays, Prefix/Suffix Concepts, Traversal
- **Why this problem:** A major step toward array optimization. The problem encourages you to combine prefix and suffix information efficiently and achieve **O(n)** time without division.
- **LeetCode:** https://leetcode.com/problems/product-of-array-except-self/

---

# 🔴 Advanced — 3 Problems

## 🔴 Problem 7 — Maximum Product Subarray

- **LeetCode:** #152
- **Difficulty:** Advanced
- **Pattern:** Dynamic State Tracking + Subarray
- **Prerequisites:** Arrays, Traversal, Subarrays, Basic Dynamic Programming
- **Why this problem:** Negative values make ordinary maximum-subarray reasoning insufficient. You must recognize that both the maximum and minimum product ending at the current position can matter.
- **LeetCode:** https://leetcode.com/problems/maximum-product-subarray/

## 🔴 Problem 8 — Set Matrix Zeroes

- **LeetCode:** #73
- **Difficulty:** Advanced
- **Pattern:** In-Place Array/Matrix Manipulation
- **Prerequisites:** Arrays, 2D Arrays, Traversal, In-Place Modification
- **Why this problem:** Introduces a harder form of in-place modification. The challenge is preserving enough information to perform all required modifications without corrupting the original state.
- **LeetCode:** https://leetcode.com/problems/set-matrix-zeroes/

## 🔴 Problem 9 — First Missing Positive

- **LeetCode:** #41
- **Difficulty:** Advanced
- **Pattern:** In-Place Index Mapping + Array Reorganization
- **Prerequisites:** Arrays, Traversal, In-Place Modification, Indexing
- **Why this problem:** A classic array optimization problem. The goal is to find the smallest missing positive integer in **O(n)** time while using **O(1)** auxiliary space, requiring the array itself to become part of the algorithmic strategy.
- **LeetCode:** https://leetcode.com/problems/first-missing-positive/

---

# ⚫ Expert — 1 Problem

## ⚫ Problem 10 — Trapping Rain Water

- **LeetCode:** #42
- **Difficulty:** Expert
- **Pattern:** Two Pointers + Prefix/Suffix Reasoning + Optimization
- **Prerequisites:** Arrays, Traversal, Maximum/Minimum, Two Pointers, Prefix/Suffix Concepts
- **Why this problem:** This is the mastery challenge. It requires understanding how each position depends on information from both sides and transforming that reasoning into an optimized approach.
- **LeetCode:** https://leetcode.com/problems/trapping-rain-water/

---

# 📊 Progression Summary

| # | Difficulty | Problem | Main Pattern | Key Skill |
|---:|---|---|---|---|
| 1 | 🟢 Beginner | Move Zeroes | Two Pointers | In-place traversal |
| 2 | 🟢 Beginner | Majority Element | Counting / Array Traversal | Efficient counting |
| 3 | 🟢 Beginner | Find Pivot Index | Prefix Sum | Left/right array reasoning |
| 4 | 🟡 Intermediate | Rotate Array | In-Place Reversal | Array reorganization |
| 5 | 🟡 Intermediate | Search in Rotated Sorted Array | Binary Search | Searching structured arrays |
| 6 | 🟡 Intermediate | Product of Array Except Self | Prefix + Suffix | Linear-time optimization |
| 7 | 🔴 Advanced | Maximum Product Subarray | State Tracking | Complex subarray reasoning |
| 8 | 🔴 Advanced | Set Matrix Zeroes | In-Place Matrix | Information preservation |
| 9 | 🔴 Advanced | First Missing Positive | Index Mapping | O(n), O(1) array algorithm |
| 10 | ⚫ Expert | Trapping Rain Water | Two Pointers + Prefix/Suffix | Advanced array optimization |

---

# 🧠 Skills Developed

By the end of these 10 problems, the learner should have developed:

1. **Array Traversal**
2. **Element Searching**
3. **Maximum/Minimum reasoning**
4. **In-place modification**
5. **Swapping**
6. **Array reversal**
7. **Two-pointer technique**
8. **Prefix-sum reasoning**
9. **Prefix/suffix optimization**
10. **Binary search on arrays**
11. **Subarray reasoning**
12. **State tracking**
13. **2D-array manipulation**
14. **Index-as-information technique**
15. **Constant-space optimization**
16. **Time-complexity optimization**
17. **Pattern recognition**

---

## 🔥 Intended Learning Path

**Traversal → In-Place Modification → Counting → Prefix Sum → Reverse → Rotation → Binary Search → Prefix/Suffix → State Tracking → Index Mapping → Advanced Two Pointers**

The final problem should feel substantially different from the first: the learner is no longer merely manipulating an array, but reasoning about **what information each array position represents and how to eliminate unnecessary work**.

---

## Understand → Implement → Practice → Analyze → Optimize → Master
