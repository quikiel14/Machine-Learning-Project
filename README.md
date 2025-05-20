# 💧 Machine Learning Project – Water Quality in England

Este proyecto explora la **predicción y análisis de la calidad del agua** en Inglaterra utilizando técnicas de **Machine Learning**. Aunque se disponía de datos de varios países (Canadá, China, Irlanda, USA), **el análisis final se centró exclusivamente en Inglaterra**, por consistencia y enfoque. Fuente: "A Comprehensive Surface Water Quality Monitoring Dataset (1940-2023): 2.82Million Record Resource for Empirical and ML-Based Research"

## 📁 Estructura del Repositorio

- `water investigation England UTILIZADO.ipynb`: 🧠 Notebook principal del análisis. Incluye:
  - Limpieza y preprocesamiento de datos
  - Análisis exploratorio (EDA)
  - Modelado supervisado para clasificar la calidad del agua
  - Predicción de puntuación de calidad (WQI)
  - Análisis de series temporales (forecasting)
  - Visualizaciones interactivas

- Otros notebooks (`No utilizado`) corresponden a análisis preliminares de otros países y no se usaron en la versión final.

## 📊 Dataset

El conjunto de datos utilizado incluye **muestras de calidad del agua de Inglaterra**, con características físico-químicas como pH, oxígeno disuelto, sólidos disueltos, conductividad, etc.  
La variable objetivo fue el **Índice de Calidad del Agua (WQI)**, tanto como clase como valor numérico.

## 🔍 Técnicas de ML Aplicadas

- Clasificación:
  - Random Forest, XGBoost, Gradient Boosting
- Regresión:
  - Linear Regression, Gradient Boosting Regressor
- Forecasting:
  - SARIMA (Análisis de series temporales para WQI)

## 🧪 Librerías Usadas

- `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `scikit-learn`, `xgboost`
- `statsmodels` (para SARIMA)
- `datetime`

## 📌 Objetivos del Proyecto

1. Determinar la calidad del agua a partir de características físico-químicas.
2. Predecir la puntuación WQI (Water Quality Index).
3. Explorar tendencias temporales y prever la evolución futura de la calidad del agua.
4. Aplicar distintos modelos de Machine Learning y comparar su rendimiento.

## 📈 Resultados

- Modelos de clasificación alcanzaron **alto recall** al predecir clases de WQI.
- Modelos de regresión lograron un **bajo MAE**, indicando predicciones fiables del valor de WQI.
- El modelo ARIMA capturó adecuadamente la tendencia y estacionalidad en series temporales del WQI.

## 🔚 Conclusión

Este proyecto muestra cómo aplicar técnicas de ciencia de datos y aprendizaje automático para abordar problemas reales de **geología ambiental y calidad del agua**. El enfoque práctico, basado en Inglaterra, permite obtener insights valiosos para futuras políticas o sistemas de monitoreo.

## 📌 Autor

- **Usuario de GitHub:** [quikiel14](https://github.com/quikiel14)
- Proyecto desarrollado como parte de un trabajo de aprendizaje aplicado.

