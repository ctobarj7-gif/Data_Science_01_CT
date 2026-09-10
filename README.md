# 📊 Ejemplo de un Modelo Predictivo utilizando Apache Spark con MLlib

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License:](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.io/badge/Status-Completed-success)]()

> **Resumen:** El siguiente ejemplo utiliza un Data Set ficticio para diseñar un modelo supervisado de clasificación con MLlib. Los datos pasan por los procesos de Limpieza, entrenamiento y evaluación del Modelo, y por ultimo obtener conclusiones técnicas

---

## 📌 Tabla de Contenidos
- [Descripción del Proyecto](#-descripción-del-proyecto)
- [Estructura del Repositorio](#-estructura-del-repositorio)
- [Dataset]#-03. Apoyo prueba - ventas_simuladas.xlsx
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
* **Objetivo 1:** [Ej. Realizar un análisis exploratorio de datos (EDA) para identificar tendencias clave.]
* **Objetivo 2:** [Ej. Entrenar y comparar 3 modelos de clasificación (Random Forest, XGBoost, Regresión Logística).]
* **Objetivo 3:** [Ej. Desplegar un dashboard interactivo / API para consulta de predicciones.]

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
