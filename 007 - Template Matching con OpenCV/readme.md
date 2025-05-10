# Template Matching con OpenCV

Este repositorio contiene un cuaderno de Colab que demuestra el uso de la técnica de "Template Matching" (Coincidencia de Plantilla) con la biblioteca OpenCV.

## Contenido del Cuaderno

El cuaderno **[Template Matching con OpenCV](007%20-%20Template_Matching_con_OpenCV.ipynb)** explica cómo encontrar la ubicación de una imagen "plantilla" dentro de una imagen más grande.

Los pasos principales que se demuestran son:

1.  **Creación de imágenes**: Se crea una imagen principal y una imagen de plantilla simple, ambas en escala de grises. La imagen principal contiene un cuadrado y un círculo, y la plantilla contiene el cuadrado. 
   
2.  **Template Matching**: Se utiliza la función `cv2.matchTemplate` de OpenCV para buscar la plantilla dentro de la imagen principal. El método `cv2.TM_CCOEFF_NORMED` se utiliza para obtener una coincidencia robusta. 
3.  **Localización de la coincidencia**: Se utiliza la función `cv2.minMaxLoc` para encontrar la ubicación de la mejor coincidencia.
   
4.  **Visualización del resultado**: Se dibuja un rectángulo alrededor de la región encontrada en la imagen principal para resaltar la coincidencia. Se utiliza Matplotlib para mostrar la imagen original, la plantilla y el resultado. 
## Uso del Cuaderno

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace `007 - Template_Matching_con_OpenCV.ipynb` para abrirlo en Google Colab.
   
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.
   
3.  **Experimentar**: Puedes modificar la imagen principal y la plantilla para probar con diferentes formas o imágenes.  También puedes explorar otros métodos de coincidencia de plantillas disponibles en OpenCV.

## Bibliotecas Utilizadas

* **OpenCV (cv2)**: Biblioteca para procesamiento de imágenes. 
   
* **NumPy**: Biblioteca para operaciones numéricas. 
   
* **Matplotlib**: Biblioteca para crear visualizaciones.