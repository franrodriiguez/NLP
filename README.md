# Práctica Final NLP

## Descripción

Esta práctica final desarrolla un proyecto completo de análisis de sentimiento sobre reviews de productos de Amazon, siguiendo las distintas etapas vistas durante el módulo de Procesamiento del Lenguaje Natural (NLP).

El objetivo principal es construir un sistema capaz de clasificar automáticamente las opiniones de los usuarios en positivas o negativas utilizando técnicas clásicas de NLP y Machine Learning.

---

## Dataset utilizado

Se ha utilizado el dataset **Sports and Outdoors** del conjunto de reviews de Amazon proporcionado por UCSD.

**Fuente:**  
http://jmcauley.ucsd.edu/data/amazon/

Para facilitar el procesamiento y entrenamiento de los modelos, se ha trabajado sobre un subconjunto balanceado de reviews positivas y negativas.

---

## Estructura de la entrega

### 1. Descarga y exploración del corpus

**Notebook:**

`1. Descarga y exploración del corpus.ipynb`

Contiene:

- Carga y preparación inicial del dataset.
- Análisis exploratorio de los datos.
- Cardinalidad del vocabulario.
- Distribución de reviews por estrellas.
- Balanceo de clases.
- N-grams más frecuentes.
- Nubes de palabras.
- Conclusiones de la exploración.

---

### 2. Etapa de preprocesado de texto

**Notebook:**

`2. Etapa de preprocesado de texto.ipynb`

Contiene:

- Limpieza de texto.
- Normalización.
- Tokenización.
- Eliminación de stopwords.
- Creación de una función reutilizable de preprocesado.
- Generación de la versión procesada de las reviews para el entrenamiento posterior.

---

### 3. Entrenamiento, evaluación y conclusiones

**Notebook:**

`3. Etapa de entrenamiento y testeo de un modelo de análisis de sentimiento.ipynb`

Este notebook incluye tanto el **Ejercicio 3** como el **Ejercicio 4** del enunciado.

#### Ejercicio 3 – Entrenamiento y testeo

- División Train/Test.
- Vectorización mediante TF-IDF.
- Entrenamiento de distintos modelos de clasificación.
- Comparación de resultados.
- Selección del mejor modelo.

#### Ejercicio 4 – Reporte de métricas y conclusiones

- Matriz de confusión.
- Accuracy.
- Precision.
- Recall.
- F1-Score.
- Classification Report.
- Análisis de resultados.
- Conclusiones finales.

> **Nota:** El ejercicio 4 no se entrega en un notebook independiente, sino que se encuentra integrado dentro del notebook 3, ya que las métricas y conclusiones se generan directamente a partir del modelo seleccionado durante la fase de entrenamiento.

---

## Librerías principales utilizadas

- Pandas
- NumPy
- Matplotlib
- NLTK
- WordCloud
- Scikit-learn
- Gensim

---

## Flujo de trabajo seguido

1. Descarga y exploración del corpus.
2. Preprocesado y limpieza de texto.
3. Representación vectorial mediante TF-IDF.
4. Entrenamiento de modelos supervisados.
5. Comparación de resultados.
6. Evaluación mediante métricas de clasificación.
7. Obtención de conclusiones finales.

---

## Observaciones

Todos los notebooks contienen el código necesario para reproducir los resultados obtenidos y los comentarios correspondientes para justificar las decisiones tomadas durante el desarrollo de la práctica.
