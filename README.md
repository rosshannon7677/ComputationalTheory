# Computational Theory

This repository contains work for the **Computational Theory** module completed as part of a fourth-year assessment at ATU.  
The assessment is delivered through a Jupyter Notebook and contains code, explanations, and results for eight tasks.

---

## Aim

The notebook is designed to help demonstrate and explore key computational theory concepts:

- **Bitwise manipulation and binary representations**  
- **Cryptographic hashing and padding techniques**  
- **Turing Machine design and state transitions**  
- **Sorting and complexity analysis of algorithms**  
- **Mathematical number theory, including primes and roots**  

Each task includes implementation, output, and explanations directly in the notebook.

---

## Tasks Overview

The project is divided into 8 separate tasks:

### **Task 1: Binary Representations**
Implements bit-level functions such as:
- Left and right bit rotations
- Bitwise choose (ch) and majority (maj) functions  
These operations are widely used in cryptographic algorithms like SHA-256.

### **Task 2: Hash Functions**
Converts a classic C hash function into Python.  
Explains the choice of multipliers and modulus (`31` and `101`) with reference to efficient hashing and reduced collisions.

### **Task 3: SHA-256 Padding**
Simulates the padding step of SHA-256:
- Appends a `1` bit (`0x80`)
- Pads with zeros until the message is 448 mod 512
- Adds the original message length as a 64-bit big-endian integer  

### **Task 4: Prime Numbers**
Calculates the first 100 prime numbers using:
- Trial Division  
- Sieve of Eratosthenes  
Each method is explained with advantages/disadvantages and outputs shown.

### **Task 5: Roots**
Finds the first **32 bits of the fractional part** of the square root for each of the first 100 prime numbers.  
Used to simulate how constants in SHA algorithms are derived.

### **Task 6: Proof of Work**
Finds dictionary words that produce SHA-256 hashes with the most leading zero bits.  
Proves word validity using standard wordlists (e.g., `/usr/share/dict/words`).

### **Task 7: Turing Machine**
Simulates a Turing Machine that adds `1` to a binary number.  
Implements the binary carry logic and presents the state transition table.

### **Task 8: Computational Complexity**
Implements **Bubble Sort** and counts comparisons for **all permutations** of `[1,2,3,4,5]`.  
This helps demonstrate the worst-case complexity of simple algorithms.

---

## Running the Jupyter Notebook

To run this notebook locally:

### 1. **Clone the Repository**
```bash
git clone https://github.com/YourUsername/ComputationalTheory

pip install notebook

cd ComputationalTheory

jupyter notebook


Contact
Ross Hannon 📧 G00381859@atu.ie