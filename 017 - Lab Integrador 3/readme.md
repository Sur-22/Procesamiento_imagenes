#   Laboratorio Integrador 3:  Análisis de Expresiones Faciales

Este cuaderno de Colab se centra en el análisis de expresiones faciales a través del procesamiento de imágenes. El objetivo principal es detectar y medir características clave del rostro, como los ojos y la boca, para cuantificar ciertos aspectos de la expresión facial.

##   Objetivos

El cuaderno busca implementar metodologías para:

* **Detección de puntos clave faciales**: Localizar puntos específicos del rostro (ojos, boca).
* **Cálculo de métricas de expresión**:  Calcular el Eye Aspect Ratio (EAR) y el Mouth Aspect Ratio (MAR) para analizar la apertura de los ojos y la boca.

##   Metodologías

Se emplean técnicas de procesamiento de imágenes y visión computacional para:

1.  **Carga y preprocesamiento de imágenes**:  Preparar las imágenes para el análisis facial.
2.  **Detección de rostros**: Localizar la región del rostro en la imagen.
3.  **Extracción de puntos clave**: Identificar las localizaciones de los ojos y la boca.
4.  **Cálculo de EAR y MAR**:  Medir la apertura de los ojos y la boca basándose en las coordenadas de los puntos clave.
    * EAR: Útil para detectar parpadeo o ojos cerrados.
    * MAR: Útil para analizar la apertura de la boca.

##   Uso del Cuaderno

1.  **Abrir el cuaderno en Colab**: Haz clic en el enlace `017 - Lab Integrador 3.ipynb` para abrirlo en Google Colab.
2.  **Ejecutar las celdas**: Ejecuta las celdas del cuaderno en orden secuencial.
    * Puedes ejecutar cada celda individualmente presionando `Shift + Enter`.
    * O puedes ejecutar todas las celdas a la vez desde el menú `Entorno de ejecución` seleccionando `Ejecutar todo`.

##   Bibliotecas Utilizadas

* **OpenCV (cv2)**: Biblioteca para procesamiento de imágenes y visión artificial[cite: 1, 2, 3].
* **dlib**:  Herramienta para visión artificial (puede usarse para detección de puntos clave)[cite: 17].
* **NumPy**:  Biblioteca para operaciones numéricas[cite: 6, 8, 12].