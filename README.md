# 📊 Ejemplo de un Modelo Predictivo utilizando Apache Spark con MLlib

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License:](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.io/badge/Status-Completed-success)]()

> **Resumen:** El siguiente ejemplo utiliza un Data Set ficticio para diseñar un modelo supervisado de clasificación con MLlib. Los datos pasan por los procesos de Limpieza, entrenamiento y evaluación del Modelo, y por ultimo obtener conclusiones técnicas

# Data Set

> **Data Sets apoyo:** 03. Apoyo prueba - ventas_simuladas.xlsx / ventas_simuladas.csv

---

## 📌 Tabla de Contenidos
- [Descripción del Proyecto](#-descripción-del-proyecto)
- [Data Set](#-Data-Set)
- [Estructura del Repositorio](#-estructura-del-repositorio)
- [Metodología](#-metodología)
- [Resultados y Conclusiones](#-resultados-y-conclusiones)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación y Uso](#-instalación-y-uso)
- [Contacto](#-ctobarj7@gmail.com)

---

## 🎯 Descripción del Proyecto

Se eligió el modelo de Regresión Logística porque es uno de los métodos más simples para resolver
problemas de clasificación binaria y permite predecir si una transacción pertenece a la categoría riesgosa o
normal. Además, es un modelo relativamente fácil de interpretar y de implementar utilizando Spark MLlib.

### Objetivos Clave:
* **Objetivo 1:** [Realizar un análisis exploratorio de datos (EDA)]
* **Objetivo 2:** [Limpiar los datos, Entrenar y comparar modelos de clasificación).]
* **Objetivo 3:** [Obtener Coclusiones Tecnicas]

---

## 📂 Estructura del Repositorio

```text
├── data/
│   ├── raw/              # Datos originales (sin procesar)
│   └── processed/        # Datos limpios y listos para modelar
├── notebooks/
│   ├── 01_eda.ipynb      # Análisis Exploratorio de Datos
│   ├── 02_feature_eng.ipynb # Ingeniería de variables
│   └── 03_modeling.ipynb # Entrenamiento y evaluación de modelos
├── src/
│   ├── utils.py          # Funciones auxiliares y scripts reutilizables
│   └── predict.py        # Pipeline de predicción
├── reports/
│   └── figures/          # Gráficos y visualizaciones exportadas
├── .gitignore            # Archivos ignorados por Git
├── README.md             # Documentación del proyecto
└── requirements.txt      # Dependencias y librerías necesarias


## Data Set 
03. Apoyo prueba - ventas_simuladas.xlsx
