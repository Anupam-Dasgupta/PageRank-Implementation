# PageRank Algorithm Implementation

An implementation and experimental study of Google's **PageRank algorithm**, exploring both the theoretical foundations of Markov chains and the practical aspects of large-scale PageRank computation.

## Overview

This repository contains multiple implementations and experiments investigating how PageRank behaves under different settings, including:

- Sparse matrix implementations
- Convergence analysis
- Scaling behaviour
- Effect of teleportation (damping factor)
- Spectral analysis of reducible Markov chains
- Initialization strategy comparisons
- Visualization of convergence

The project was completed as part of coursework exploring numerical linear algebra and stochastic processes.

---

## Repository Structure

```
.
├── pagerank_sparse.ipynb
├── pagerank_scaling.ipynb
├── pagerank_sparse_alpha_convergence.ipynb
├── pagerank_sparse_with_init_comparison.ipynb
├── pagerank_sparse_with_visuals.ipynb
├── Comparison with and without teleportation.ipynb
├── Spectral Analysis of Reducible Markov Chains.ipynb
└── LAA_Report.pdf
```

---

## Experiments

The notebooks investigate several important properties of PageRank:

- Sparse matrix implementation for efficiency
- Convergence speed under different damping factors
- Effect of teleportation on reducible graphs
- Scaling behaviour as graph size increases
- Influence of different initialization vectors
- Spectral properties of transition matrices
- Visualizations of convergence dynamics

---

## Topics Covered

- Markov Chains
- Eigenvalue Problems
- Power Iteration
- Sparse Linear Algebra
- Graph Algorithms
- Numerical Linear Algebra
- Google's PageRank Algorithm

---

## Technologies

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

---

## Report

The repository also includes a written report (`LAA_Report.pdf`) describing the mathematical background, implementation details, and experimental observations.

---

## Future Improvements

Potential extensions include:

- Personalized PageRank
- Parallel implementations
- GPU acceleration
- Comparison with NetworkX implementation
- Large real-world graph datasets

---

