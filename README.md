# Software Engineering Lab

> Curated collection of programming exercises, algorithms, and mini-projects

**Author**: [Andrey Quesada](https://github.com/andreyques41) | **GitHub**: [andreyques41/software-engineering-lab](https://github.com/andreyques41/software-engineering-lab)

[![Status](https://img.shields.io/badge/Status-Active-blue.svg)]()
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue.svg)](https://www.postgresql.org/)

## 📋 Overview

This repository contains **curated programming exercises, algorithms, and mini-projects** completed during intensive software engineering training. The collection showcases progression from fundamental programming concepts to advanced data structures and real-world application development.

---

## 📂 Repository Structure

```
software-engineering-lab/
├── python-fundamentals/      # OOP exercises and design patterns
│   └── exerciseOOP/         # Modular OOP project (data/actions separation)
├── algorithms/
│   ├── data-structures/     # Stack, Queue, Deque, Binary Tree implementations
│   └── sorting/             # Big-O analysis and sorting algorithms
├── backend/
│   └── sql/                 # PostgreSQL queries, joins, aggregations
├── projects/
│   └── finance-tracker/     # Complete Python GUI application
└── README.md
```

---

## 📚 Contents

### 🐍 Python Fundamentals

**Location**: `python-fundamentals/exerciseOOP/`

Demonstrates modular OOP design with separation of concerns:
- `main.py` - Application entry point
- `data.py` - Data models and structures
- `actions.py` - Business logic operations
- `menu.py` - User interface and navigation

**Concepts**: Classes, encapsulation, modular design, separation of concerns

---

### 🧮 Algorithms & Data Structures

#### Data Structures (`algorithms/data-structures/`)

| File | Implementation | Key Features |
|------|----------------|--------------|
| `ejercicio1_Stack.py` | Stack (LIFO) | Push, pop, peek, is_empty |
| `ejercicio_Queue.py` | Queue (FIFO) | Enqueue, dequeue, front, rear |
| `ejercicio2_DoubleEndedQueue.py` | Deque | Add/remove from both ends |
| `ejercicio3_BinaryTree.py` | Binary Tree | Insert, search, traversals (in-order, pre-order, post-order) |

#### Algorithms (`algorithms/sorting/`)

| File | Focus | Topics |
|------|-------|--------|
| `ejercicioBigO_1.py` | Complexity Analysis | Time/space complexity comparison |
| `ejercicioBigO_2.py` | Performance Testing | Practical Big-O demonstrations |
| `ejercicioOrdenamiento_1.py` | Basic Sorting | Bubble, selection, insertion sort |
| `ejercicioOrdenamiento_2.py` | Advanced Sorting | Merge sort, quicksort, performance analysis |

---

### 🗄️ Backend Development

#### SQL Practice (`backend/sql/`)

7 progressive exercises covering:
- Basic queries and filtering
- Complex joins (INNER, LEFT, RIGHT)
- Subqueries and CTEs
- Aggregation functions (COUNT, SUM, AVG, GROUP BY)
- Database design patterns

**Files**: `exercise2.sql` through `exercise4.sql` + 4 extra challenges

---

### 🚀 Featured Project: Finance Tracker

**Location**: `projects/finance-tracker/`

Complete desktop application for personal finance management built with Python and FreeSimpleGUI.

#### Architecture

```
finance-tracker/
├── finance_tracker.py        # Main entry point
├── Clases/
│   └── finance_movements.py  # Movement & FinanceMonth classes
├── DataHandler/
│   ├── csv_handler.py        # Data persistence
│   └── finance_data.csv      # Storage file
├── Gui/
│   ├── main_gui.py          # GUI window management
│   └── gui_helpers.py       # UI utilities
├── Tests/
│   └── test_finance_movements.py  # Unit tests
└── Utilities/
    └── utilities.py          # Helper functions
```

#### Features
- ✅ Income/expense tracking with categories
- ✅ CSV-based data persistence
- ✅ Input validation and error handling
- ✅ Clean OOP design with separation of concerns
- ✅ Unit tests with pytest

**[View detailed documentation →](projects/finance-tracker/README.md)**

---

## � Quick Start

### Running Python Exercises

```bash
# Data Structures
cd algorithms/data-structures
python ejercicio1_Stack.py

# Sorting Algorithms
cd algorithms/sorting
python ejercicioOrdenamiento_1.py

# OOP Exercise
cd python-fundamentals/exerciseOOP
python main.py
```

### Running SQL Exercises

```bash
# Connect to PostgreSQL
psql -U your_user -d your_database

# Execute SQL file
\i backend/sql/exercise2.sql

# Or run directly
psql -U your_user -d your_database -f backend/sql/exercise3.sql
```

### Finance Tracker Application

```bash
# Navigate to project
cd projects/finance-tracker

# Install dependencies
pip install FreeSimpleGUI pytest

# Run application
python finance_tracker.py

# Run tests
pytest Tests/ -v
```

---

## 🎯 What This Demonstrates

### Technical Skills
- **Data Structures**: Building fundamental structures from scratch (Stack, Queue, Deque, Binary Tree)
- **Algorithm Analysis**: Understanding and measuring time/space complexity
- **OOP Design**: Modular architecture with proper separation of concerns
- **Database**: SQL queries, joins, aggregations, and schema design
- **GUI Development**: Desktop application with FreeSimpleGUI
- **Testing**: Unit testing with pytest and validation patterns

### Engineering Practices
- Clean code organization and file structure
- Input validation and error handling
- Data persistence strategies (CSV)
- Test-driven development approach
- Incremental complexity progression

---

## 🔗 Related Projects

These production-quality applications evolved from this learning foundation:

- **[CaterPro](https://github.com/andreyques41/caterpro)** - Full-stack catering management platform (Flask + PostgreSQL)
- **[Pet E-Commerce API](https://github.com/andreyques41/pet-ecommerce-api)** - RESTful backend with 42 endpoints
- **[Todo List App](https://github.com/andreyques41/todo-list-app)** - Modular JavaScript frontend application
- **[Multi-Agent Web System](https://github.com/andreyques41/multi-agent-web-system)** - AI-powered development automation

---

## 📄 License

MIT License - See [LICENSE](LICENSE) for details.

---

*Completed as part of the Lifter Software Engineering Program (Costa Rica, 2024-2025)*
