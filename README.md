# Actividad de Minería de Datos

Este repositorio contiene el desarrollo de una actividad de la asignatura de Minería de Datos, donde se aplican dos modelos vistos en clases:

1. **Market Basket Analysis**
2. **Regresión Lineal Múltiple**

## Descripción del proyecto

El objetivo de esta actividad es aplicar modelos de minería de datos sobre datasets reales o adaptados, siguiendo una estructura de análisis basada en la metodología CRISP-DM.

En la primera parte se desarrolla un modelo de **Market Basket Analysis** utilizando el algoritmo **Apriori**, con el propósito de encontrar asociaciones entre productos comprados dentro de una misma orden.

En la segunda parte se aplica un modelo de **regresión lineal múltiple**, con el objetivo de predecir una variable numérica a partir de distintas variables explicativas.

## Modelos utilizados

### 1. Market Basket Analysis

Para esta parte se utiliza un dataset de ventas retail.  
El análisis permite identificar productos que suelen aparecer juntos dentro de una misma compra.

El modelo utiliza:

- Matriz transaccional
- Algoritmo Apriori
- Reglas de asociación
- Métricas como `support`, `confidence`, `lift`, `leverage` y `conviction`

### 2. Regresión Lineal Múltiple

Para esta parte se utiliza un dataset relacionado con salarios en el ámbito laboral.  
El objetivo es predecir el salario de una persona considerando variables como experiencia, habilidades, certificaciones, nivel educacional, industria, ubicación, modalidad de trabajo y tamaño de empresa.

El modelo se evalúa mediante:

- MAE
- MSE
- RMSE
- R²

## Archivos del repositorio

- `Modelo_Canasta_EstephanyC.ipynb`: notebook con el desarrollo del modelo Market Basket Analysis.
- `Prueba.ipynb`: notebook base utilizado para la parte de regresión lineal.
- `Retail_pos_basket_data.csv.csv`: dataset utilizado para el análisis de canasta de mercado.
- Archivos adicionales del dataset de salarios, si corresponde.

## Librerías utilizadas

Las principales librerías utilizadas son:

```python
pandas
matplotlib
mlxtend
scikit-learn
