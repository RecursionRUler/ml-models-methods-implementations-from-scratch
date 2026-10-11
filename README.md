# ML Models & Methods — Implementations from Scratch

A collection of machine learning algorithms implemented from scratch to understand their underlying mathematics, optimization techniques, and mechanics.

Rather than relying on high-level ML libraries, this project focuses on building algorithms step by step using **Python and NumPy**.

The goal is simple: **understand what's happening under the hood.**

---

## Implementations

This repository is an ongoing learning project. Each implementation focuses on understanding the algorithm's mathematical foundations and translating them into working code.

### 1. Gradient Descent

Exploring gradient-based optimization and how model parameters are updated to minimize a loss function.

| Method | Implementation | Key Concepts |
|---|---|---|
| Batch Gradient Descent | [`own_batch_gdreg.ipynb`](gradient_descent/own_batch_gdreg.ipynb) | Full-dataset gradients, learning rate, loss minimization |
| Stochastic Gradient Descent (SGD) | [`own_stochastic_gdreg.ipynb`](gradient_descent/own_stochastic_gdreg.ipynb) | Sample-wise updates, stochastic optimization, convergence |

**Concepts explored:**
- Gradients and partial derivatives
- Loss functions and parameter updates
- Learning rates and convergence
- Batch versus stochastic optimization
- The effect of gradient updates on model training

---

## Tech Stack

- **Python** — Core implementation
- **NumPy** — Numerical computation and array operations
- **Jupyter Notebook** — Interactive implementation and experimentation

The implementations prioritize understanding the underlying mechanics rather than hiding them behind high-level abstractions.

---

## Learning Objectives

- Implement machine learning algorithms from scratch.
- Understand the mathematics behind optimization algorithms.
- Develop an intuition for gradients, loss functions, and parameter updates.
- Compare optimization methods and understand their trade-offs.
- Experiment with hyperparameters and observe their effects on convergence.
- Build a strong foundation for implementing more advanced ML models.

---

## Roadmap

### Optimization Algorithms
- [x] Batch Gradient Descent
- [x] Stochastic Gradient Descent
- [ ] Mini-Batch Gradient Descent

### Machine Learning Models
- [ ] Linear Regression from scratch
- [ ] Logistic Regression from scratch
- [ ] Regularization techniques
- [ ] Model evaluation and experimentation

*This roadmap will evolve as the project develops.*

---

## Project Structure

```text
ml-model-implementations/
├── gradient_descent/
│   ├── own_batch_gdreg.ipynb
│   └── own_stochastic_gdreg.ipynb
├── .gitignore
└── README.md
```

---

## Project Status

**Actively developing.**

This project documents my progress in understanding machine learning from the ground up through mathematical exploration, implementation, and experimentation.

Each algorithm is an opportunity to strengthen my understanding of the mathematics behind machine learning and how it translates into code.

Future implementations will expand into additional optimization techniques and machine learning models.

---

## Author

**RecursionRuler**

*Learning machine learning by building it from the ground up.*