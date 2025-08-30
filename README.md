# 🔎 Searching and Sorting (DSA)

This folder contains my solutions to **Searching and Sorting** problems from **LeetCode** and **GeeksforGeeks (GFG)**.  
The problems cover basic to advanced concepts in searching and sorting algorithms.

## What is Searching?
Searching means **finding an element** in a collection of data (like an array or list).

### Common Types:
- **Linear Search** → check one by one.  
  - Time: O(n)  
  - Best when data is small or unsorted.  

- **Binary Search** → repeatedly divide the search space into half.  
  - Time: O(log n)  
  - Works only on **sorted data**.  

👉 **How to identify searching problem?**  
If the question asks you to **find position / check existence / count frequency** of an element → it’s usually a searching problem.

---

## What is Sorting?
Sorting means **arranging elements** in increasing or decreasing order.  

### Common Algorithms:
- Bubble Sort → compare and swap neighbours. (O(n²))  
- Insertion Sort → build sorted part step by step. (O(n²))  
- Merge Sort → divide array, sort each half, merge. (O(n log n))  
- Quick Sort → pick a pivot, partition, sort parts. (O(n log n) average)  
- Heap Sort → use max-heap / min-heap. (O(n log n))  

👉 **How to identify sorting problem?**  
If the problem asks you to **arrange / minimize / maximize / find order / closest / largest/smallest after sorting** → it’s usually a sorting problem.

---

## Why Important?
- Searching helps us **find information quickly**.  
- Sorting makes data **organized** → easier to search, compare, or apply two-pointer methods.  

---

## Formulas & Key Points
- **Binary Search mid formula**:  
  `mid = low + (high - low) // 2` (to avoid overflow)  

- **Complexity to remember**:  
  - Best Sorting: O(n log n) (Merge/Quick/Heap)  
  - Worst Sorting: O(n²) (Bubble/Insertion/Selection)  
  - Searching: O(n) (Linear), O(log n) (Binary)

---

✨ In short:  
- Use **Linear Search** when unsorted & small data.  
- Use **Binary Search** when sorted data.  
- Use **Sorting** when order is needed or problem reduces after arrangement.
