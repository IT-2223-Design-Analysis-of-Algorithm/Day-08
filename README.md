# Day-08

# 📊 MATLAB Sorting Algorithms: Insertion & Bubble Sort

This project demonstrates two fundamental sorting algorithms implemented in MATLAB: **Insertion Sort** and **Bubble Sort**.

---

## 📌 Algorithms Included

### 🔢 1. Insertion Sort
Efficient for small datasets and partially sorted arrays.
```matlab
arr = [5, 4, 10, 1, 6, 2];
% Output: [1, 2, 4, 5, 6, 10]
```
**Logic**:  
- Start from the second element.  
- Compare and shift larger elements to the right.  
- Insert the current element (`key`) in the correct position.

---

### 💫 2. Bubble Sort
Simple but inefficient on large lists. Compares and swaps adjacent elements.
```matlab
array = [64, 34, 25, 12, 22, 11, 90];
% Output: [11, 12, 22, 25, 34, 64, 90]
```
**Logic**:  
- Repeatedly step through the list.  
- Swap adjacent elements if they are in the wrong order.  
- Continue until the list is sorted.

---

## 🧠 Time Complexities

| Algorithm      | Best Case   | Worst Case  | Time Complexity |
|----------------|-------------|-------------|------------------|
| Insertion Sort | O(n)        | O(n²)       | Efficient for nearly-sorted data |
| Bubble Sort    | O(n)        | O(n²)       | Easy but slow for large lists    |

---

## 🚀 How to Run
1. Open MATLAB
2. Paste the code in a `.m` file
3. Run the file to see sorted output in the console

---



