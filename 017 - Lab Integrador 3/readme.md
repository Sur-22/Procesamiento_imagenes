#   Análisis Facial con OpenCV y dlib

Este repositorio contiene dos cuadernos de Colab que exploran el análisis facial utilizando las bibliotecas OpenCV y dlib. Ambos cuadernos se centran en la detección de rostros y la identificación de puntos clave faciales, pero pueden diferir en su enfoque y funcionalidades.

##   Contenido de los Cuadernos

* **[017 - Laboratorio Integrador 3.ipynb](017%20-%20Lab%20Integrador%203.ipynb)**

    * Este cuaderno se enfoca en el **análisis de expresiones faciales** a través del procesamiento de imágenes.
    * Implementa metodologías para detectar puntos clave faciales (ojos, boca) y calcular métricas de expresión.
    * Calcula el Eye Aspect Ratio (EAR) y el Mouth Aspect Ratio (MAR) para analizar la apertura de los ojos y la boca.

* **[017B - Deteccion de rostro y puntos faciales.ipynb](017B%20-%20Deteccion%20de%20rostro%20y%20puntos%20faciales.ipynb)**

    * Este cuaderno se centra en la **detección de rostros y la identificación de puntos faciales** en videos.
    * Puede incluir la detección de rostros en tiempo real y el seguimiento de puntos faciales a lo largo de un video.
    * Utiliza dlib para la detección de puntos clave faciales, lo que permite una localización precisa de las características del rostro.

##   Diferencias Clave

Aunque ambos cuadernos trabajan con rostros, existen diferencias en su enfoque:

* **Objetivo Principal**: 017 se centra en el análisis de expresiones (EAR, MAR), mientras que 017B puede enfocarse más en la detección y el seguimiento de puntos faciales.
* **Tipo de Entrada**: 017 Puede funcionar principalmente con imágenes fijas, mientras que el 017B está diseñado para funcionar con transmisiones de video.
* **Funcionalidades**: 017B podría incluir funcionalidades adicionales como visualización de puntos faciales en video en tiempo real.

##   Uso de los Cuadernos

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace del cuaderno que deseas utilizar.
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial para seguir el flujo del código.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú "Entorno de ejecución" seleccionando "Ejecutar todo".
3.  **Experimentar**: Modifica el código, cambia los parámetros y prueba con tus propias imágenes o videos para explorar el análisis facial.

##   Bibliotecas Utilizadas

* **OpenCV (cv2)**: Biblioteca para procesamiento de imágenes y video.
* **dlib**: Biblioteca para visión artificial, utilizada para la detección de puntos clave faciales.
* **NumPy**: Biblioteca para operaciones numéricas.