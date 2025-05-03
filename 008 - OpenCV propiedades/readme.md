# Propiedades de Imágenes en OpenCV

Este repositorio contiene un cuaderno de Colab que explora las propiedades fundamentales de las imágenes digitales y cómo acceder a ellas utilizando la biblioteca OpenCV.

## Contenido del Cuaderno

El cuaderno `008 - Open_CV_Propiedades.ipynb` cubre los siguientes temas:

1.  **¿Qué es una imagen digital?**:
    * Explica cómo las imágenes digitales están compuestas por píxeles.
    * Describe cómo cada píxel representa un color y cómo la combinación de estos forma la imagen completa.
    * Introduce la idea de representar una imagen como una matriz de números.

2.  **Carga y Visualización de Imágenes**:
    * Utiliza OpenCV (`cv2.imread`) para cargar una imagen.
    * Utiliza Matplotlib (`matplotlib.pyplot.imshow`) para mostrar la imagen cargada.

3.  **Acceso a Propiedades de la Imagen**:
    * Muestra cómo acceder a diferentes propiedades de una imagen, incluyendo:
        * `shape`:  Dimensiones de la imagen (alto, ancho y número de canales de color).
        * `size`:   Número total de píxeles en la imagen.
        * `dtype`:  Tipo de datos de los píxeles.

4.  **Acceso a Píxeles**:
    * Explica cómo acceder a píxeles individuales utilizando la notación de indexación de NumPy.
    * Demuestra cómo obtener el valor de un píxel en una imagen en escala de grises y en una imagen a color (BGR).
    * Muestra cómo modificar el valor de un píxel.

## Uso del Cuaderno

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace `008 - Open_CV_Propiedades.ipynb` para abrirlo en Google Colab.
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.
3.  **Experimentar**:  Puedes experimentar cargando diferentes imágenes y modificando el código para acceder y manipular diferentes píxeles o propiedades de la imagen.

## Bibliotecas Utilizadas

* **OpenCV (cv2)**: Biblioteca para procesamiento de imágenes.
* **NumPy**: Biblioteca para operaciones numéricas.
* **Matplotlib**: Biblioteca para crear visualizaciones.