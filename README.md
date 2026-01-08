# Software Engineering Lab

> Curated collection of programming exercises, algorithms, and mini-projects

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue.svg)](https://www.postgresql.org/)

## 📋 Overview

This repository contains structured programming exercises and mini-projects completed during intensive software engineering training. Each module builds progressively on fundamental concepts, demonstrating growth from basic syntax to complex system design.

---

## 📚 Contents

### Module 1: Python Fundamentals

| Week | Topic | Key Concepts |
|------|-------|-------------|
| **Week 3-4** | Syntax & Logic | Variables, operators, control flow, functions |
| **Week 5** | Data Structures | Lists, dictionaries, list comprehensions |
| **Week 6** | Functions | Function design, scope, recursion basics |
| **Week 7** | Practical Apps | Calculator implementation |
| **Week 8** | File I/O | Text files, CSV, JSON processing |
| **Week 10** | Modular Design | Multi-file programs, data/actions separation |
| **Week 11** | OOP | Classes, inheritance, encapsulation |
| **Week 12-13** | Advanced OOP | Design patterns, composition |
| **Week 14** | Data Structures | Stack, Queue, Deque, Binary Tree |
| **Week 15** | Algorithms | Big-O analysis, sorting algorithms |
| **Week 16** | Testing | pytest, test-driven development |

### Module 2: Backend Development

| Week | Topic | Key Concepts |
|------|-------|-------------|
| **Week 1** | Web Fundamentals | HTTP, REST principles, client-server |
| **Week 3** | SQL | Queries, joins, aggregations |
| **Week 4-5** | Flask Basics | Routes, templates, request handling |
| **Week 6-7** | APIs | RESTful design, JSON responses, validation |
| **Week 8** | Authentication | JWT, bcrypt, middleware |

### Module 2: Frontend Development

| Week | Topic | Key Concepts |
|------|-------|-------------|
| **Week 1** | HTML/CSS | Semantic markup, responsive design |
| **Week 2** | CSS Advanced | Flexbox, Grid, animations |
| **Week 3-4** | JavaScript | DOM manipulation, events, async |
| **Week 5-6** | Modern JS | ES6+, modules, fetch API |
| **Week 7-8** | SPA Concepts | Routing, state management |

---

## 🔬 Highlighted Exercises

### Data Structures (Week 14)

#### Stack Implementation
```
M1/week_14/ejercicio1_Stack.py
```
- LIFO structure with push, pop, peek operations
- Practical application: expression evaluation

#### Queue Implementation
```
M1/week_14/ejercicio_Queue.py
```
- FIFO structure with enqueue, dequeue
- Practical application: task scheduling

#### Binary Tree
```
M1/week_14/ejercicio3_BinaryTree.py
```
- Node insertion, traversal (in-order, pre-order, post-order)
- Search operations

### Algorithms (Week 15)

#### Big-O Analysis
```
M1/week_15/ejercicioBigO_1.py
M1/week_15/ejercicioBigO_2.py
```
- Time complexity comparisons
- Space complexity analysis

#### Sorting Algorithms
```
M1/week_15/ejercicioOrdenamiento_1.py
M1/week_15/ejercicioOrdenamiento_2.py
```
- Bubble sort, selection sort, insertion sort
- Merge sort, quicksort implementations
- Performance comparisons

### OOP Design (Week 11)

```
M1/week_11/ejercicioOOP1.py
M1/week_11/ejercicioOOP2.py
M1/week_11/ejercicioOOP3.py
```
- Class design and encapsulation
- Inheritance hierarchies
- Polymorphism examples

### SQL Practice (Week 3)

```
M2_Backend/week_3/exercise2.sql
M2_Backend/week_3/exercise3.sql
M2_Backend/week_3/exercise_extra*.sql
```
- Complex joins and subqueries
- Aggregation functions
- Database design patterns

---

## 📂 Directory Structure

```
software-engineering-lab/
├── python-fundamentals/
│   ├── syntax-and-control-flow/
│   ├── data-structures/
│   ├── functions/
│   ├── file-io/
│   └── oop/
├── algorithms/
│   ├── data-structures/
│   │   ├── stack.py
│   │   ├── queue.py
│   │   ├── deque.py
│   │   └── binary_tree.py
│   └── sorting/
│       ├── bubble_sort.py
│       ├── merge_sort.py
│       └── quick_sort.py
├── backend/
│   ├── sql-exercises/
│   └── flask-basics/
├── frontend/
│   ├── html-css/
│   ├── javascript/
│   └── todo-list-app/
└── README.md
```

---

## 🎯 Learning Outcomes

### Python Mastery
- [x] Fluent with core syntax and idioms
- [x] Effective use of data structures (lists, dicts, sets)
- [x] Object-oriented design principles
- [x] File handling and data serialization
- [x] Testing with pytest

### Algorithms & Data Structures
- [x] Implement fundamental data structures from scratch
- [x] Analyze time/space complexity (Big-O)
- [x] Apply sorting algorithms appropriately
- [x] Tree traversal techniques

### Web Development
- [x] RESTful API design principles
- [x] Database schema design
- [x] Authentication and authorization
- [x] Frontend-backend integration

---

## 🚀 Running Exercises

### Python Exercises

```bash
# Navigate to exercise
cd M1/week_14

# Run specific exercise
python ejercicio1_Stack.py

# Run tests (week 16)
cd M1/week_16
pytest tests/ -v
```

### SQL Exercises

```bash
# Connect to PostgreSQL
psql -U your_user -d your_database

# Run SQL file
\i M2_Backend/week_3/exercise2.sql
```

### Frontend Projects

```bash
# Navigate to project
cd M2_Frontend/Project/To-Do\ List

# Open in browser
start Home/home.html  # Windows
open Home/home.html   # Mac
```

---

## 📊 Progress Summary

| Area | Exercises | Status |
|------|-----------|--------|
| Python Basics | 25+ | ✅ Complete |
| OOP | 10+ | ✅ Complete |
| Data Structures | 8 | ✅ Complete |
| Algorithms | 6 | ✅ Complete |
| SQL | 10+ | ✅ Complete |
| Testing | 5+ | ✅ Complete |
| Frontend | 15+ | ✅ Complete |

---

## 🔗 Related Projects

These standalone projects evolved from this learning foundation:

- **[LyfterCook](../lyftercook)** - Full-stack chef management platform
- **[Pet E-Commerce API](../pet-ecommerce-api)** - RESTful backend
- **[Finance Tracker](../finance-tracker-desktop)** - Python GUI app
- **[Multi-Agent System](../multi-agent-web-system)** - AI automation

---

## 📄 License

MIT License

---

*Completed as part of the Lifter Software Engineering Program (Costa Rica, 2024-2025)*
