#  Transformaciones de Recorte, Extracción y Perspectiva en Imágenes

Este repositorio contiene un cuaderno de Colab que demuestra cómo realizar operaciones de recorte, extracción y cambio de perspectiva en imágenes utilizando OpenCV.

##   Contenido del Cuaderno

El cuaderno **[Recorte, extracción y cambio de perpectiva](009%20-%20Recorte_extracción_y_cambio_de_perspectiva.ipynb)** guía a través de los siguientes pasos:

1.  **Importación de librerías**:  Se importan las bibliotecas necesarias: OpenCV (`cv2`), NumPy (`numpy`) y Matplotlib (`matplotlib.pyplot`).
   
2.  **Montaje de Google Drive**:  Se monta Google Drive para acceder a las imágenes (esto es específico de Colab).
   
3.  **Recorte, extracción y cambio de perspectiva**:
   
    * Se identifican las cuatro esquinas de una carta en una imagen.
    * Se calcula una matriz de transformación de perspectiva utilizando `cv2.getPerspectiveTransform`, especificando los puntos de origen y destino.
   
4.  **Aplicación de la transformación**:
   
    * Se utiliza `cv2.warpPerspective` para aplicar la transformación y obtener una vista frontal de la carta.
   
5.  **Visualización de resultados**:
   
    * Se muestran la imagen original y la imagen transformada utilizando Matplotlib.

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