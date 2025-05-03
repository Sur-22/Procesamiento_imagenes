#  Espacios de Color y Conversiones con OpenCV

Este repositorio contiene un cuaderno de Colab que introduce los espacios de color y demuestra cómo realizar conversiones entre ellos utilizando la biblioteca OpenCV.

##   Contenido del Cuaderno

El cuaderno `006_open_cv.ipynb` cubre los siguientes temas:

1.  **Introducción a los Espacios de Color**[cite: 18]:
    * **RGB**:  Describe cómo este espacio de color representa las imágenes como una combinación de rojo, verde y azul.
    * **Grayscale**: Explica cómo representa una imagen con un solo canal de intensidad, desde el negro hasta el blanco.
    * **HSV**:  Introduce este espacio de color, que utiliza el tono (Hue), la saturación (Saturation) y el valor (Value) para representar los colores.

2.  **Conversión de Espacios de Color con OpenCV**[cite: 20]:
    * Utiliza las funciones de OpenCV (`cv2.cvtColor`) para convertir imágenes entre diferentes espacios de color.
    * Muestra cómo cargar una imagen, convertirla de BGR (formato por defecto de OpenCV) a RGB (formato usado por Matplotlib para mostrar imágenes), y visualizarla.

##   Uso del Cuaderno

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace `006_open_cv.ipynb` para abrirlo en Google Colab.
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.
3.  **Montar Google Drive**: El cuaderno incluye una celda para montar tu Google Drive, lo que te permitirá acceder a tus propias imágenes[cite: 21]. Si deseas utilizar tus propias imágenes, asegúrate de ejecutar esta celda y modificar la ruta del archivo.
4.  **Experimentar**: Siéntete libre de modificar el código para probar con diferentes imágenes o explorar otras conversiones de espacios de color soportadas por OpenCV.

##   Bibliotecas Utilizadas

* **OpenCV (cv2)**:  Biblioteca para procesamiento de imágenes[cite: 19, 20].
* **NumPy**:  Biblioteca para operaciones numéricas[cite: 19].
* **Matplotlib**: Biblioteca para crear visualizaciones[cite: 19].