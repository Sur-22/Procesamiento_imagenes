#  Análisis Comparativo de Segmentación de Imágenes

Este repositorio contiene dos cuadernos de Colab que demuestran un ejercicio de procesamiento de imágenes, con un enfoque en la segmentación.  Los cuadernos utilizan el mismo código, pero se aplican a imágenes diferentes, lo que permite observar el impacto de la calidad de la imagen en los resultados del procesamiento.

## Contenido de los Cuadernos

1.  **[001 - LAB\_Integrador\_2](001%20-%20LAB_Integrador_2.ipynb)**

    * Este cuaderno aplica un conjunto de procedimientos de procesamiento de imágenes a una imagen de alta calidad. [cite: 1, 2, 3, 4, 5, 6, 7]
    * El objetivo es leer la imagen, aplicar mejoras y segmentar objetos, mostrando los resultados visualmente. [cite: 1]
    * Debido a la buena calidad de la imagen de entrada, las diferencias entre la imagen original y la procesada pueden ser sutiles.

2.  **[002 - LAB\_Integrador\_2](002%20-%20LAB_Integrador_2.ipynb)**

    * Este cuaderno contiene el mismo código de procesamiento de imágenes que el anterior. [cite: 1563, 1564, 1565, 1566, 1567, 1568, 1569, 1570, 1571, 1572, 1573, 1574, 1575, 1576, 1577]
    * Sin embargo, se aplica a una imagen de menor calidad o con características que hacen que los efectos del procesamiento sean más notorios. [cite: 1563, 1564, 1565, 1566, 1567, 1568, 1569, 1570, 1571, 1572, 1573, 1574, 1575, 1576, 1577]
    * Esto permite una mejor visualización de las diferencias introducidas por las técnicas de procesamiento de imágenes.

## Objetivo

Ambos cuadernos tienen el mismo objetivo de demostrar los pasos básicos del procesamiento de imágenes:

* Leer una imagen. [cite: 411, 1569]
* Aplicar mejoras. [cite: 1, 1564]
* Segmentar objetos. [cite: 1, 1564]
* Mostrar los resultados. [cite: 1, 1564]

## Preparación

* **Entorno**: Ambos cuadernos están diseñados para ser ejecutados en Google Colab. [cite: 1, 1564]
* **Bibliotecas**:  Se utilizan las bibliotecas OpenCV (`cv2`), Matplotlib (`matplotlib.pyplot`) y NumPy (`numpy`). [cite: 408, 1563, 1564, 1565, 1566, 1567, 1568, 1569, 1570]

## Instrucciones de Uso

1.  **Abrir en Colab**:  Haz clic en el enlace del cuaderno (`001...` o `002...`) para abrirlo en Google Colab.
2.  **Ejecutar celdas**: Ejecuta las celdas del cuaderno en orden.  Usa `Shift + Enter` para ejecutar individualmente, o "Entorno de ejecución" -> "Ejecutar todo" para ejecutar el cuaderno completo.
3.  **Observar los resultados**: Compara los resultados de ambos cuadernos para apreciar el impacto de la calidad de la imagen en el procesamiento.