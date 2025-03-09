# 📌 Heap Sort Implementation

## 🆔 Student Identity
- **👤 Name:** Muhammad Axel Savero Fikri
- **🆔 NIM:** 1313623004

---

## 🚀 About the Project
Heap Sort is an efficient, comparison-based sorting algorithm that utilizes a binary heap data structure. This implementation demonstrates the fundamental workings of Heap Sort, offering an optimized way to sort an array of elements.

### 🔹 Key Features:
✅ Efficient sorting using Heap Sort algorithm
✅ Demonstrates max-heap structure
✅ Optimized for performance

---

## 🛠 How to Run
Follow these steps to build and execute the Heap Sort program:

### 🔧 Build the Project:
```bash
meson setup build
cd build
meson compile
```

### ▶️ Run the Program:
```bash
./heapsort
```

---

## 📖 How Heap Sort Works
1. **Build Max-Heap:** Convert the input array into a max-heap.
2. **Heapify:** Swap the root (largest value) with the last element and reduce the heap size.
3. **Repeat:** Continue heapifying until the entire array is sorted.

Time Complexity: **O(n log n)** 🔥