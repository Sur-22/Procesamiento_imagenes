#  Análisis Comparativo de Segmentación de Imágenes

Este repositorio contiene dos cuadernos de Colab que demuestran un ejercicio de procesamiento de imágenes, con un enfoque en la segmentación.  Los cuadernos utilizan el mismo código, pero se aplican a imágenes diferentes, lo que permite observar el impacto de la calidad de la imagen en los resultados del procesamiento.

## Contenido de los Cuadernos

1.  **[001 - Laboratorio integrador 2](001%20-%20LAB_Integrador_2.ipynb)**

    * Este cuaderno aplica un conjunto de procedimientos de procesamiento de imágenes a una imagen de alta calidad. 
    * El objetivo es leer la imagen, aplicar mejoras y segmentar objetos, mostrando los resultados visualmente. 
    * Debido a la buena calidad de la imagen de entrada, las diferencias entre la imagen original y la procesada pueden ser sutiles.

2.  **[002 - Laboratorio integrador 2B](002%20-%20LAB_Integrador_2.ipynb)**

    * Este cuaderno contiene el mismo código de procesamiento de imágenes que el anterior.
    * Sin embargo, se aplica a una imagen de menor calidad o con características que hacen que los efectos del procesamiento sean más notorios. 
    * Esto permite una mejor visualización de las diferencias introducidas por las técnicas de procesamiento de imágenes.

## Objetivo

Ambos cuadernos tienen el mismo objetivo de demostrar los pasos básicos del procesamiento de imágenes:

* Leer una imagen. 
* Aplicar mejoras. 
* Segmentar objetos. 
* Mostrar los resultados. 

## Preparación

* **Entorno**: Ambos cuadernos están diseñados para ser ejecutados en Google Colab. 
* **Bibliotecas**:  Se utilizan las bibliotecas OpenCV (`cv2`), Matplotlib (`matplotlib.pyplot`) y NumPy (`numpy`).

## Instrucciones de Uso

1.  **Abrir en Colab**:  Haz clic en el enlace del cuaderno (`001...` o `002...`) para abrirlo en Google Colab.
2.  **Ejecutar celdas**: Ejecuta las celdas del cuaderno en orden.  Usa `Shift + Enter` para ejecutar individualmente, o "Entorno de ejecución" -> "Ejecutar todo" para ejecutar el cuaderno completo.
3.  **Observar los resultados**: Compara los resultados de ambos cuadernos para apreciar el impacto de la calidad de la imagen en el procesamiento.