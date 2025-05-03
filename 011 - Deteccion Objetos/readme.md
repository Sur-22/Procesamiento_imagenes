# Detección de Objetos con OpenCV

Este repositorio contiene un cuaderno de Colab que introduce los conceptos básicos de la detección de objetos utilizando la biblioteca OpenCV. El cuaderno se centra principalmente en la detección de caras usando el algoritmo de Viola & Jones.

## Contenido del Cuaderno

El cuaderno `011 - Deteccion_Objetos.ipynb` cubre los siguientes temas:

1.  **Detección de Caras (Face Detection)**

    * Explica que la detección de caras es un caso específico de la detección de objetos[cite: 2].
    * Introduce el algoritmo de Viola & Jones, que es eficiente y rápido para la detección de caras[cite: 2, 3].
    * Describe el concepto de la ventana deslizante para entender cómo funciona la técnica de detección de objetos[cite: 3, 4, 5, 6].
    * Explica las características de Haar, que son esenciales para el algoritmo de Viola & Jones[cite: 7, 8, 9].
    * Menciona el uso de una "cascada" de clasificadores (AdaBoost) para mejorar la eficiencia de la detección[cite: 31, 32, 33, 34, 10, 11, 12].

2.  **Video Explicativo**

    * Incluye un video que demuestra cómo el algoritmo descarta los recortes sin rostro y se enfoca en las regiones con rostros[cite: 34].

## Uso del Cuaderno

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace `011 - Deteccion_Objetos.ipynb` para abrirlo en Google Colab.
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.

## Bibliotecas Utilizadas

* **OpenCV (cv2)**: Biblioteca para procesamiento de imágenes.
* **NumPy**: Biblioteca para operaciones numéricas.
* **Matplotlib**: Biblioteca para crear visualizaciones.
* **IPython.display**: Para mostrar el video explicativo.