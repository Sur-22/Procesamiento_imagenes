#   Operaciones Morfológicas en Procesamiento de Imágenes

Este cuaderno de Colab explora las **operaciones morfológicas** en procesamiento de imágenes[cite: 1]. Estas técnicas modifican la forma y estructura geométrica de los objetos en una imagen[cite: 1].

##   Introducción Teórica

Las operaciones morfológicas se basan en el uso de un **elemento estructurante** (también llamado kernel o máscara), que es una pequeña matriz (generalmente binaria) que se desliza sobre la imagen[cite: 1]. El elemento estructurante define una vecindad de píxeles, y la operación morfológica determina el valor del píxel central en la imagen de salida basándose en los píxeles de esa vecindad en la imagen de entrada[cite: 1, 2].

Estas operaciones son útiles para:

* Eliminar ruido[cite: 2].
* Segmentar objetos[cite: 2].
* Encontrar contornos[cite: 2].
* Extraer esqueletos de objetos[cite: 2].
* Medir y cuantificar formas[cite: 2].

Este cuaderno trabaja principalmente con imágenes binarias (blanco y negro) y también muestra ejemplos en escala de grises[cite: 2].

##   Uso del Cuaderno

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace `014 - Operaciones_Morfológicas.ipynb` para abrirlo en Google Colab.
   
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.

##   Bibliotecas Utilizadas

* **OpenCV (cv2)**: Biblioteca para procesamiento de imágenes.
* **NumPy**: Biblioteca para operaciones numéricas.
* **Matplotlib**: Biblioteca para crear visualizaciones.