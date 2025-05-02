# Computational Theory - Ross Hannon G00381859

This repository contains work completed for the **Computational Theory** module as part of a fourth-year Software Development assessment at ATU Galway. All tasks are implemented and explained within a Jupyter Notebook.
---

## Table of Contents
- [Introduction](#introduction)
- [Tasks Overview](#tasks-overview)
- [Running the Jupyter Notebook](#running-the-jupyter-notebook)
- [Contact](#contact)

## Introduction
---  

This notebook demonstrates and explores foundational concepts in computational theory:

- **Bitwise operations and binary manipulation**
- **Cryptographic hashing and SHA-256 padding**
- **Turing Machine simulation**
- **Prime number generation and root extraction**
- **Proof-of-work concepts using leading zero bits**
- **Algorithm complexity and sorting analysis**

Each task includes:
- ✔️ Code implementation
- ✔️ Explanation in plain English
- ✔️ Output and validation

## Tasks Overview
---

| Task | Description | Key Components |
|------|-------------|---------------|
| **Task 1** | **Binary Representations** | • **rotl(x, n)**: Left bit rotation<br>• **rotr(x, n)**: Right bit rotation<br>• **ch(x, y, z)**: Bitwise choice logic<br>• **maj(x, y, z)**: Bitwise majority logic<br><br>*Commonly used in cryptographic hashing like SHA-256.* |
| **Task 2** | **Hash Functions** | • Converts a C-style hash function to Python<br>• Explains use of constants **31** and **101** in hashing<br>• Demonstrates step-by-step string-to-hash conversion |
| **Task 3** | **SHA-256 Padding** | Simulates SHA-256 message padding by:<br>• Appending a **1** bit (`0x80`)<br>• Padding with `0x00` until **448 mod 512**<br>• Adding original message length (**64-bit big-endian**) |
| **Task 4** | **Prime Numbers** | Calculates first 100 prime numbers using two methods:<br>• **Trial Division** (simple, slower)<br>• **Sieve of Eratosthenes** (faster, memory-intensive)<br><br>*Includes comparison table of both approaches.* |
| **Task 5** | **Roots** | • Computes the square roots of the first 100 primes<br>• Extracts the fractional part and converts to **32-bit binary**<br>• Used in cryptographic algorithms (e.g. SHA constants)<br><br>*Based on principles from **Wikipedia – SHA-2 Constants*** |
| **Task 6** | **Proof of Work** | • Uses SHA-256 to hash dictionary words<br>• Identifies words with most leading 0 bits in hash<br>• Validates against standard dictionaries (e.g. `/usr/share/dict/words`) |
| **Task 7** | **Turing Machine** | • Simulates a Turing Machine that adds **1** to binary input<br>• Implements carry logic and halting conditions<br>• Shows real output and state transitions |
| **Task 8** | **Computational Complexity** | • Implements **Bubble Sort**<br>• Applies it to all permutations of `[1, 2, 3, 4, 5]`<br>• Counts and summarizes comparisons<br>• Outputs worst/best case examples |


### **AI Used**
---
| Tool | Purpose | Link |
|------|----------|------|
| GitHub Copilot | Used for code, pattern matching, and Python suggestions  | [GitHub Copilot](https://github.com/features/copilot) |
| ChatGPT | Helped with code structure, debugging, and enhancing conversation patterns | [ChatGPT](https://openai.com/chatgpt) |

## Running the Jupyter Notebook

To run the project locally:

```bash
git clone https://github.com/rosshannon7677/ComputationalTheory

pip install notebook

cd ComputationalTheory

jupyter notebook
```
---

## Contact
For any questions or clarifications, feel free to contact me at G00381859@atu.ie.com.

### Task 1: Binary Representations

Implements low-level bit operations:

- **rotl(x, n)**: Left bit rotation
- **rotr(x, n)**: Right bit rotation
- **ch(x, y, z)**: Bitwise choice logic
- **maj(x, y, z)**: Bitwise majority logic

Commonly used in cryptographic hashing like SHA-256.

### Task 2: Hash Functions

Converts a C-style hash function to Python.

Explains use of constants **31** and **101** in hashing.

Demonstrates step-by-step string-to-hash conversion.

### Task 3: SHA-256 Padding

Simulates SHA-256 message padding by:

- Appending a **1** bit (`0x80`)
- Padding with `0x00` until **448 mod 512**
- Adding original message length (**64-bit big-endian**)

### Task 4: Prime Numbers

Calculates first 100 prime numbers using two methods:

- **Trial Division** (simple, slower)
- **Sieve of Eratosthenes** (faster, memory-intensive)

Includes comparison table of both approaches.

### Task 5: Roots

Computes the square roots of the first 100 primes.

Extracts the fractional part and converts to **32-bit binary**.

Used in cryptographic algorithms (e.g. SHA constants).

Based on principles from **Wikipedia – SHA-2 Constants**

### Task 6: Proof of Work

Uses SHA-256 to hash dictionary words.

Identifies words with most leading 0 bits in hash.

Validates against standard dictionaries (e.g. `/usr/share/dict/words`).

### Task 7: Turing Machine

Simulates a Turing Machine that adds **1** to binary input.

Implements carry logic and halting conditions.

Shows real output and state transitions.

### Task 8: Computational Complexity

Implements **Bubble Sort**.

Applies it to all permutations of `[1, 2, 3, 4, 5]`.

Counts and summarizes comparisons.

Outputs worst/best case examples.