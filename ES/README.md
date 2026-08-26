# 🇪🇸 Métodos Computacionales en Física

Material del curso de **Métodos Computacionales en Física**.

[← Volver al README principal](../README.md)
[🇬🇧 English version](../EN/README.md)

[![Ejecutar notebooks](https://github.com/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/actions/workflows/test-notebooks.yml/badge.svg)](https://github.com/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/actions/workflows/test-notebooks.yml)

---

## 📚 Contenido

Cada notebook tiene un botón **Open in Colab**: lo abre directamente en tu navegador, sin instalar nada, con la última versión del archivo en la rama `main`.

### 1. Introducción y herramientas

| # | Notebook | Descripción | Colab |
|---|---|---|---|
| 1–3 | [Introducción y Preliminares](./Clases_1_2_3_Introduccion_y_Preliminares.ipynb) | Entorno de trabajo, Python y Jupyter; tipos de datos, condicionales y bucles; listas, tuplas, diccionarios y arrays de numpy; funciones, `args`/`kwargs` y librerías científicas básicas (numpy, matplotlib); programación orientada a objetos (clases, herencia, decoradores, métodos de clase). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/Clases_1_2_3_Introduccion_y_Preliminares.ipynb) |
| 4 | [Representación Binaria](./04_Representacion_Binaria.ipynb) | Representación de enteros y números de punto flotante en binario, estándar IEEE 754 (32 y 64 bits), operaciones bit a bit (`bitwise`). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/04_Representacion_Binaria.ipynb) |

### 2. Computación científica

| # | Notebook | Descripción | Colab |
|---|---|---|---|
| 5 | [Teoría de Errores](./05_Teoria_de_Errores.ipynb) | *Overflow*/*underflow*, épsilon de máquina, tipos de error, cancelación sustractiva, catástrofes numéricas en la ecuación cuadrática. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/05_Teoria_de_Errores.ipynb) |
| 6 | [Estabilidad Numérica](./06_Estabilidad_Numerica.ipynb) | Error local y global, estabilidad algorítmica (crecimiento lineal vs. exponencial del error), linealidad del tiempo de cómputo. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/06_Estabilidad_Numerica.ipynb) |

### 3. Métodos numéricos

| # | Notebook | Descripción | Colab |
|---|---|---|---|
| 7–9 | [Raíces de Ecuaciones](./Clases_7_8_9_Raices.ipynb) | Método gráfico, bisección, punto fijo, Newton-Raphson, secante, posición falsa (*regula falsi*) y Steffensen; aplicaciones a problemas de física. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/Clases_7_8_9_Raices.ipynb) |
| 10–12 | [Interpolación](./Clases_10_11_12_Interpolacion.ipynb) | Interpolación lineal, polinomio de Lagrange, diferencias divididas, interpolación de Hermite, método de Horner y splines cúbicos. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/Clases_10_11_12_Interpolacion.ipynb) |
| 13 | [Diferenciación Numérica](./13_Diferenciacion.ipynb) | Derivadas numéricas por diferencias finitas (adelante y centrada), análisis de error e inestabilidad numérica. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/13_Diferenciacion.ipynb) |
| 14–16 | [Integrales Numéricas](./Clases_14_15_16_Integrales_Numericas.ipynb) | Cuadratura (Riemann), trapecio, Simpson, cuadratura gaussiana, método de Romberg, integrales impropias, método de Monte Carlo (von Neumann) e integrales múltiples. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/Clases_14_15_16_Integrales_Numericas.ipynb) |

### 4. Álgebra lineal

| # | Notebook | Descripción | Colab |
|---|---|---|---|
| 17–18 | [Álgebra Lineal](./Clases_17_18_Algebra_Lineal.ipynb) | Operaciones matriciales con numpy, efecto de multiplicar una matriz por un vector, solución de sistemas lineales (inversión, regla de Cramer, eliminación gaussiana, Jacobi/Gauss-Seidel), matriz inversa y Gauss-Jordan, determinantes, eficiencia computacional. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/Clases_17_18_Algebra_Lineal.ipynb) |
| 19–20 | [Matrices con numpy y scipy](./Clases_19_20_Matrices.ipynb) | Matrices reales y complejas, matrices simétricas/hermíticas/ortogonales/unitarias, factorización LU y casos especiales (Cholesky, LDL, matrices tridiagonales), diagonalización y sus aplicaciones, descomposición QR. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/Clases_19_20_Matrices.ipynb) |

### 5. Ecuaciones diferenciales

| # | Notebook | Descripción | Colab |
|---|---|---|---|
| 21–23 | [Métodos de Integración de EDO](./Clases_21_22_23_Metodos_de_integracion_EDO.ipynb) ⚠️ | Definiciones básicas y sistemas de EDO de primer orden, método de Euler, métodos de Verlet y leapfrog, Runge-Kutta de segundo orden (rk2) y cuarto orden (rk4), estabilidad y atractores, espacio fásico, método de Runge-Kutta-Fehlberg (rk45). | — |

> ⚠️ **Este notebook no tiene botón de Colab a propósito.** Varias celdas abren una ventana interactiva (backend `Qt5Agg`) para animar el péndulo, las órbitas y el atractor de Lorenz en tiempo real. Ni Colab ni CI tienen pantalla, así que esas celdas no muestran nada ahí (el notebook corre igual, sin errores, pero sin animación). **Para ver las animaciones, descarga el notebook y ejecútalo en Jupyter en tu computador.**

### 6. Aplicaciones a la física
*Próximamente.*

### 7. Estadística y simulación

| # | Notebook | Descripción | Colab |
|---|---|---|---|
| 24–26 | [Estadística y Monte Carlo](./Clases_24_25_26_Estadistica_y_Monte_Carlo.ipynb) | Generación de números aleatorios y estadística descriptiva (distribuciones uniforme, exponencial, normal, Poisson), métodos de Monte Carlo en física: caminatas aleatorias, decaimiento exponencial, procesos de Poisson, regresión lineal por mínimos cuadrados, ley de los grandes números. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oantoniorestrepo/Metodos-Computacionales-en-Fisica---Computational-Methods-for-Physics/blob/main/ES/Clases_24_25_26_Estadistica_y_Monte_Carlo.ipynb) |

---

## 🖼️ Figuras

Los notebooks que incluyen imágenes (diagramas, capturas de métodos, etc.) las referencian desde una carpeta compartida [`figures/`](../figures/) en la raíz del repositorio, común a ambas versiones (ES/EN).

## ▶️ Cómo usar estos notebooks

Cada notebook es autocontenido dentro de su rango de clases (por ejemplo, `Clases_7_8_9_Raices.ipynb` incluye todo lo necesario para las tres clases, sin depender de otros notebooks); basta con ejecutarlo de principio a fin, ya sea localmente o con el botón **Open in Colab** de la tabla de arriba.

## ✅ Integración continua (CI)

Este repositorio usa [GitHub Actions](../.github/workflows/test-notebooks.yml) para ejecutar automáticamente **todos** los notebooks (ES y EN) en cada `push` y cada *pull request*: si alguna celda lanza un error, el workflow falla y queda registrado en la pestaña *Actions* del repositorio, antes de que el problema llegue a `main`.

La Clase 21-23 (EDO) se ejecuta en un job aparte, ya que sus celdas de animación dependen de una pantalla; ahí solo se valida que el código no truene, no que la animación se vea (eso solo se puede comprobar en local).
READMEEOF
