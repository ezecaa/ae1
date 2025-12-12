# Optimización Metaheurística de Problemas de Logística Compleja (TSP y VRP)

Este repositorio contiene la resolución de dos problemas clásicos de optimización combinatoria utilizando **Algoritmos Genéticos (GA)**. El proyecto forma parte del Trabajo Final para la materia **Algoritmos Evolutivos I**.

## 👤 Información del Autor
* **Materia:** Algoritmos Evolutivos I
* **Carrera:** Especialización en Inteligencia Artificial (EIA)
* **Institución:** Universidad de Buenos Aires (FIUBA)
* **Alumno:** Ezequiel Alejandro Caamaño (a1802)

## 📌 Resumen del Proyecto
El objetivo de este trabajo es implementar y comparar la eficiencia de los Algoritmos Genéticos para resolver:
1.  **TSP (Traveling Salesman Problem):** Optimización de una ruta única para visitar 20 ciudades.
2.  **VRP (Vehicle Routing Problem):** Distribución logística con 3 vehículos y restricciones de capacidad de carga.

Se utilizó la librería **PyGAD** para el motor evolutivo, aplicando técnicas de mapeo indirecto (`argsort`) y funciones de fitness con penalizaciones adaptativas.



## 📂 Estructura del Repositorio
* `tsp-ga.ipynb`: Notebook con la implementación detallada del TSP. Incluye 6 paneles de análisis de métricas.
* `vrp-ga.ipynb`: Notebook con la implementación del VRP. Incluye la lógica de penalizaciones y 9 paneles de análisis.
* `Informe Trabajo Final.pdf`: El documento técnico completo con el análisis teórico, la discusión de la convergencia y las conclusiones.
* `tsp_ga_results.png`: Visualización de los gráficos de rendimiento del TSP.
* `vrp_ga_results.png`: Visualización de los gráficos de rendimiento del VRP.

## 🛠️ Requisitos
Para la ejecución y visualización de los notebooks, se requiere el siguiente entorno de Python:
```bash
pip install pygad numpy matplotlib scipy