# Memory Management Simulation

## Overview

This project simulates memory management systems to compare paging and non-paging techniques. It evaluates performance based on various parameters including page-replacement algorithms (LRU, FIFO, Random), swap-space size, and page size. The simulation is divided into three main modules, each handling different aspects of memory management.

## Modules

### 1. Data Generator

- **Purpose:** Simulates the generation of memory access data for the simulation.
- **Functionality:** Produces a set of random memory access requests to be used by both paging and non-paging systems.

### 2. Non-Paging System

- **Purpose:** Implements the contiguous allocation technique using a variable partition approach.
- **Algorithm:** Uses the first-fit algorithm to allocate memory blocks.
- **Functionality:** Manages memory without paging, focusing on contiguous memory allocation.

### 3. Paging System

- **Purpose:** Simulates a paging memory management system.
- **Functionality:** Handles memory using paging, evaluating the impact of various page-replacement algorithms (LRU, FIFO, Random).

### 4. Main Program (`main.cpp`)

- **Purpose:** Integrates all modules and runs the simulation.
- **Functionality:** Coordinates between the Data Generator, Non-Paging System, and Paging System. Measures and reports performance metrics such as page hit/miss ratio and page replacement time.

## Objectives

- **Compare Paging and Non-Paging Systems:** Analyze and compare the performance of paging versus non-paging memory management systems.
- **Evaluate Page Replacement Algorithms:** Assess the effectiveness of different page-replacement algorithms (LRU, FIFO, Random).
- **Analyze Parameters:** Study the impact of swap-space size and page size on system performance.

## Conclusion

The Memory Management Simulation project provides insights into the performance of paging and non-paging memory management systems. By simulating different algorithms and system parameters, it offers a comparative analysis to understand the strengths and limitations of various memory management techniques.

## Getting Started

To replicate this analysis, clone the repository and follow the instructions provided in the `setup.md` file.

```bash
git clone https://github.com/vikask-iitg/Memory-Management-Technique-Simulation.git
