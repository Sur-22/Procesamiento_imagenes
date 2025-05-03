#  Transformaciones de Recorte, Extracción y Perspectiva en Imágenes

Este repositorio contiene un cuaderno de Colab que demuestra cómo realizar operaciones de recorte, extracción y cambio de perspectiva en imágenes utilizando OpenCV.

##   Contenido del Cuaderno

El cuaderno `009 - Recorte,_extracción_y_cambio_de_perspectiva.ipynb` guía a través de los siguientes pasos:

1.  **Importación de librerías**:  Se importan las bibliotecas necesarias: OpenCV (`cv2`), NumPy (`numpy`) y Matplotlib (`matplotlib.pyplot`)[cite: 1].
   
2.  **Montaje de Google Drive**:  Se monta Google Drive para acceder a las imágenes (esto es específico de Colab)[cite: 17, 18, 19, 2].
   
3.  **Recorte, extracción y cambio de perspectiva**:
   
    * Se identifican las cuatro esquinas de una carta en una imagen[cite: 20, 21, 3].
    * Se calcula una matriz de transformación de perspectiva utilizando `cv2.getPerspectiveTransform`, especificando los puntos de origen y destino[cite: 22, 4].
   
4.  **Aplicación de la transformación**:
   
    * Se utiliza `cv2.warpPerspective` para aplicar la transformación y obtener una vista frontal de la carta[cite: 26, 27, 28].
   
5.  **Visualización de resultados**:
   
    * Se muestran la imagen original y la imagen transformada utilizando Matplotlib[cite: 23, 24, 25, 5].

##   Uso del Cuaderno

1.  **Abrir el cuaderno en Colab**:  Abre el cuaderno `009 - Recorte,_extracción_y_cambio_de_perspectiva.ipynb` en Google Colab.
   
2.  **Ejecutar las celdas**:  Ejecuta las celdas del cuaderno en orden secuencial.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.
   
3.  **Experimentar**:  Puedes modificar los puntos de origen y destino para transformar diferentes objetos en la imagen o cambiar la perspectiva de la transformación.

##   Bibliotecas Utilizadas

* **OpenCV (cv2)**:  Biblioteca para procesamiento de imágenes.
   
* **NumPy**:  Biblioteca para operaciones numéricas.
   
* **Matplotlib**:  Biblioteca para crear visualizaciones.