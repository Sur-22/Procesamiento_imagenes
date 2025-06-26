# Anonimización Facial en Imágenes y Videos

Este cuaderno de Colab titulado **[Sistema de anonimización para rostros en imágenes y videos](Sistema_de_anonimización_para_rostros_en_imagenes_y_videos.ipynb)** implementa un sistema avanzado de detección y **anonimización facial automática** en imágenes y videos. Utiliza modelos preentrenados para reconocimiento facial y una interfaz interactiva basada en **Gradio**.

## Introducción Técnica

El objetivo de este proyecto es:

- Detectar rostros automáticamente en imágenes y videos.
- Permitir que ciertos rostros (autorizados) no sean anonimizados.
- Aplicar **anonimización visual** (difuminado) en los rostros desconocidos.
- Exportar imágenes y videos con los rostros anonimizados.
- Operar mediante una interfaz amigable para el usuario sin escribir código.

La anonimización se realiza con una **máscara elíptica** sobre la región facial, alineada automáticamente usando puntos clave (landmarks).

## ¿Cómo Funciona?

- Utiliza `InsightFace` con RetinaFace para detección de rostros.
- Extrae **embeddings faciales** con `InceptionResnetV1` (facenet-pytorch).
- Compara cada rostro con una base de datos de rostros autorizados.
- Si no se reconoce, lo anonimiza usando un **blur facial localizado**.
- Todo el sistema está encapsulado en una interfaz **Gradio** para uso visual.

## Instrucciones de Uso

1. **Abrí el cuaderno en Google Colab**:  
   Hacé clic en `Sistema_de_anonimización_para_rostros_en_imagenes_y_videos.ipynb` y seleccioná “Abrir en Colab”.

2. **Ejecutá todas las celdas**:  
   Usá `Entorno de ejecución > Ejecutar todo`.

3. **Interfaz Gradio (automática)**:
   - Paso 1: Subí imágenes con rostros conocidos que **no quieras anonimizar**.
   - Paso 2: Subí imágenes o videos que quieras procesar.
   - Elegí el nivel de anonimización (desenfoque).
   - Al finalizar, podés descargar los archivos anonimizados en formato ZIP.

## Archivos Procesables

- **Imágenes**: JPG, PNG  
- **Videos**: MP4, MOV, AVI, MKV, WEBM  
  *(los `.webm` se convierten automáticamente a `.mp4` usando ffmpeg)*

## Bibliotecas Utilizadas

- **InsightFace + RetinaFace**: detección y landmarks faciales.
- **InceptionResnetV1 (facenet-pytorch)**: generación de embeddings faciales.
- **OpenCV**: procesamiento de imágenes y videos.
- **Gradio**: interfaz web interactiva.
- **NumPy, PIL, SciPy**: soporte general.
- **ffmpeg** (vía `subprocess`): conversión de videos.

## Ejemplo de Aplicación

> Este sistema puede ser utilizado para anonimizar personas en videos o fotos antes de su publicación, proteger identidades o entrenar modelos éticos sin usar datos sensibles.

---

> Este código requiere acceso a GPU para funcionar de forma fluida, especialmente en videos. 
