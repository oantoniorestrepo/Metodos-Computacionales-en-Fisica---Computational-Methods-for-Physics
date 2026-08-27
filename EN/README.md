# 🇬🇧 Computational Methods in Physics

Course material for **Computational Methods in Physics**. (Second-year undergraduate Physics course).

[← Back to main README](../README.md)
[🇪🇸 Versión en español](../ES/README.md)

[![Run notebooks](https://github.com/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/actions/workflows/test-notebooks.yml/badge.svg)](https://github.com/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/actions/workflows/test-notebooks.yml)

---

## 📚 Contents

### 1. Introduction and tools

| # | Notebook | Description | Colab |
|---|---|---|---|
| 1–3 | [Introduction and Preliminaries](./Classes_1_2_3_Introduction_and_Preliminaries.ipynb) | Working environment, Python and Jupyter; data types, conditionals and loops; lists, tuples, dictionaries and numpy arrays; functions, `args`/`kwargs` and basic scientific libraries (numpy, matplotlib); object-oriented programming (classes, inheritance, decorators, class methods). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Classes_1_2_3_Introduction_and_Preliminaries.ipynb) |
| 4 | [Binary Representation](./Class_04_Binary_Representation.ipynb) | Binary representation of integers and floating-point numbers, the IEEE 754 standard (32 and 64 bits), bitwise operations. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Class_04_Binary_Representation.ipynb) |

### 2. Error theory and stability

| # | Notebook | Description | Colab |
|---|---|---|---|
| 5 | [Error Theory](./Class_05_Error_Theory.ipynb) | Overflow/underflow, machine epsilon, types of error, subtractive cancellation, numerical catastrophes in the quadratic equation. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Class_05_Error_Theory.ipynb) |
| 6 | [Numerical Stability](./Class_06_Numerical_Stability.ipynb) | Local and global error, algorithmic stability (linear vs. exponential error growth), linearity of computation time. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Class_06_Numerical_Stability.ipynb) |

### 3. Roots, interpolation, differentiation and integration

| # | Notebook | Description | Colab |
|---|---|---|---|
| 7–9 | [Root-Finding Methods](./Classes_7_8_9_Roots.ipynb) | Graphical method, bisection, fixed point, Newton-Raphson, secant, false position (*regula falsi*) and Steffensen's method; applications to physics problems. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Classes_7_8_9_Roots.ipynb) |
| 10–12 | [Interpolation](./Classes_10_11_12_Interpolation.ipynb) | Linear interpolation, Lagrange polynomial, divided differences, Hermite interpolation, Horner's method and cubic splines. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Classes_10_11_12_Interpolation.ipynb) |
| 13 | [Numerical Differentiation](./13_Differentiation.ipynb) | Numerical derivatives by finite differences (forward and central), error analysis and numerical instability. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/13_Differentiation.ipynb) |
| 14–16 | [Numerical Integration](./Classes_14_15_16_Numerical_Integration.ipynb) | Quadrature (Riemann), trapezoidal rule, Simpson's rule, Gaussian quadrature, Romberg's method, improper integrals, the Monte Carlo (von Neumann) method and multiple integrals. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Classes_14_15_16_Numerical_Integration.ipynb) |

### 4. Linear algebra

| # | Notebook | Description | Colab |
|---|---|---|---|
| 17–18 | [Linear Algebra](./Classes_17_18_Linear_Algebra.ipynb) | Matrix operations with numpy, effect of multiplying a matrix by a vector, solving linear systems (matrix inversion, Cramer's rule, Gaussian elimination, Jacobi/Gauss-Seidel), matrix inverse and Gauss-Jordan, determinants, computational efficiency. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Classes_17_18_Linear_Algebra.ipynb) |
| 19–20 | [Matrices with numpy and scipy](./Classes_19_20_Matrices.ipynb) | Real and complex matrices, symmetric/Hermitian/orthogonal/unitary matrices, LU factorisation and special cases (Cholesky, LDL, tridiagonal matrices), diagonalisation and its applications, QR decomposition. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Classes_19_20_Matrices.ipynb) |

### 5. Differential equations

| # | Notebook | Description | Colab |
|---|---|---|---|
| 21–23 | [ODE Integration Methods](./Classes_21_22_23_ODE_Integration_Methods.ipynb) ⚠️ | Basic definitions and first-order ODE systems, Euler's method, Verlet and leapfrog methods, second-order (rk2) and fourth-order (rk4) Runge-Kutta, stability and attractors, phase space, Runge-Kutta-Fehlberg method (rk45). | — |

> ⚠️ **This notebook intentionally has no Colab button.** Several cells open an interactive window (`Qt5Agg` backend) to animate the pendulum, the orbits and the Lorenz attractor in real time. **To see the animations, download the notebook and run it in Jupyter on your own computer.**

### 6. Statistics and simulation

| # | Notebook | Description | Colab |
|---|---|---|---|
| 24–26 | [Statistics and Monte Carlo](./Classes_24_25_26_Statistics_and_Monte_Carlo.ipynb) | Random number generation and descriptive statistics (uniform, exponential, normal and Poisson distributions), Monte Carlo methods in physics: random walks, exponential decay, Poisson processes, least-squares linear regression, law of large numbers. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/EN/Classes_24_25_26_Statistics_and_Monte_Carlo.ipynb) |

---

## 🖼️ Figures

Notebooks that include images (diagrams, method illustrations, etc.) reference them from a shared [`figures/`](../figures/) folder at the repository root, common to both versions (ES/EN).

## ▶️ How to use these notebooks

Each notebook is self-contained; simply run it from beginning to end, either locally or using the **Open in Colab** button in the table above. Some notebooks require downloading because they open pop-up windows, such as Lessons 13 or 21-23 (EDO), which must be run locally since their animation cells depend on pop-up windows.
