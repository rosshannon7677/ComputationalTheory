# Computational Theory - Ross Hannon G00381859

This repository includes a Jupyter notebook that uses practical applications to examine the main ideas of **Computational Theory**. Every task shows the fundamental ideas that support contemporary cryptography and computation.

## Table of Contents
- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Tasks Overview](#tasks-overview)
- [AI Used](#ai-used)
- [Instructions to run Jupyter Notebook](#instructions-to-run-jupyter-notebook)
- [Contact](#contact)

## Introduction
---  

In this notebook there will be an explorartion of the foundational concepts in computational theory:

- **Bitwise operations and binary manipulation**
- **Cryptographic hashing and SHA-256 padding**
- **Turing Machine simulation**
- **Generation of prime number and root extraction**
- **Proof of work concepts using leading zero bits**
- **Complexity of algorithms and sorting analysis**

## Repository Structure
---

* **tasks.ipynb**: All 8 computational theory tasks displayed here
* **README.md**: Project overview and instructions on how to run the notebook
* **test.txt**: Input file used for SHA-256 padding demonstration in Task 3
* **requirements.txt**: Dependencies that run the notebook

## Tasks Overview
---

| Task | Description | Key Components |
|------|-------------|---------------|
| **Task 1** | **Binary Representations** | • **rotl(x, n)**: Left bit rotation<br>• **rotr(x, n)**: Right bit rotation<br>• **ch(x, y, z)**: Bitwise choice logic<br>• **maj(x, y, z)**: Bitwise majority logic<br><br>|
| **Task 2** | **Hash Functions** | • Converts a C-style hash function to Python<br>• Explains use of constants **31** and **101** in hashing<br>• Demonstrates string to hash conversion |
| **Task 3** | **SHA-256 Padding** | Simulates SHA-256 message padding by:<br>• Appending a **1** bit (`0x80`)<br>• Padding with `0x00` until **448 mod 512**<br>• Adding original message length (**64-bit big endian**) |
| **Task 4** | **Prime Numbers** | Does calculations of first 100 prime numbers using two methods:<br>• **Trial Division** <br>• **Sieve of Eratosthenes** <br><br>*Includes comparison table of both approaches.* |
| **Task 5** | **Roots** | • Calculates the square roots of the first 100 prime numbers<br>• Finds the fractional part and converts to **32-bit binary**<br>• Used in cryptographic algorithms|
| **Task 6** | **Proof of Work** | • Uses SHA-256 to hash dictionary words<br>• Identifies words with most leading 0 bits in hash<br>• Validates against standard dictionaries |
| **Task 7** | **Turing Machine** | • Turing Machine that adds **1** to binary input<br>• Creates a carry logic and halting conditions<br>• Shows real output and state transitions |
| **Task 8** | **Computational Complexity** | • Implements **Bubble Sort**<br>• Applies it to all permutations of `[1, 2, 3, 4, 5]`<br>• Counts and summarizes comparisons<br>• Outputs worst/best case examples |


### **AI Used**
---
| Tool | Purpose | Link |
|------|----------|------|
| GitHub Copilot | Used for code, pattern matching, and Python suggestions  | [GitHub Copilot](https://github.com/features/copilot) |
| ChatGPT | Helped with code structure, debugging, and enhancing conversation patterns | [ChatGPT](https://openai.com/chatgpt) |

## Instructions to run Jupyter Notebook
1. **Clone the Repository**: Clone this repository using the following command:

   ```bash
   git clone https://github.com/rosshannon7677/ComputationalTheory
   ```
2. **Navigate to Project Directory** 
    ```bash
    cd ComputationalTheory
    ```
3. **Install Dependencies** 
    ```bash
    pip install -r requirements.txt
    ```
4. **Launch Jupyter Notebook** 
    ```bash
    jupyter notebook
    ```
---

## Contact
For any questions or clarifications, feel free to contact me at G00381859@atu.ie