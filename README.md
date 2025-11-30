OS Lab Assignment 3 — Scheduling, File Allocation & Memory Management

This repository contains Python programs that simulate core Operating System concepts, including CPU scheduling, file allocation methods, and memory management techniques. The goal is to bridge theory with hands-on implementation.

Features Implemented
1. CPU Scheduling Algorithms

Priority Scheduling

Round Robin Scheduling

Calculates:

Waiting Time

Turnaround Time

Generates simple Gantt-style output.

2. File Allocation Methods

Sequential File Allocation

Indexed File Allocation

Validates block availability and allocation.

3. Memory Allocation Techniques

First Fit

Best Fit

Worst Fit

Tracks partition usage and fragmentation.

4. MFT & MVT Memory Management

MFT (Fixed Partition)

MVT (Variable Partition)

Simulates allocation and memory reduction.

How to Run

Clone the repository and run each script using:

python3 filename.py


Follow CLI instructions to input:

Burst times

Priorities

Block sizes

Partition sizes

Process sizes

Repository Structure
 priority_roundrobin.py
 sequential_allocation.py
 indexed_allocation.py
 memory_fit.py
 mft_mvt.py
 README.md
 sample_outputs/   # optional screenshots/output logs

Learning Objectives

✔ Understand CPU scheduling behavior
✔ Simulate file allocation strategies
✔ Analyze memory allocation performance
✔ Apply OS theory in Python programs

Requirements

Python 3.x

Runs on any OS (Linux recommended but not required)
