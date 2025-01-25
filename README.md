# Predicción de Abandono de Clientes en una Institución Bancaria: Modelo de Clasificación Supervisada con CRISP-DM 

Este proyecto tiene como objetivo construir un modelo de clasificación supervisada para predecir el abandono o la permanencia de los clientes en una institución bancaria. El modelo fue desarrollado utilizando el enfoque CRISP-DM (Cross-Industry Standard Process for Data Mining), que es un estándar en la minería de datos para estructurar proyectos de ciencia de datos.

## Metodología
El proceso de desarrollo del modelo se siguió de acuerdo con las etapas del CRISP-DM, que son las siguientes:

### 1. Comprensión del Negocio
El objetivo principal es predecir si un cliente abandonará o permanecerá con la institución bancaria, basado en diversas características relacionadas con su comportamiento y sus interacciones con la entidad. Esta predicción puede ser utilizada por la institución para implementar estrategias de retención, mejorar la satisfacción del cliente y optimizar los recursos.

### 2. Comprensión de los Datos
Se trabajó con un conjunto de datos que incluye información sobre los clientes de la institución bancaria, tales como:

Información demográfica del cliente (edad, género, ubicación).
Datos sobre las interacciones del cliente con la entidad (número de transacciones, uso de productos financieros, antigüedad en el banco).
Estado del cliente (si ha abandonado o no la institución).

### 3. Preparación de los Datos
La preparación de los datos consistió en:

Limpieza de datos: Manejo de valores faltantes, eliminación de registros duplicados.
Transformación de variables: Codificación de variables categóricas, normalización de variables numéricas.
Selección de características relevantes: Análisis exploratorio de datos (EDA) para identificar las características más significativas que impactan en la decisión de abandono o permanencia.

### 4. Modelado
Para el modelado, se aplicaron dos algoritmos de aprendizaje supervisado de clasificación:

- K-Nearest Neighbors (KNN): Un algoritmo basado en la distancia, que clasifica un punto en función de la mayoría de las clases de sus vecinos más cercanos.
- Árboles de Decisión: Este algoritmo crea un modelo que utiliza una estructura en forma de árbol para tomar decisiones basadas en las características del cliente. Los árboles de decisión son fáciles de interpretar y permiten visualizar cómo se toman las decisiones.
Cada modelo fue entrenado con el conjunto de datos de entrenamiento y evaluado utilizando el conjunto de datos de prueba. Para evaluar el rendimiento de los modelos se utilizaron métricas como la precisión, recall, F1-score, y AUC-ROC.

### 5. Evaluación
Se compararon los resultados de los distintos modelos para determinar cuál de ellos ofrece la mejor capacidad predictiva. Además, se realizó un análisis de validación cruzada para verificar la robustez del modelo.
