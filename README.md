# Predicción de la tasa de criminalidad en distritos del Perú

Proyecto académico desarrollado en la Pontificia Universidad Católica del Perú
para el curso de Inteligencia Artificial.

El proyecto compara modelos de Machine Learning para predecir la tasa de
criminalidad a nivel distrital utilizando información de inseguridad,
denuncias policiales y variables socioeconómicas.

## Datos

Se construyó un dataset consolidado de **6,231 registros** a partir de información
de ENAPRES, denuncias policiales y variables socioeconómicas a nivel distrital
para el periodo 2022–2024.

## Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Modelos evaluados

- Regresión Lineal
- K-Nearest Neighbors (KNN)
- XGBoost

XGBoost obtuvo el mejor desempeño entre los modelos evaluados,
alcanzando un R² aproximado de 0.719 en el conjunto de prueba.

## Fuentes de datos

El análisis integró información procedente de:
- ENAPRES - INEI
- Denuncias policiales SIDPOL
- Indicadores socioeconómicos a nivel distrital

## Mi contribución

- Búsqueda y análisis de trabajos relacionados.
- Redacción y citación de antecedentes académicos.
- Contribución en la fase de experimentación de los modelos.
- Redacción del análisis de implicaciones éticas del modelo.

## Autores

Proyecto grupal desarrollado por:
- Cristhian Reaño Ccoscco
- Cristhian Guevara De la Cruz
- Jean Paul Pasache Guzman 
- Sebastian Saco Alvarado

## Estructura del repositorio

```text
Prediccion-Criminalidad-Peru/
├── README.md
├── G6_TA_FINAL.ipynb
├── .gitignore
└── paper/
    └── Prediccion_Criminalidad_Peru.pdf
