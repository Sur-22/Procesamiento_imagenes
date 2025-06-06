# Clasificación de Imágenes con ResNet18

Este cuaderno de Colab implementa un modelo de **[ResNet18](022%20-%20ResNet18.ipynb)** preentrenado para realizar tareas de clasificación de imágenes utilizando la técnica de **transferencia de aprendizaje** con PyTorch.

## Introducción Teórica

**ResNet (Residual Network)** es una familia de redes neuronales profundas propuesta por Microsoft que introduce conexiones residuales o atajos para facilitar el entrenamiento de redes muy profundas. En particular, **ResNet18** es una versión liviana con 18 capas, ideal para tareas de clasificación con conjuntos de datos medianos.

Este cuaderno muestra cómo:

* Cargar el modelo ResNet18 preentrenado en ImageNet.
* Modificar su capa de salida para ajustarse a una nueva tarea de clasificación.
* Entrenar el nuevo modelo usando PyTorch.
* Evaluar el rendimiento y visualizar resultados.

## Uso del Cuaderno

1. **Abrir el cuaderno en Colab**: Haz clic en el enlace `022 - ResNet18.ipynb` para abrirlo en Google Colab.

2. **Ejecutar las celdas**:
   * Usa `Shift + Enter` para avanzar paso a paso o `Entorno de ejecución > Ejecutar todo`.

3. **Flujo de trabajo**:
   * Instalación y configuración de PyTorch.
   * Carga y transformación de un conjunto de datos (por ejemplo, `flowers`).
   * Adaptación de la arquitectura ResNet18.
   * Entrenamiento del modelo final.
   * Evaluación y visualización de imágenes clasificadas.

## Bibliotecas Utilizadas

* **PyTorch**: Framework principal para deep learning.
* **torchvision**: Para modelos preentrenados y utilidades de datos.
* **Matplotlib**: Para visualizar imágenes y métricas.
* **NumPy**: Para operaciones numéricas.
* **PIL**: Para manejo de imágenes.