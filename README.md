# Desapariciones en el Área Metropolitana de Guadalajara, 2020–2025

Seminario de Proyecto II, Maestría en Ciencia de Datos e Información (INFOTEC).
Jorge Flores Uribe

**Título preliminar:** Relación entre factores socioeconómicos y de seguridad en la tasa de desapariciones del Área Metropolitana de Guadalajara, 2020–2025.

## Notebooks

- `notebooks/01_eda.ipynb`: análisis exploratorio del panel municipio × trimestre (216 observaciones).
- `notebooks/02_analisis_preliminar.ipynb`: cobertura CNB/REPD, modelos de panel con efectos fijos y comparación con Random Forest y XGBoost.

Ambos leen la base SQLite del proyecto (`tesis_panel.db`), construida a partir de fuentes públicas: el Registro Estatal de Personas Desaparecidas de Jalisco, el RNPDNO, la ENOE y la ENSU del INEGI, y el Censo 2020. La base no se incluye porque contiene registros a nivel caso.

## Requisitos

Python 3.12 con `pandas`, `numpy`, `statsmodels`, `scikit-learn`, `xgboost`, `matplotlib` y `seaborn`.
