# Simulaciones Cuánticas y Desafíos de Programación - Capítulo 4

Este repositorio contiene la implementación de simulaciones cuánticas y desafíos de programación basados en los conceptos del Capítulo 4 de un curso de mecánica cuántica. Se exploran las probabilidades de transición, el cálculo de valores propios, y la dinámica del sistema a través de operaciones sobre vectores de estado y matrices unitarias. Además, se incluyen ejemplos y soluciones de problemas específicos planteados en los ejercicios.

## Contenidos

### 1. Simulación del Primer Sistema Cuántico (Sección 4.1)
Este sistema simula la evolución de una partícula restringida a un conjunto discreto de posiciones en una línea. El simulador te permite:

- **Definir el número de posiciones:** Se crea un vector de estado (ket) con amplitudes asignadas a cada posición.
- **Calcular la probabilidad de encontrar la partícula en una posición específica:** Utiliza las amplitudes cuánticas para determinar la probabilidad de localizar la partícula en un punto dado.
- **Transición entre estados:** Calcula la probabilidad de transitar de un vector ket inicial a otro vector ket después de una observación.

### 2. Desafíos de Programación del Capítulo 4

- **Amplitud de Transición:**
  - Calcula la probabilidad de transitar de un estado inicial a un estado final dado dos vectores de estado (ket). Esto implica evaluar las amplitudes de transición entre los estados y aplicar las reglas cuánticas para obtener la probabilidad.

- **Media y Varianza de un Observable:**
  - Dado un observable representado por una matriz, primero se verifica si es hermitiana (condición necesaria para ser un observable en mecánica cuántica). Si la matriz cumple con esta propiedad, se calcula la media y la varianza del observable en un estado dado.

- **Cálculo de Valores Propios y Probabilidad de Transición:**
  - Se calculan los valores propios de un observable (matriz) y las probabilidades de transitar a uno de sus vectores propios después de la observación. Esto implica la diagonalización de la matriz y el cálculo de probabilidades cuánticas asociadas.

- **Dinámica del Sistema:**
  - Dado un estado inicial y una serie de matrices unitarias que describen la evolución temporal del sistema, se calcula el estado final tras aplicar estas matrices. Este proceso permite estudiar la dinámica cuántica de un sistema bajo diferentes transformaciones unitarias.

### 3. Problemas Incluidos

Los siguientes modelos de problemas están implementados en la biblioteca como ejemplos:

- **Problema 4.3.1:** Evolución cuántica en sistemas de dos estados.
- **Problema 4.3.2:** Cálculo de la probabilidad de transición en un sistema de posiciones discretas.
- **Problema 4.4.1:** Media y varianza de un observable en un estado dado.
- **Problema 4.4.2:** Valores propios de un observable y transición a vectores propios.

### 4. Discusión en GitHub

- **Ejercicios 4.5.2 y 4.5.3:** Se discuten y desarrollan en el repositorio de GitHub. Aquí, se anima a los usuarios a contribuir con sus propias soluciones y enfoques a estos problemas.

## Librerías

Este proyecto utiliza las siguientes librerías de Python:

- **NumPy:** Para realizar cálculos matriciales, como la multiplicación de matrices y la obtención de valores propios.
- **Matplotlib:** Para la visualización de probabilidades cuánticas y evolución del sistema.

Asegúrate de tener instaladas estas dependencias antes de ejecutar el código.

```bash
pip install numpy matplotlib

