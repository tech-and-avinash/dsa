# dsa

Here's a **Big-O Notation Reference Table for Time & Space Complexity** so you can compare both in one place:

---

### **📌 Big-O Complexity Cheat Sheet (Time & Space)**

| **Big-O**        | **Time Complexity**      | **Space Complexity**  | **Description**                                      | **Example Algorithm**  |
|------------------|------------------|------------------|------------------------------------------------------|------------------------|
| **O(1)**        | Constant Time     | O(1)            | Fastest, doesn't depend on input size.              | Hash Table Lookup, Accessing an array index. |
| **O(log n)**    | Logarithmic Time  | O(1) or O(log n) | Efficient divide & conquer approaches.              | Binary Search, Tree Traversals. |
| **O(n)**        | Linear Time       | O(n)            | Grows directly with input size.                     | Looping through an array. |
| **O(n log n)**  | Linearithmic Time | O(n)            | Common in efficient sorting algorithms.             | Merge Sort, QuickSort (avg). |
| **O(n²)**       | Quadratic Time    | O(n²)           | Grows quickly, common in nested loops.              | Bubble Sort, Selection Sort. |
| **O(n³)**       | Cubic Time        | O(n³)           | Even slower; seen in triple nested loops.           | Matrix Multiplication. |
| **O(2ⁿ)**       | Exponential Time  | O(2ⁿ)           | Extremely slow, recursive problems.                 | Fibonacci (naive recursion). |
| **O(n!)**       | Factorial Time    | O(n!)           | Worst case, huge growth.                           | Traveling Salesman (Brute Force). |

---

### **🚀 Quick Growth Order (Time & Space)**
- **Time Complexity:**  
  ```
  O(1) < O(log n) < O(n) < O(n log n) < O(n²) < O(n³) < O(2ⁿ) < O(n!)
  ```
- **Space Complexity:**  
  ```
  O(1) < O(log n) < O(n) < O(n²) < O(n³) < O(2ⁿ) < O(n!)
  ```

---

### **🔹 Quick Notes on Space Complexity:**
1. **O(1) Space** → No extra memory used (e.g., swapping two numbers).  
2. **O(n) Space** → Storing results in arrays, linked lists, recursion stacks.  
3. **O(n²) Space** → Storing 2D arrays/matrices (like Floyd-Warshall).  
4. **Recursive Algorithms** → Usually take **O(n) space** due to stack usage.  

