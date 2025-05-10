# Segmentación Simple de Imágenes por Color

Este repositorio contiene un cuaderno de Colab que demuestra un método básico de segmentación de imágenes basado en el color.

## Contenido del Cuaderno

El cuaderno **[Segmentacion Simple](Segmentacion_simple.ipynb)** presenta una introducción a la segmentación de imágenes mediante el uso de umbrales de color.  Los puntos clave que se exploran son:

1.  **Carga de Bibliotecas**:
    * Importa las bibliotecas necesarias: `NumPy` para manipulación de arrays, `OpenCV (cv2)` para leer y mostrar imágenes, `google.colab.patches` para mostrar imágenes en Colab, y `Matplotlib` para visualizaciones.

2.  **Función de Información de Imagen (`info_img`)**:
    * Define una función para mostrar información básica sobre una imagen, como su tamaño (shape), valor máximo de píxel y tipo de datos.

3.  **Carga de Imagen**:
    * Carga una imagen de ejemplo (`hojas.jpg`) utilizando `cv2.imread`.

4.  **Visualización de Imagen**:
    * Muestra la imagen original utilizando `cv2_imshow` (para Colab) y `matplotlib.pyplot.imshow`.

5.  **Segmentación por Umbral de Color**:
    * Implementa la segmentación por color creando máscaras binarias basadas en rangos de valores de color en los canales BGR.
    * Define límites de color inferior y superior para segmentar objetos de interés (en este caso, hojas verdes).
    * Utiliza `cv2.inRange` para crear las máscaras.
    * Aplica las máscaras a la imagen original mediante la operación bitwise AND (`cv2.bitwise_and`) para extraer los objetos segmentados.

6.  **Visualización de Resultados**:
    * Muestra las máscaras creadas y las imágenes segmentadas resultantes.

## Instrucciones de Uso

1.  **Abrir el cuaderno en Colab**:  Abre el cuaderno `Segmentacion_simple.ipynb` en Google Colab.
2.  **Ejecutar las celdas**:  Ejecuta las celdas del cuaderno en orden secuencial. Utiliza `Shift + Enter` para ejecutar celdas individuales o el menú `Entorno de ejecución -> Ejecutar todo` para ejecutar todo el cuaderno.
3.  **Entender el código**:  Lee las explicaciones en el cuaderno para comprender cómo se realiza la segmentación por color.
4.  **Experimentar**:
    * Puedes modificar los límites de color (`lower_bound`, `upper_bound`) para segmentar diferentes objetos en la imagen.
    * Puedes probar con otras imágenes reemplazando `hojas.jpg` con la ruta a tu propia imagen.
    * Puedes explorar diferentes espacios de color (como HSV) para realizar la segmentación.

Este cuaderno proporciona un punto de partida simple y efectivo para aprender los conceptos básicos de la segmentación de imágenes por color.