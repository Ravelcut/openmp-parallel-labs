# OpenMP Parallel Programming Coursework 
- **Student:** Luka Bezhashvili
- **University:** Saint Andrew's National Georgian University
- **Course:** Parallel and Distributed Computing (2026)

---

## 📌 Project Overview
This repository serves as a comprehensive portfolio of my practical work using **OpenMP** in C++. It includes 10 core tasks covering the fundamental concepts of parallel computing, synchronization, and performance optimization.

## 🛠️ Environment & Tools
* **Language:** C++11 or higher
* **Library:** OpenMP (`omp.h`)
* **Platform:** Google Colab (Ubuntu 22.04 LTS)
* **Compiler:** GCC (`g++`) with `-fopenmp` flag

---

## 📂 Repository Structure

### 📝 Quiz 1: Threads and OpenMP Fundamentals
Each task below includes the source code, compilation/execution commands, and a brief technical analysis.

| Task # | Title | Key Concept |
| :--- | :--- | :--- |
| **Task 1** | First Parallel Program | `pragma omp parallel`, Thread IDs |
| **Task 2** | Thread Control | `omp_set_num_threads()` |
| **Task 3** | Parallel Loops | `pragma omp parallel for` |
| **Task 4** | Array Doubling | Data Parallelism |
| **Task 5** | Vector Addition | Shared Memory Operations |
| **Task 6** | Race Condition | Data Inconsistency Demo |
| **Task 7** | Atomic Operations | `pragma omp atomic` |
| **Task 8** | Reduction Clause | `reduction(+:var)` |
| **Task 9** | Critical Sections | `pragma omp critical` |
| **Task 10** | Performance Scaling | Benchmarking with `omp_get_wtime()` |

### This will be updated everytime I will get a new assignment.

---

## How to Run the Tasks
To compile and run any task in a Linux/Colab environment, use the following syntax:

```bash
# Example for Task 1
g++ -fopenmp task1.cpp -o task1_exe
./task1_exe
