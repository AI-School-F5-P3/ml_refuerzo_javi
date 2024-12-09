# Proyecto de Clasificación de Clientes de Telecomunicaciones

## 📋 Descripción
Proyecto de machine learning que desarrolla un modelo de clasificación multiclase para predecir la categoría de servicio de clientes de una empresa de telecomunicaciones basándose en sus características demográficas. El modelo permite segmentar clientes en cuatro categorías de servicio diferentes, facilitando la personalización de ofertas y mejorando las estrategias de marketing.

## 🎯 Objetivos
- Desarrollar un modelo de clasificación que prediga el grupo al que pertenece un cliente
- Realizar un análisis exploratorio de datos (EDA) completo
- Implementar una solución funcional para la predicción de categorías
- Evaluar el rendimiento del modelo mediante múltiples métricas

## 📊 Dataset
El dataset (`teleCust1000t.csv`) contiene información sobre 1000 clientes con las siguientes características:
- region: Región del cliente
- tenure: Tiempo como cliente
- age: Edad del cliente
- marital: Estado civil
- address: Años en la dirección actual
- income: Ingresos
- ed: Nivel educativo
- employ: Años de empleo
- retire: Estado de jubilación
- gender: Género
- reside: Número de residentes en el hogar
- custcat: Categoría del cliente (variable objetivo)
  - 1: Basic Service
  - 2: E-Service
  - 3: Plus Service
  - 4: Total Service

## 🛠️ Tecnologías Utilizadas
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Joblib
- Torch
- Optuna

