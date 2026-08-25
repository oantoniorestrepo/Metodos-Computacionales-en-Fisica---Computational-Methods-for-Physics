# 🇪🇸 Métodos Computacionales en Física

Material del curso de **Métodos Computacionales en Física**.

[← Volver al README principal](../README.md)
[🇬🇧 English version](../EN/README.md)

---

## 📚 Contenido

### 1. Introducción y herramientas

| # | Notebook | Descripción |
|---|---|---|
| 1–3 | [Introducción y Preliminares](./Clases_1_2_3_Introduccion_y_Preliminares.ipynb) | Entorno de trabajo, Python y Jupyter; tipos de datos, condicionales y bucles; listas, tuplas, diccionarios y arrays de numpy; funciones, `args`/`kwargs` y librerías científicas básicas (numpy, matplotlib); programación orientada a objetos (clases, herencia, decoradores, métodos de clase). |
| 4 | [Representación Binaria](./04_Representacion_Binaria.ipynb) | Representación de enteros y números de punto flotante en binario, estándar IEEE 754 (32 y 64 bits), operaciones bit a bit (`bitwise`). |

### 2. Computación científica

| # | Notebook | Descripción |
|---|---|---|
| 5 | [Teoría de Errores](./05_Teoria_de_Errores.ipynb) | *Overflow*/*underflow*, épsilon de máquina, tipos de error, cancelación sustractiva, catástrofes numéricas en la ecuación cuadrática. |
| 6 | [Estabilidad Numérica](./06_Estabilidad_Numerica.ipynb) | Error local y global, estabilidad algorítmica (crecimiento lineal vs. exponencial del error), linealidad del tiempo de cómputo. |

### 3. Métodos numéricos

| # | Notebook | Descripción |
|---|---|---|
| 7–9 | [Raíces de Ecuaciones](./Clases_7_8_9_Raices.ipynb) | Método gráfico, bisección, punto fijo, Newton-Raphson, secante, posición falsa (*regula falsi*) y Steffensen; aplicaciones a problemas de física. |
| 10–12 | [Interpolación](./Clases_10_11_12_Interpolacion.ipynb) | Interpolación lineal, polinomio de Lagrange, diferencias divididas, interpolación de Hermite, método de Horner y splines cúbicos. |
| 13 | [Diferenciación Numérica](./13_Diferenciacion.ipynb) | Derivadas numéricas por diferencias finitas (adelante y centrada), análisis de error e inestabilidad numérica. |
| 14–16 | [Integrales Numéricas](./Clases_14_15_16_Integrales_Numericas.ipynb) | Cuadratura (Riemann), trapecio, Simpson, cuadratura gaussiana, método de Romberg, integrales impropias, método de Monte Carlo (von Neumann) e integrales múltiples. |

### 4. Álgebra lineal

| # | Notebook | Descripción |
|---|---|---|
| 17–18 | [Álgebra Lineal](./Clases_17_18_Algebra_Lineal.ipynb) | Operaciones matriciales con numpy, efecto de multiplicar una matriz por un vector, solución de sistemas lineales (inversión, regla de Cramer, eliminación gaussiana, Jacobi/Gauss-Seidel), matriz inversa y Gauss-Jordan, determinantes, eficiencia computacional. |
| 19–20 | [Matrices con numpy y scipy](./Clases_19_20_Matrices.ipynb) | Matrices reales y complejas, matrices simétricas/hermíticas/ortogonales/unitarias, factorización LU y casos especiales (Cholesky, LDL, matrices tridiagonales), diagonalización y sus aplicaciones, descomposición QR. |

### 5. Ecuaciones diferenciales

| # | Notebook | Descripción |
|---|---|---|
| 21–23 | [Métodos de Integración de EDO](./Clases_21_22_23_Metodos_de_integracion_EDO.ipynb) | Definiciones básicas y sistemas de EDO de primer orden, método de Euler, métodos de Verlet y leapfrog, Runge-Kutta de segundo orden (rk2) y cuarto orden (rk4), estabilidad y atractores, espacio fásico, método de Runge-Kutta-Fehlberg (rk45). |

### 8. Estadística y simulación

| # | Notebook | Descripción |
|---|---|---|
| 24–26 | [Estadística y Monte Carlo](./Clases_24_25_26_Estadistica_y_Monte_Carlo.ipynb) | Generación de números aleatorios y estadística descriptiva (distribuciones uniforme, exponencial, normal, Poisson), métodos de Monte Carlo en física: caminatas aleatorias, decaimiento exponencial, procesos de Poisson, regresión lineal por mínimos cuadrados, ley de los grandes números. |

---

## 🖼️ Figuras

Los notebooks que incluyen imágenes (diagramas, capturas de métodos, etc.) las referencian desde una carpeta compartida [`figures/`](../figures/) en la raíz del repositorio, común a ambas versiones (ES/EN).

## ▶️ Cómo usar estos notebooks

Cada notebook es autocontenido dentro de su rango de clases (por ejemplo, `Clases_7_8_9_Raices.ipynb` incluye todo lo necesario para las tres clases, sin depender de otros notebooks); basta con ejecutarlo de principio a fin.
