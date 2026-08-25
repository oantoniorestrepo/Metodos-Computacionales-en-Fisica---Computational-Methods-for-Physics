# 🇬🇧 Computational Methods in Physics

Course material for **Computational Methods in Physics**.

[← Back to main README](../README.md)
[🇪🇸 Versión en español](../ES/README.md)

---

## 📚 Contents

### 1. Introduction and tools

| # | Notebook | Description |
|---|---|---|
| 1–3 | [Introduction and Preliminaries](./Classes_1_2_3_Introduction_and_Preliminaries.ipynb) | Working environment, Python and Jupyter; data types, conditionals and loops; lists, tuples, dictionaries and numpy arrays; functions, `args`/`kwargs` and basic scientific libraries (numpy, matplotlib); object-oriented programming (classes, inheritance, decorators, class methods). |
| 4 | [Binary Representation](./04_Binary_Representation.ipynb) | Binary representation of integers and floating-point numbers, the IEEE 754 standard (32 and 64 bits), bitwise operations. |

### 2. Scientific computing

| # | Notebook | Description |
|---|---|---|
| 5 | [Error Theory](./05_Error_Theory.ipynb) | Overflow/underflow, machine epsilon, types of error, subtractive cancellation, numerical catastrophes in the quadratic equation. |
| 6 | [Numerical Stability](./06_Numerical_Stability.ipynb) | Local and global error, algorithmic stability (linear vs. exponential error growth), linearity of computation time. |

### 3. Numerical methods

| # | Notebook | Description |
|---|---|---|
| 7–9 | [Root-Finding Methods](./Classes_7_8_9_Roots.ipynb) | Graphical method, bisection, fixed point, Newton-Raphson, secant, false position (*regula falsi*) and Steffensen's method; applications to physics problems. |
| 10–12 | [Interpolation](./Classes_10_11_12_Interpolation.ipynb) | Linear interpolation, Lagrange polynomial, divided differences, Hermite interpolation, Horner's method and cubic splines. |
| 13 | [Numerical Differentiation](./13_Differentiation.ipynb) | Numerical derivatives by finite differences (forward and central), error analysis and numerical instability. |
| 14–16 | [Numerical Integration](./Classes_14_15_16_Numerical_Integration.ipynb) | Quadrature (Riemann), trapezoidal rule, Simpson's rule, Gaussian quadrature, Romberg's method, improper integrals, the Monte Carlo (von Neumann) method and multiple integrals. |

### 4. Linear algebra

| # | Notebook | Description |
|---|---|---|
| 17–18 | [Linear Algebra](./Classes_17_18_Linear_Algebra.ipynb) | Matrix operations with numpy, effect of multiplying a matrix by a vector, solving linear systems (matrix inversion, Cramer's rule, Gaussian elimination, Jacobi/Gauss-Seidel), matrix inverse and Gauss-Jordan, determinants, computational efficiency. |
| 19–20 | [Matrices with numpy and scipy](./Classes_19_20_Matrices.ipynb) | Real and complex matrices, symmetric/Hermitian/orthogonal/unitary matrices, LU factorisation and special cases (Cholesky, LDL, tridiagonal matrices), diagonalisation and its applications, QR decomposition. |

### 5. Differential equations

| # | Notebook | Description |
|---|---|---|
| 21–23 | [ODE Integration Methods](./Classes_21_22_23_ODE_Integration_Methods.ipynb) | Basic definitions and first-order ODE systems, Euler's method, Verlet and leapfrog methods, second-order (rk2) and fourth-order (rk4) Runge-Kutta, stability and attractors, phase space, Runge-Kutta-Fehlberg method (rk45). |

### 6. Statistics and Monte Carlo

| # | Notebook | Description |
|---|---|---|
| 24–26 | [Statistics and Monte Carlo](./Classes_24_25_26_Statistics_and_Monte_Carlo.ipynb) | Random number generation and descriptive statistics (uniform, exponential, normal and Poisson distributions), Monte Carlo methods in physics: random walks, exponential decay, Poisson processes, least-squares linear regression, law of large numbers. |

### 7. Applications to physics
*Coming soon.*

---

## 🖼️ Figures

Notebooks that include images (diagrams, method illustrations, etc.) reference them from a shared [`figures/`](../figures/) folder at the repository root, common to both versions (ES/EN).

## ▶️ How to use these notebooks

Each notebook is self-contained within its class range (for example, `Classes_7_8_9_Roots.ipynb` includes everything needed for all three classes, with no dependency on other notebooks); simply run it from top to bottom.
