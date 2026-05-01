# Deutsch–Jozsa Algorithm Implementation (Qiskit)

## Overview

This project implements Deutsch’s algorithm and the Deutsch–Jozsa algorithm using Qiskit.  
The goal is to demonstrate how quantum computing can determine global properties of Boolean functions using only a single oracle query.

The project includes:
- Generation of constant and balanced Boolean functions
- Construction of quantum oracles
- Implementation of Deutsch’s algorithm (1-bit case)
- Implementation of the Deutsch–Jozsa algorithm (4-bit case)
- Demonstration of quantum interference used to distinguish function types

---

## Project Structure

- `problems.ipynb` → Main notebook containing all implementations and results
- `data/` → (if applicable) datasets used in experiments
- `img/` → Generated circuit diagrams or figures
- `requirements.txt` → Required Python dependencies

---

## Setup Instructions

Clone the repository:

```bash
git clone <repo-url>
cd <repo-folder>

Install dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook problems.ipynb