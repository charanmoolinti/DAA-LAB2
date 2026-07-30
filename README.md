# 🔍 String Matching Algorithms

A Python implementation and performance comparison of three popular string matching algorithms:

- Naive String Matching
- Knuth-Morris-Pratt (KMP)
- Rabin-Karp

---

# 📖 Project Overview

This project demonstrates the implementation and comparison of three widely used string matching algorithms. It searches for a pattern within a given text and compares the algorithms based on the number of character comparisons performed.

The project also includes a simple performance analysis to help understand the efficiency of each algorithm.

---

# 🎯 Objectives

- Implement Naive String Matching.
- Implement Knuth-Morris-Pratt (KMP) Algorithm.
- Implement Rabin-Karp Algorithm.
- Compare their performance.
- Analyze time complexity and efficiency.

---

# ✨ Features

- Pattern searching using three algorithms.
- Counts the number of comparisons.
- Displays matching positions.
- Performance comparison between algorithms.
- Easy-to-understand Python implementation.

---

# 🛠 Technologies Used

- Python 3
- Visual Studio Code
- Git
- GitHub

---

# 📂 Project Structure

```
DAA-LAB2/
│
├── lab2.py
├── README.md
└── .gitignore
```

---

# ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/charanmoolinti/DAA-LAB2.git
```

Move into the project folder:

```bash
cd DAA-LAB2
```

Run the program:

```bash
python lab2.py
```

---

# 📋 Algorithms Implemented

## 1. Naive String Matching

The Naive algorithm compares the pattern with every possible position in the text until a match is found.

### Time Complexity

- Best Case: **O(n)**
- Average Case: **O(nm)**
- Worst Case: **O(nm)**

---

## 2. Knuth-Morris-Pratt (KMP)

KMP uses the Longest Prefix Suffix (LPS) array to avoid unnecessary comparisons.

### Time Complexity

- Best Case: **O(n + m)**
- Average Case: **O(n + m)**
- Worst Case: **O(n + m)**

---

## 3. Rabin-Karp

Rabin-Karp uses hashing to efficiently compare substrings.

### Time Complexity

- Best Case: **O(n + m)**
- Average Case: **O(n + m)**
- Worst Case: **O(nm)**

---

# 💻 Sample Input

```
Text:
ABCDABCDABC

Pattern:
ABC
```

---

# 📤 Sample Output

```
Naive  -> Matches at: [0, 4, 8]
KMP    -> Matches at: [0, 4, 8]
RK     -> Matches at: [0, 4, 8]

Comparisons:
Naive : 15
KMP   : 10
RK    : 11
```

---

# 📊 Performance Comparison

| Algorithm | Best Case | Average Case | Worst Case |
|------------|-----------|--------------|-------------|
| Naive | O(n) | O(nm) | O(nm) |
| KMP | O(n+m) | O(n+m) | O(n+m) |
| Rabin-Karp | O(n+m) | O(n+m) | O(nm) |

---

# 🌍 Applications

- Text Editors
- Search Engines
- DNA Sequence Matching
- Plagiarism Detection
- Data Compression
- Spell Checkers

---

# 📚 Learning Outcomes

- Understand different string matching algorithms.
- Compare search performance.
- Analyze time complexity.
- Learn pattern searching techniques.

---

# 👨‍💻 Author

**Charan Moolinti**

BE Artificial Intelligence and Machine Learning

Chennai Institute of Technology

---

# ⭐ Repository

If you found this project useful, consider giving it a **Star ⭐** on GitHub.

Thank you!# DAA-LAB2
