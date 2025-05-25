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

## Visualización y Modelado con Redes Convolucionales (CNN)

### **[019 - 1 - Filtros y Activaciones](019%20-%201%20-%20Filtros%20activaciones.ipynb)**

Este cuaderno muestra cómo inspeccionar los **filtros** y **activaciones** intermedias de una red convolucional entrenada. Permite entender qué patrones está aprendiendo la red y cómo responde a diferentes entradas.

#### Contenido del Cuaderno

* Carga de un modelo CNN previamente entrenado
* Visualización de filtros de capas convolucionales
* Extracción y visualización de **activaciones** para imágenes específicas
* Exploración de cómo diferentes capas "ven" la entrada

#### Uso

1. Abrí el cuaderno en Google Colab haciendo clic en el enlace.
2. Ejecutá las celdas paso a paso (`Shift + Enter`) o todo el cuaderno (`Entorno de ejecución > Ejecutar todo`).
3. Se recomienda tener un modelo previamente entrenado para cargar sus pesos y analizar su comportamiento.

---

### **[019 - 2 - CNN Básica con Keras y TensorFlow](019%20-%202%20-%20CNN%20b%C3%A1sica%20con%20Keras%20y%20TensorFlow.ipynb)**

Este cuaderno implementa una red neuronal convolucional **básica** para la clasificación de letras manuscritas con el dataset EMNIST/Letters. Es una introducción clara al uso de CNNs con Keras.

#### Contenido del Cuaderno

* Carga del conjunto EMNIST/Letters desde `tensorflow_datasets`
* Preprocesamiento de datos (normalización y batching)
* Construcción de una CNN sencilla
* Entrenamiento y evaluación
* Visualización de predicciones

#### Arquitectura del Modelo

- 1 capa convolucional + MaxPooling
- 1 capa densa intermedia
- Capa de salida Softmax con 26 clases

#### Uso

1. Abrí el cuaderno desde Colab con el enlace.
2. Ejecutá todo el notebook.
3. Revisá los gráficos y métricas para evaluar el desempeño del modelo.

---

### **[019 - 3 - CNN Full](019%20-%203%20-%20CNN%20Full.ipynb)**

Este cuaderno extiende el modelo básico a una **CNN más profunda** y robusta, con múltiples capas convolucionales. Ideal para observar mejoras de desempeño al usar arquitecturas más complejas.

#### Contenido del Cuaderno

* Uso del dataset EMNIST/Letters
* Red convolucional profunda:
  - Múltiples bloques Conv2D + MaxPooling
  - Dropout para regularización
  - Capa final densa con Softmax
* Entrenamiento en varias épocas
* Evaluación con métricas y gráficos
* Visualización de predicciones

#### Uso

1. Abrí el cuaderno desde el enlace en Colab.
2. Ejecutá todas las celdas.
3. Analizá el impacto de una arquitectura más compleja en los resultados.
