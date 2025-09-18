# Quantum MaxCut with QAOA

This project demonstrates how to solve the **MaxCut problem** on a small graph using the **Quantum Approximate Optimization Algorithm (QAOA)** implemented with [Qiskit](https://qiskit.org/).

## 📖 Overview

- Builds a parameterized QAOA circuit for a 5-node graph.
- Optimizes the parameters using classical optimization (`scipy.optimize.minimize`).
- Visualizes:
  - The input graph.
  - The final QAOA circuit.
  - The resulting cut assignment.
- Prints the top measured bitstrings and their probabilities.

This is intended as an educational notebook to illustrate hybrid quantum-classical optimization workflows.

## 🛠 Dependencies

Make sure you have the following Python libraries installed:

```bash
pip install qiskit networkx scipy numpy matplotlib
```

## ▶️ Usage

Run the notebook step by step:

1. Open the notebook:

```bash
jupyter notebook "Quantum project.ipynb"
```

2. Execute all cells to:
   - Build the graph.
   - Optimize the QAOA parameters.
   - Visualize results and solutions.

## 📂 Project Structure

```
.
├── Quantum project.ipynb  # Main notebook with QAOA MaxCut implementation
├── README.md              # Project documentation
└── .gitignore             # Ignore cache, outputs, and environment files
```

## 📜 License

This project is for educational purposes. You may use, modify, and share it under an open-source license of your choice.
