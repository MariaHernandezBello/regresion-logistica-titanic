# Regresión Logística - Titanic

## Descripción

Este proyecto implementa un modelo de Regresión Logística para predecir la supervivencia de pasajeros del Titanic.

## Objetivo

Predecir si un pasajero sobrevivió o no utilizando variables relacionadas con sus características y condiciones de viaje.

## Variables utilizadas

- `pclass`: clase del pasajero.
- `age`: edad.
- `sibsp`: número de hermanos o cónyuges a bordo.
- `parch`: número de padres o hijos a bordo.
- `fare`: tarifa pagada.

### Variable objetivo

- `survived`
  - `0` = No sobrevivió
  - `1` = Sobrevivió

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Metodología

Los datos se dividieron en 75 % para entrenamiento y 25 % para prueba, utilizando `random_state=42` y `stratify=y`.

Se entrenó un modelo de Regresión Logística y se generaron tanto predicciones de clase como probabilidades de supervivencia.

## Evaluación

El modelo fue evaluado mediante:

- Accuracy
- Matriz de confusión
- Precision
- Recall
- F1-score

También se modificó el umbral de decisión de 0,50 a 0,60 para observar cómo cambiaban las predicciones.

## Resultado

El modelo obtuvo un Accuracy de 70,39 % en el conjunto de prueba.

## Archivo principal

El desarrollo completo del ejercicio se encuentra en:

`Regresion_Logistica_Titanic.ipynb`
