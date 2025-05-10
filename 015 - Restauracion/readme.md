#   Restauración Básica de Imágenes

Este repositorio contiene tres cuadernos de Colab que exploran los fundamentos de la restauración de imágenes, centrándose en la reducción del desenfoque.

##   Contenido de los Cuadernos

Los cuadernos incluidos en este repositorio demuestran diferentes aspectos y enfoques de la restauración de imágenes, específicamente la corrección del desenfoque.

* **[001 Restauración](001_Restauracion.ipynb)**

    * Este cuaderno se centra en la restauración de imágenes que sufren de **desenfoque por movimiento horizontal uniforme**.
    * Explica cómo se puede simular este tipo de degradación y cómo aplicar un filtro inverso simple para intentar restaurar la imagen.
    * Incluye experimentación con diferentes imágenes para observar los resultados de la restauración.

* **[002 Restauración](002_Restauracion.ipynb)**

    * Similar al primer cuaderno, este también aborda la **restauración de imágenes con desenfoque de movimiento**.
    * Puede presentar una implementación ligeramente diferente del filtro de restauración o utilizar una imagen de ejemplo distinta, permitiendo comparar los resultados.
    * Incluye una sección de experimentación para ajustar parámetros o probar con otras imágenes.

* **[003 Restauración](003_Restauracion.ipynb)**

    * Este cuaderno continúa explorando la **restauración de imágenes borrosas**, posiblemente con un enfoque en un tipo diferente de desenfoque o una técnica de restauración más avanzada.
    * Puede introducir conceptos adicionales como filtros de Wiener o regularización para mejorar los resultados de la restauración.
    * También anima a la experimentación para comprender mejor las fortalezas y limitaciones de las técnicas presentadas.

##   Enfoques Diferentes

Si bien los tres cuadernos comparten el tema general de la restauración de imágenes y la corrección del desenfoque, es importante tener en cuenta que pueden diferir en los siguientes aspectos:

* **Imágenes de Ejemplo**: Cada cuaderno puede utilizar diferentes imágenes para demostrar las técnicas de restauración. Esto permite a los usuarios ver cómo los algoritmos funcionan en distintos tipos de contenido (por ejemplo, retratos, paisajes, objetos).
   
* **Tipos de Desenfoque**: Los cuadernos podrían simular o corregir diferentes tipos de desenfoque, como desenfoque de movimiento lineal, desenfoque gaussiano o desenfoque uniforme.
   
* **Técnicas de Restauración**: Los cuadernos pueden implementar distintas técnicas de restauración, desde filtros inversos básicos hasta métodos más sofisticados como filtros de Wiener o algoritmos de deconvolución.
   
* **Parámetros y Ajustes**: Los parámetros de los filtros de restauración pueden variar entre los cuadernos, lo que afecta el resultado final. Se anima a los usuarios a experimentar con estos parámetros para encontrar los mejores resultados para cada imagen.

##   Uso de los Cuadernos

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace del cuaderno que deseas utilizar.
   
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial para seguir el flujo del código y las explicaciones.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú "Entorno de ejecución" seleccionando "Ejecutar todo".
   
3.  **Experimentar**: Modifica el código, cambia los parámetros de los filtros y prueba con tus propias imágenes para explorar los conceptos de restauración de imágenes.