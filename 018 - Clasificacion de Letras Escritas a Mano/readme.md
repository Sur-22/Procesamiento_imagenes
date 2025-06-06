# Clasificación de Letras Manuscritas con Redes Neuronales

El cuaderno **[018 - Clasificación](018%20-%20Clasificacion.ipynb)** explora la construcción, entrenamiento y evaluación de una red neuronal para reconocer letras escritas a mano. Utiliza el conjunto de datos EMNIST/Letters y TensorFlow para resolver un problema de clasificación multiclase.

## ¿Qué es la clasificación de letras manuscritas?

Es una tarea de reconocimiento de patrones en la que un modelo aprende a identificar letras del alfabeto a partir de imágenes en escala de grises. Estas imágenes provienen del dataset EMNIST, una extensión del conocido MNIST, pero enfocado en letras.

## ¿Para qué sirve?

Este tipo de sistema puede ser útil en aplicaciones como:

* Reconocimiento óptico de caracteres (OCR)
* Lectura automática de formularios
* Digitalización de textos manuscritos
* Interfaces accesibles basadas en escritura

## Uso del Cuaderno

1. **Abrir el cuaderno en Colab**: Haz clic en el enlace `018 - Clasificación.ipynb` para abrirlo en Google Colab.
2. **Ejecutar las celdas**: Ejecuta las celdas una a una (`Shift + Enter`) o todas desde `Entorno de ejecución > Ejecutar todo`.

## Contenido del Cuaderno

* **Carga del dataset EMNIST/Letters** usando `tensorflow_datasets`
* **Preprocesamiento**: Normalización de imágenes, ajuste de etiquetas y batching
* **Visualización de ejemplos**
* **Construcción del modelo**: Red neuronal tipo MLP con `Keras`
* **Entrenamiento** del modelo en múltiples épocas
* **Evaluación** del desempeño sobre el conjunto de prueba
* **Visualización de predicciones** correctas e incorrectas
* **Análisis de errores** con matriz de confusión
* **Gráficos de aprendizaje** (pérdida y precisión por época)

## Arquitectura del Modelo

- Entrada: Imagen de 28x28 píxeles (escalada a [0, 1])
- Capas ocultas: 2 capas densas de 64 neuronas con activación ReLU
- Salida: 26 neuronas (una por cada letra del alfabeto), con activación Softmax

## Resultados

- Precisión final del modelo: **~92% en el conjunto de prueba**
- Ejemplos visuales de predicciones correctas e incorrectas
- Curvas de aprendizaje bien formadas

## Bibliotecas Utilizadas

* **TensorFlow**: Entrenamiento de redes neuronales
* **TensorFlow Datasets**: Carga de EMNIST
* **Matplotlib / Seaborn**: Visualización de datos y métricas
* **NumPy**: Manipulación numérica
* **scikit-learn**: Matriz de confusión

---

> Este cuaderno está diseñado para quienes desean iniciarse en el uso de redes neuronales con datos reales. Incluye explicaciones detalladas y visualizaciones para facilitar la comprensión.

