# PageRank Algorithm Implementation

An implementation and experimental study of Google's **PageRank algorithm**, exploring both the theoretical foundations of Markov chains and the practical aspects of large-scale PageRank computation.

## Overview

This repository presents a comprehensive study of Google's **PageRank algorithm**, covering its mathematical foundations, efficient implementation, empirical evaluation, and modern machine learning applications.

Beginning from graph representations and Markov chains, the project derives the Google Matrix, implements PageRank using sparse linear algebra and power iteration, analyzes convergence behaviour, and evaluates computational performance on different graph structures.

Beyond classical PageRank, the project explores **Personalized PageRank**, **graph kernels**, and **PageRank-based node embeddings**, demonstrating how PageRank can be used as a structural representation learning technique for downstream machine learning tasks.
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

## Repository Highlights

The repository investigates several theoretical and practical aspects of PageRank, including:

- Mathematical derivation of the PageRank algorithm
- Random surfer interpretation
- Spectral properties of stochastic matrices
- Handling dangling nodes and rank sinks
- Effect of damping factor on convergence
- Sparse implementations for large graphs
- Performance and memory benchmarking
- Personalized PageRank
- Construction of graph kernels from PageRank diffusion
- Learning node representations using PageRank embeddings

---

## Features

- Classical PageRank implementation
- Sparse matrix implementation for scalability
- Google Matrix construction
- Power Iteration solver
- Personalized PageRank
- Convergence analysis
- Spectral analysis of reducible Markov chains
- Computational complexity analysis
- Memory usage benchmarking
- Graph topology experiments
- PageRank score distribution analysis
- Graph kernels based on diffusion profiles
- PageRank-based node embeddings

---

## Topics Covered

- Graph Theory
- Linear Algebra
- Markov Chains
- Spectral Graph Theory
- Sparse Linear Algebra
- Numerical Methods
- Random Walks
- Eigenvalue Problems
- Personalized PageRank
- Graph Kernels
- Representation Learning
- Node Embeddings

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

## Collaborators

This project was completed collaboratively by:

- **Anupam Dasgupta** (MDS202509)
- **Arkaprabha Chakraborty** (MDS202510)
- **Arnab Chakraborti** (MDS202511)
- **Arushi Marwaha** (MDS202512)


