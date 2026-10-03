# Python Programming Experiments

This repository contains the work completed for my first-year **Python Programming Lab**. It consists of five Jupyter Notebook experiments covering the progression from Python fundamentals to structured programming, modules, regular expressions, file operations, and exception handling.

The focus throughout the repository is on implementing each concept through small, executable programs rather than treating the experiments as purely theoretical exercises.

## Experiments

| # | Experiment | Core Concepts | Notebook |
|:---:|---|---|:---:|
| 01 | Python Basics | Syntax, data types, operators, type conversion, input | [View](./Experiment%20-%201.ipynb) |
| 02 | Control Flow & Collections | Conditionals, loops, lists, tuples, sets, dictionaries | [View](./Experiment%20-%202.ipynb) |
| 03 | Functions & Recursion | Functions, arguments, lambda expressions, recursion | [View](./Experiment%20-%203.ipynb) |
| 04 | Modules & Regular Expressions | Standard modules, custom modules, packages, regex | [View](./Experiment%20-%204.ipynb) |
| 05 | File & Exception Handling | File I/O, directories, exceptions, assertions | [View](./Experiment%20-%205.ipynb) |

---

## 01 — Python Basics: Syntax, Data Types and Operators

[**Open Experiment 1 →**](./Experiment%20-%201.ipynb)

An introduction to Python's syntax and execution model, with an emphasis on variables, expressions, types, and basic user interaction.

**Covered in the notebook:**

- Python tokens and keywords
- Variable assignment and dynamic typing
- Built-in types: `int`, `float`, `str`, and `bool`
- Arithmetic, relational, logical, and assignment operators
- Expression evaluation and operator precedence
- Explicit type conversion
- Input-driven programs using `input()`

---

## 02 — Control Flow and Collections

[**Open Experiment 2 →**](./Experiment%20-%202.ipynb)

Builds on the fundamentals by introducing conditional execution, iteration, and Python's primary collection types.

**Covered in the notebook:**

- `if`, `if-else`, and nested conditional statements
- Iteration using `for` and `while`
- List operations: insertion, deletion, modification, and slicing
- Tuple indexing and immutability
- Set operations: union, intersection, and difference
- Dictionary creation, modification, and deletion
- Application of collections through a student record system

---

## 03 — Functions and Recursion

[**Open Experiment 3 →**](./Experiment%20-%203.ipynb)

Introduces functional decomposition — moving from sequential programs to code organized around reusable units of logic.

**Covered in the notebook:**

- Defining and calling user-defined functions
- Default arguments
- Keyword arguments
- Variable-length arguments
- Lambda expressions
- Functional operations using `map()` and `filter()`
- Factorial using recursion
- Fibonacci sequence using recursion
- Small programs composed using multiple functions

---

## 04 — Modules and Regular Expressions

[**Open Experiment 4 →**](./Experiment%20-%204.ipynb)

Moves beyond self-contained programs by exploring Python's module system, package structure, and pattern matching with regular expressions.

**Covered in the notebook:**

- Standard library modules: `math`, `sys`, `time`, and `os`
- Creation and import of user-defined modules
- Packages containing multiple modules
- Regular expressions using the `re` module
- Email address validation
- Mobile number extraction from text
- Regex metacharacters and pattern construction

Supporting Python modules and packages used in this experiment are maintained alongside the notebooks in the repository.

---

## 05 — File Handling and Exception Handling

[**Open Experiment 5 →**](./Experiment%20-%205.ipynb)

Introduces interaction with persistent data and structured error handling, allowing programs to operate beyond values stored only during execution.

**Covered in the notebook:**

- File access modes: `r`, `w`, and `a`
- Reading, writing, and appending data
- Context-managed file operations using `with`
- File and directory operations using `os`
- Exception handling with `try`, `except`, `else`, and `finally`
- Handling multiple exception types
- Explicit exception generation using `raise`
- Assertions using `assert`
- Defining custom exceptions

The repository also contains the files and directories required by the file-handling programs.

---

## Repository Structure

```text id="8wmv0f"
Python_Programming_Experiments_Suyosha/
│
├── Experiment - 1.ipynb
├── Experiment - 2.ipynb
├── Experiment - 3.ipynb
├── Experiment - 4.ipynb
├── Experiment - 5.ipynb
│
├── LabFiles/
├── mypackage/
├── studentpackage/
│
├── mymodule.py
├── demo.txt
├── student.txt
│
└── README.md
```

The five notebooks contain the primary experimental work. The additional modules, packages, directories, and text files are supporting resources for experiments involving modular programming and file handling.

## Running the Notebooks

Clone the repository:

```bash id="cuh2sc"
git clone https://github.com/SuyoshaAgarwal/Python_Programming_Experiments_Suyosha.git
```

Move into the project directory:

```bash id="ybhqpg"
cd Python_Programming_Experiments_Suyosha
```

If Jupyter Notebook is not already available:

```bash id="80a6dt"
pip install notebook
```

Start Jupyter:

```bash id="zn98oc"
jupyter notebook
```

From there, open any experiment and execute its cells in sequence. The notebooks can also be viewed directly on GitHub using the links above.

---

## Scope

Across the five experiments, the repository follows a deliberate progression:

```text id="u2lh36"
Python Fundamentals
        │
        ▼
Control Flow & Data Structures
        │
        ▼
Functions & Recursion
        │
        ▼
Modules, Packages & Regex
        │
        ▼
File I/O & Exception Handling
```

Together, these experiments cover the core Python concepts required to move from writing individual statements to building programs that are structured, reusable, and capable of interacting with external data.

---

**Suyosha Agarwal**  
*Python Programming Lab*

