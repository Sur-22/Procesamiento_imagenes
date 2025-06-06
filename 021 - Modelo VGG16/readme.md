# VGG16 como Modelo Preentrenado

Este cuaderno de Colab aplica el modelo **[VGG16 preentrenado](021%20-%20VGG16%20modelo%20preentrenado.ipynb)** para la clasificación de imágenes mediante la técnica de **transferencia de aprendizaje**. Se usa como extractor de características, y se entrena un clasificador personalizado sobre un conjunto de datos nuevo.

## Introducción Teórica

**VGG16** es una arquitectura de red neuronal convolucional profunda desarrollada por el Visual Geometry Group de la Universidad de Oxford. Fue entrenada originalmente en el dataset ImageNet, y es ampliamente utilizada por su capacidad de generalización y precisión.

Este cuaderno muestra cómo:

* Cargar el modelo VGG16 sin su capa de clasificación superior.
* Congelar sus pesos para que actúe como extractor de características.
* Añadir capas densas para clasificar nuevas imágenes.
* Entrenar y evaluar el modelo con un dataset personalizado.

## Uso del Cuaderno

1. **Abrir el cuaderno en Colab**: Haz clic en el enlace `021 - VGG16 modelo preentrenado.ipynb` para abrirlo en Google Colab.

2. **Ejecutar las celdas en orden**:
   * Usa `Shift + Enter` o selecciona `Entorno de ejecución > Ejecutar todo`.

3. **Flujo del trabajo en el cuaderno**:
   * Descarga y prepara un conjunto de datos (ej. flores).
   * Carga el modelo VGG16 preentrenado (sin top).
   * Añade nuevas capas densas para clasificación.
   * Entrena el nuevo modelo.
   * Evalúa su desempeño y visualiza predicciones.

## Bibliotecas Utilizadas

* **TensorFlow / Keras**: Para cargar el modelo VGG16, definir nuevas capas y entrenar la red.
* **NumPy**: Para manipulación de datos numéricos.
* **Matplotlib**: Para graficar métricas y resultados.
* **PIL / pathlib**: Para manejo de imágenes y archivos.