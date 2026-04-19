# ⚙️ Python — Algorithms & Libraries

> Mastering DSA + top Python libraries with hands-on notebooks

![Algorithms](https://img.shields.io/badge/Topic-Algorithms%20%26%20DSA-purple)
![Libraries](https://img.shields.io/badge/Libraries-NumPy%20%7C%20Pandas%20%7C%20Matplotlib-blue)
![Python](https://img.shields.io/badge/Python-3.x-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

---

## 📌 About

This repository is a complete reference for learning Python algorithms and its most important libraries — all in one place. Every topic has a dedicated Jupyter notebook with explanations, visual examples, and practice problems.

Two tracks run in parallel:
- **DSA Track** — Algorithms and Data Structures from scratch
- **Library Track** — NumPy, Pandas, Matplotlib, Seaborn, SciPy

```python
import numpy as np

my_list = [64, 34, 25, 12, 22, 11, 90]

# Bubble sort — manual implementation
for i in range(len(my_list)):
    for j in range(0, len(my_list)-i-1):
        if my_list[j] > my_list[j+1]:
            my_list[j], my_list[j+1] = my_list[j+1], my_list[j]

# NumPy way — 1 line!
sorted_arr = np.sort(np.array(my_list))
```

---

## 🔃 Algorithms Covered

### Sorting
`Bubble Sort` `Selection Sort` `Insertion Sort` `Merge Sort` `Quick Sort` `Heap Sort` `Counting Sort`

### Searching
`Linear Search` `Binary Search` `Jump Search` `Interpolation Search`

### Data Structures
`Arrays` `Linked List` `Stack` `Queue` `Hash Table` `Binary Tree` `BST` `Graphs`

### Problem Solving Techniques
`Recursion` `Two Pointers` `Sliding Window` `Dynamic Programming` `Greedy` `Backtracking` `BFS / DFS`

---

## 📦 Libraries Covered

| Library | Topics |
|---------|--------|
| **NumPy** | Arrays, matrix ops, linear algebra, broadcasting, random |
| **Pandas** | DataFrames, Series, groupby, merge, data cleaning, CSV/Excel |
| **Matplotlib** | Line, bar, scatter, pie charts, subplots, custom styling |
| **Seaborn** | Statistical plots, heatmaps, pairplots, distribution charts |
| **SciPy** | Scientific computing, optimization, signal processing, stats |
| **Collections / itertools** | Counter, deque, defaultdict, combinations |

---

## 📊 Progress Tracker

| Topic | Progress |
|-------|----------|
| Bubble / Selection Sort | ✅ 100% |
| Merge Sort / Quick Sort | 🔄 80% |
| Binary Search | ✅ 100% |
| Linked List & Stack | 🔄 70% |
| Trees & Graphs | 🔄 30% |
| Dynamic Programming | ⏳ 15% |
| NumPy | 🔄 90% |
| Pandas | 🔄 65% |
| Matplotlib / Seaborn | 🔄 50% |
| SciPy | ⏳ 10% |

---

## 🚀 Setup

```bash
# 1. Clone the repo
git clone https://github.com/your-username/python-algo-libs
cd python-algo-libs

# 2. Create a virtual environment
python3 -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# 3. Install all libraries
pip install -r requirements.txt

# 4. Open Jupyter
jupyter lab
```

**requirements.txt**
