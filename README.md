# Day9-50-days-coding-challenge
## ✅ Problems Solved

### 1. Nth Digit in Infinite Integer Sequence
- **Problem:**  
  Given an integer `n`, return the `n`th digit of the infinite sequence of positive integers concatenated.
- **Examples:**  
  - Input: `n = 3` → Output: `3`  
  - Input: `n = 11` → Output: `0` (because the 11th digit is from number `10`)
- **Approach:**  
  1. Find the digit-length group where `n` belongs (1-digit, 2-digit, 3-digit...)  
  2. Calculate the actual number and the digit within it.
- **Time Complexity:** `O(log n)`  
- **Space Complexity:** `O(1)`

---

### 2. Swapping Kth Nodes in a Linked List
- **Problem:**  
  Swap the values of the `k`th node from the beginning and the `k`th node from the end.
- **Examples:**  
  - Input: `[1,2,3,4,5]`, `k = 2` → Output: `[1,4,3,2,5]`  
  - Input: `[7,9,6,6,7,8,3,0,9,5]`, `k = 5` → Output: `[7,9,6,6,8,7,3,0,9,5]`
- **Approach:**  
  1. Traverse to find the length of the list.  
  2. Access the `k`th node from the front and from the end using two passes.  
  3. Swap their values.
- **Time Complexity:** `O(n)`  
- **Space Complexity:** `O(1)`

---

## 🔍 Concepts Practiced
- Math-based string digit extraction  
- Grouping logic (by digit lengths)  
- Linked list traversal and in-place swaps  
- 1-indexed logic in singly linked lists

## 💻 Tools & Language
- Language: C++  
- IDE: VS Code  
- Version Control: Git, GitHub
