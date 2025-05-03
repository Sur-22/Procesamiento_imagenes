# Template Matching con OpenCV

Este repositorio contiene un cuaderno de Colab que demuestra el uso de la técnica de "Template Matching" (Coincidencia de Plantilla) con la biblioteca OpenCV.

## Contenido del Cuaderno

El cuaderno `007 - Template_Matching_con_OpenCV.ipynb` explica cómo encontrar la ubicación de una imagen "plantilla" dentro de una imagen más grande. [cite: 1, 2, 4, 7]

Los pasos principales que se demuestran son:

1.  **Creación de imágenes**: Se crea una imagen principal y una imagen de plantilla simple, ambas en escala de grises. [cite: 1, 2, 3] La imagen principal contiene un cuadrado y un círculo, y la plantilla contiene el cuadrado. [cite: 1, 2, 3]
   
2.  **Template Matching**: Se utiliza la función `cv2.matchTemplate` de OpenCV para buscar la plantilla dentro de la imagen principal. [cite: 4] El método `cv2.TM_CCOEFF_NORMED` se utiliza para obtener una coincidencia robusta. [cite: 4]
   
3.  **Localización de la coincidencia**: Se utiliza la función `cv2.minMaxLoc` para encontrar la ubicación de la mejor coincidencia. [cite: 5, 8]
   
4.  **Visualización del resultado**: Se dibuja un rectángulo alrededor de la región encontrada en la imagen principal para resaltar la coincidencia. [cite: 8, 9] Se utiliza Matplotlib para mostrar la imagen original, la plantilla y el resultado. [cite: 1, 9, 10, 11, 12]

## Uso del Cuaderno

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace `007 - Template_Matching_con_OpenCV.ipynb` para abrirlo en Google Colab.
   
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.
   
3.  **Experimentar**: Puedes modificar la imagen principal y la plantilla para probar con diferentes formas o imágenes.  También puedes explorar otros métodos de coincidencia de plantillas disponibles en OpenCV.

## Bibliotecas Utilizadas

* **OpenCV (cv2)**: Biblioteca para procesamiento de imágenes. [cite: 1]
   
* **NumPy**: Biblioteca para operaciones numéricas. [cite: 1]
   
* **Matplotlib**: Biblioteca para crear visualizaciones. [cite: 1]