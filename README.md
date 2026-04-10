# Hierarchical Linear Combination of Unitaries (H-LCU)

This repository contains the official implementation of the framework presented in:
**"Hierarchical Linear Combination of Unitaries (H-LCU): A Recursive Multi-scale Framework for Scalable Quantum Operator Decomposition"** *Scientific Reports (2026).*

## 🔬 Overview
H-LCU is a hierarchical framework for representing quantum operators based on recursive tensorization. Unlike standard flat Pauli expansions, H-LCU organizes coefficients into a tree-structured representation (Quaternary Tree) that separates global and local contributions.

## 🚀 Key Results in this Repository
- **Recursive Decomposition:** Implementation of the tree-based partitioning for $n$-qubit operators.
- **Symmetry-Protected Manifolds:** Tools to isolate essential algebraic correlations in structured systems.
- **Benchmarks:**
  - **TFIM (Transverse Field Ising Model):** Demonstrating >99% compression in structured manifolds.
  - **Block-Toeplitz Models:** Achieving 42.2% density through hierarchical sparsity.
  - **Haar-random Matrices:** Comparative analysis of entropy and compressibility.

## 📂 Repository Structure
- `/core`: The recursive H-LCU algorithm and connectivity matrix (Aµ) logic.
- `/benchmarks`: Scripts to reproduce the TFIM and Toeplitz compression results.
- `/scripts`: Tools for visualizing the hierarchical sparsity patterns.

## 📜 Citation
Luis J. M. Santa Cruz, Luis F. Faina, and João H. S. Pereira. "Hierarchical Linear Combination of Unitaries (H-LCU): A Recursive Multi-scale Framework for Scalable Quantum Operator Decomposition". *Scientific Reports* (2026).
