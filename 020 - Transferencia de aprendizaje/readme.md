# Transferencia de Aprendizaje

Este cuaderno de Colab explora la técnica de **[Transferencia de Aprendizaje](020%20-%20Transferencia%20de%20Aprendizaje.ipynb)** aplicada a problemas de clasificación de imágenes. Se aprovechan modelos preentrenados en grandes datasets (como ImageNet) para mejorar el rendimiento en conjuntos de datos más pequeños y específicos.

## Introducción Teórica

La transferencia de aprendizaje consiste en reutilizar un modelo previamente entrenado en una tarea amplia (por ejemplo, clasificación general de imágenes) como punto de partida para una tarea diferente pero relacionada. Esto permite:

* Reducir el tiempo de entrenamiento.
* Mejorar la precisión con menos datos.
* Evitar el sobreajuste.

En este cuaderno se utiliza un modelo preentrenado de **Keras / TensorFlow** como extractor de características (feature extractor) y se entrena una capa superior (clasificador denso) adaptada al nuevo conjunto de datos.

## Uso del Cuaderno

1. **Abrir el cuaderno en Colab**: Haz clic en el enlace `020 - Transferencia de Aprendizaje.ipynb` para abrirlo en Google Colab.

2. **Ejecutar las celdas**: 
   * Ejecuta las celdas del cuaderno en orden.
   * Usa `Shift + Enter` para ejecutar una por una o el menú `Entorno de ejecución > Ejecutar todo`.

3. **Entrenamiento del modelo**:
   * El cuaderno descarga y prepara automáticamente un conjunto de datos de imágenes.
   * Luego carga un modelo preentrenado (`MobileNetV2`, `VGG16`, etc.), congela sus capas y entrena una nueva red de salida para una tarea específica.

4. **Evaluación y pruebas**:
   * Se muestran gráficos de precisión y pérdida del entrenamiento.
   * Se visualizan predicciones realizadas por el modelo final.

## Bibliotecas Utilizadas

* **TensorFlow / Keras**: Framework principal para deep learning y modelos preentrenados.
* **NumPy**: Para operaciones numéricas.
* **Matplotlib**: Para visualización de resultados y métricas.
* **PIL**: Para manejo de imágenes.
