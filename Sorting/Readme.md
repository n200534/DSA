# 🔁 Sorting Techniques – Points to Remember

## 📌 Selection Sort
- Always selects the minimum element from the unsorted part and swaps it to the beginning.
- Time Complexity: O(n²)
- Space Complexity: O(1)
- Stable: ❌
- In-place: ✅
- Best used when memory write is minimal.

---

## 📌 Bubble Sort
- Repeatedly swaps adjacent elements if they are in the wrong order.
- Time Complexity: O(n²), Best Case: O(n) when sorted
- Space Complexity: O(1)
- Stable: ✅
- In-place: ✅
- Best for educational purposes or when array is nearly sorted.

---

## 📌 Insertion Sort
- Builds sorted array by inserting elements at correct position.
- Time Complexity: O(n²), Best Case: O(n)
- Space Complexity: O(1)
- Stable: ✅
- In-place: ✅
- Good for small or partially sorted arrays.

---

## 📌 Merge Sort
- Divide the array, sort recursively, and merge.
- Time Complexity: O(n log n)
- Space Complexity: O(n)
- Stable: ✅
- In-place: ❌
- Preferred when stability is needed or working with linked lists.

---

## 📌 Quick Sort
- Picks a pivot and partitions the array around the pivot.
- Time Complexity: Avg: O(n log n), Worst: O(n²)
- Space Complexity: O(log n)
- Stable: ❌
- In-place: ✅
- Fastest in practice for large datasets, cache-friendly.

---

