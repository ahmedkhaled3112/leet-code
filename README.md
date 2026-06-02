<div align="center">

# 🧠 LeetCode Daily Challenge

**Enterprise-grade solutions to daily LeetCode problems — built with clean code principles, multiple algorithmic approaches, and rigorous complexity analysis.**

[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

_"It's not about solving the problem — it's about solving it the right way."_

</div>

## 📋 Table of Contents

- [About](#-about)
- [Repository Structure](#-repository-structure)
- [Solution Methodology](#-solution-methodology)
- [Code Standards](#-code-standards)
- [Complexity Analysis](#-complexity-analysis)
- [Testing & Validation](#-testing--validation)
- [Getting Started](#-getting-started)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 About

This repository is a structured, disciplined approach to solving the **LeetCode Daily Challenge**. Every solution is treated as production-ready code, adhering to enterprise-level software engineering standards. The goal is not just to pass test cases, but to deeply understand algorithmic patterns, write maintainable code, and produce rigorous analyses.

Each day's challenge is documented with:

- 📝 **Full problem description**, constraints, and notes
- 💡 **Multiple solution approaches** (brute force → optimized → alternative)
- 📊 **Big O complexity analysis** for every approach
- 🧪 **Edge case testing** to validate correctness and performance

---

## 📁 Repository Structure

The repository follows a strict separation between **problem definitions** and **solutions**:

```text
leet-code/
│
├── problems/
│   ├── 1/          # Day 1 — Problem description, constraints, and notes
│   ├── 2/          # Day 2 — Problem description, constraints, and notes
│   ├── 3/          # Day 3 — ...
│   └── ...
│
├── solutions/
│   ├── 1/          # Day 1 — Code solutions and detailed explanations
│   ├── 2/          # Day 2 — Code solutions and detailed explanations
│   ├── 3/          # Day 3 — ...
│   └── ...
│
├── .gitignore
└── README.md
```

> **Note:** Folder numbers in `problems/` and `solutions/` always match 1-to-1. Day **N**'s problem description lives in `problems/N/`, and its corresponding solutions live in `solutions/N/`.

---

## 🔬 Solution Methodology

Every problem is tackled using **multiple approaches** to build a complete understanding of the solution space:

### 1. Brute Force Approach

- Establishes a **baseline** naive solution.
- Clearly explains **why** this approach may fail under heavy constraints (e.g., TLE, memory limits).
- Serves as a starting point for optimization.

### 2. Optimized Approach

- Implements the **most efficient** solution using optimal algorithmic patterns.
- Focuses on minimizing time and space complexity.
- Leverages well-known techniques: sliding window, two pointers, dynamic programming, greedy algorithms, etc.

### 3. Alternative Approach _(when applicable)_

- Explores a **different paradigm** to solve the same problem.
- Examples: recursion vs. iteration, bit manipulation, specialized data structures (tries, segment trees, monotonic stacks).
- Highlights trade-offs between approaches.

---

## ✅ Code Standards

All code in this repository adheres to **strict clean code principles**, ensuring it is production-ready and highly readable:

| Principle              | Standard                                                                                                                   |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Naming Conventions** | Clear, descriptive variable and function names. No single-letter variables (except standard loop iterators like `i`, `j`). |
| **Modularity**         | Complex logic is extracted into well-named helper functions. Each function has a single responsibility.                    |
| **Maintainability**    | No deeply nested loops or unnecessary conditional checks. Flat, readable control flow.                                     |
| **Comments**           | Brief, high-level comments explain the _why_ behind complex logic — not the _what_.                                        |

---

## 📊 Complexity Analysis

Every solution includes a **rigorous theoretical analysis**:

- **Time Complexity** — Big O notation ($\mathcal{O}$) with an explanation of the driving factors (input size, nested iterations, recursive calls, etc.).
- **Space Complexity** — Big O notation ($\mathcal{O}$) for auxiliary space usage, excluding the input itself.

Example format used in solutions:

```text
Time Complexity:  O(n log n) — Sorting dominates, followed by a linear scan.
Space Complexity: O(n)       — HashMap stores up to n key-value pairs.
```

---

## 🧪 Testing & Validation

Before any solution is finalized, it undergoes **rigorous validation**:

1. ✅ **Standard Examples** — Verified against all LeetCode-provided test cases.
2. 🔍 **Edge Cases** — Constructed and tested for boundary conditions:
   - Empty or null inputs
   - Maximum/minimum integer limits
   - Negative values
   - Duplicate elements
   - Single-element inputs
   - Very large inputs (stress testing)
3. ⚡ **Performance** — Ensured to execute safely within time limits, avoiding TLE or memory overflow.

---

## 🚀 Getting Started

### Prerequisites

- A LeetCode account (free tier is sufficient)
- A code editor (VS Code recommended)

### Clone the Repository

```bash
git clone https://github.com/ahmedkhaled3112/leet-code.git
cd leet-code
```

### Navigate a Challenge

```bash
# View the problem description for Day 1
cat problems/1/

# View the solution(s) for Day 1
cat solutions/1/
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to add an alternative solution or improve an existing one:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b day-42-alternative`)
3. **Follow** the code standards outlined above
4. **Include** complexity analysis and edge case tests
5. **Submit** a pull request with a clear description
