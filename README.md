# Proyecto de Análisis de Sentimiento de Reseñas de Instrumentos Musicales

## Descripción General

Este proyecto tiene como objetivo el análisis de sentimiento en un conjunto de reseñas de productos musicales, con el fin de clasificar las opiniones de los usuarios en **positivas** o **negativas**. Para ello, se ha utilizado un enfoque de aprendizaje supervisado, aplicando modelos de clasificación como **SVM** (Máquinas de Soporte Vectorial) y **Random Forest**.

El análisis se realiza sobre un conjunto de datos de reseñas de instrumentos musicales obtenidas de Amazon. Las tareas del proyecto incluyen la **preprocesamiento de texto**, la **creación de modelos de clasificación** y la **evaluación** de su desempeño utilizando métricas como **precisión**, **recall**, **f1-score** y **accuracy**.

## Objetivos

1. **Preprocesamiento de Reseñas**: Eliminar URLs, números, caracteres especiales y convertir el texto a minúsculas.
2. **Entrenamiento de Modelos**: Entrenar dos modelos de clasificación (SVM y Random Forest) para predecir el sentimiento de las reseñas.
3. **Evaluación de Modelos**: Comparar los resultados obtenidos por ambos modelos y seleccionar el mejor en función de las métricas de evaluación.
4. **Visualización de Resultados**: Comparar gráficamente los resultados de ambos modelos en términos de sus métricas.

## Requisitos

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn (opcional)
- NLTK
- WordCloud
