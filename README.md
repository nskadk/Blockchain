# Blockchain Technology Fundamentals - Assignment 1

## Author
- **SID:** S3979030
- **Name:** Nguyen Phuc Doan
- **Lecturer:** Dr. Jeff Nijsse
- **Subject:** INTE264[1|2] - Blockchain Technology Fundamentals
- **Assignment:** 1
- **Due Date:** 12:00pm, 25th Jul 2025

---

## Project Overview
This repository contains Python code and a Jupyter notebook demonstrating key concepts in blockchain technology:
- **Hash Functions:** Avalanche effect, brute-force preimage attacks, and hash security analysis.
- **Merkle Tree:** Efficient data integrity verification and proof generation.
- **Digital Signature:** RSA-based signing and verification for authenticity and non-repudiation.
- **Simple Blockchain:** Block creation, chaining, and timestamping.

---

## File Structure
- `hash.ipynb` : Main Jupyter notebook with all code, explanations, and output analysis.
- `README.md`: This documentation and usage guide.

---

## Requirements
- Python 3.8+
- Jupyter Notebook
- Required packages:
  - `cryptography`
  - `hashlib` (built-in)
  - `secrets` (built-in)
  - `itertools` (built-in)
  - `string` (built-in)

Install the required package with:
```bash
pip install cryptography
```

---

## How to Run

### 1. Open the Notebook
- Launch Jupyter Notebook:
  ```bash
  jupyter notebook
  ```
- Open `hash.ipynb` in your browser.

### 2. Run the Code
- Step through each cell in order for explanations and output
- To re-run any block:
  - Click the ▶ (Run) button to the left of the cell, or
  - Select the cell and press ```Shift + Return (Mac/Linux)``` or ```Shift + Enter (Windows)```.
- The notebook covers:
  - Hash function demonstrations
  - Avalanche effect and brute-force attacks
  - Merkle tree construction and proof verification
  - Digital signature creation and validation
  - Simple blockchain block creation
---

## References
- Hash and Merkle tree code adapted from: [Blockchain-for-Developers/merkle-tree](https://github.com/Blockchain-for-Developers/merkle-tree)
- Digital signature code adapted from: [dev.to/0x2633](https://dev.to/0x2633/the-flow-of-creating-digital-signature-and-verification-in-python-37ng)

