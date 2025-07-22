# push_swap

**push_swap** is a sorting algorithm project developed as part of the **42 School Curriculum**.  
The goal is to sort a stack of integers with the least possible number of operations, using a limited set of stack operations, while following specific constraints.

---

## 📋 Project Overview

You are given a list of integers and you must sort them using **two stacks** (`a` and `b`) with a limited set of allowed operations:

- `sa` — swap the first two elements at the top of stack **a**
- `sb` — swap the first two elements at the top of stack **b**
- `ss` — `sa` and `sb` at the same time
- `pa` — push the top element of **b** onto **a**
- `pb` — push the top element of **a** onto **b**
- `ra` — rotate **a** (first element becomes last)
- `rb` — rotate **b**
- `rr` — `ra` and `rb` at the same time
- `rra` — reverse rotate **a** (last element becomes first)
- `rrb` — reverse rotate **b**
- `rrr` — `rra` and `rrb` at the same time

---

## 🎯 Objectives

- ✅ Implement a sorting algorithm using **only the allowed operations**
- ✅ Optimize the number of moves required
- ✅ Handle various input sizes (including edge cases)
- ✅ Follow strict **42 Norm** coding style
- ✅ Implement error handling for invalid inputs

---

## 🛠️ Features

- ✅ Sorting for small sets (2, 3, 5 numbers) using hardcoded optimal moves
- ✅ Chunking / Divide & Conquer algorithm for large inputs
- ✅ Input parsing with validation
- ✅ Custom stack data structure implementation
- ✅ Leak-free and crash-safe (tested with `valgrind`)
- ✅ Clear code structure and separation of concerns

---

## 🖥️ Getting Started

### Prerequisites

- GCC Compiler
- `make` utility

### Installation
```bash
git clone https://github.com/[your_username]/push_swap.git
cd push_swap
make
