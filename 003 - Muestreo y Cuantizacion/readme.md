# Muestreo y Cuantización en Procesamiento de Imágenes

Este repositorio contiene un cuaderno de Colab que demuestra los conceptos fundamentales de muestreo y cuantización en el procesamiento digital de imágenes.

## Contenido del Cuaderno

El cuaderno `Muestreo_y_Cuantización.ipynb` explora las dos operaciones esenciales en el procesamiento digital de imágenes:

* **Muestreo espacial**:  Convierte una imagen continua en una matriz discreta de píxeles. [cite: 37, 38]
   
* **Cuantización**: Asigna valores discretos a la intensidad de cada píxel. [cite: 38]

El cuaderno incluye los siguientes pasos:

1.  **Preparación del entorno**: Importa las bibliotecas necesarias:
    * `NumPy`: Para trabajar con matrices que representan las imágenes. [cite: 39, 40]
    * `OpenCV (cv2)`:  Biblioteca para procesamiento de imágenes. [cite: 39, 40]
    * `Matplotlib`: Para visualizar imágenes y gráficos. [cite: 39, 40]
       
2.  **Descarga de la imagen de ejemplo**:  Utiliza `wget` para descargar una imagen de ejemplo (`gatito.jpg`). [cite: 41]
   
3.  **Visualización y análisis de la imagen original**:
    * Carga la imagen usando `imread` de OpenCV. [cite: 44, 45]
    * Muestra información básica de la imagen (tamaño, valor máximo y mínimo de los píxeles) con la función `howis`. [cite: 42, 43, 46, 47]
    * Visualiza la imagen original en escala de grises usando `matplotlib.pyplot`. [cite: 46, 47]

## Instrucciones de Uso

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace del cuaderno `Muestreo_y_Cuantización.ipynb` para abrirlo en Google Colab.
2.  **Ejecutar las celdas**:  Ejecuta las celdas del cuaderno en orden. Puedes ejecutar cada celda individualmente presionando `Shift + Enter` o ejecutar todas las celdas en el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.
3.  **Interactuar con el cuaderno**:  El cuaderno te guiará a través de los conceptos de muestreo y cuantización, mostrando el código y los resultados de cada paso.
4.  **Experimentar**:  Si lo deseas, puedes modificar el código para experimentar con diferentes imágenes o parámetros y observar los efectos en el procesamiento de la imagen.

¡Espero que este cuaderno te sea de utilidad para comprender los fundamentos del procesamiento digital de imágenes!
