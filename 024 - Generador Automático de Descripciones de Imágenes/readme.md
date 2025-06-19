# 📚 Cuadernos de Procesamiento Digital de Imágenes

Este repositorio contiene cuadernos de Google Colab relacionados con el Procesamiento Digital de Imágenes.

## 📝 Índice de Cuadernos

* [cite_start][**024 - Img Caption.ipynb**](024%20-%20Img%20Caption.ipynb) : Generación Automática de Descripciones de Imágenes 

---

## 🚀 024 - Img Caption.ipynb: Generación Automática de Descripciones de Imágenes

[cite_start]Este cuaderno te guía a través de la generación automática de descripciones para imágenes utilizando Modelos de Lenguaje Visual (VLMs). [cite_start]Aprenderás a usar estos modelos para "subtitular" tus imágenes y, lo que es aún mejor, ¡en español!  [cite_start]Al final, tendrás un sistema funcional que genera estas descripciones automáticamente.

### [cite_start]🎯 Objetivos de Aprendizaje 

Al finalizar este cuaderno, podrás:

* [cite_start]**Entender cómo funcionan los VLMs (Modelos de Lenguaje-Visión):** Comprenderás cómo estos modelos combinan lo que "ven" con lo que "entienden" del lenguaje para generar texto.
* [cite_start]**Generar subtítulos automáticamente:** Explorarás cómo se crean descripciones de imágenes de forma autónoma.
* [cite_start]**Implementar un sistema completo:** Armarás un generador de descripciones de imágenes que funcione en español.

### [cite_start]📌 Conceptos Clave 

Para seguir el hilo del cuaderno, tené en cuenta estos conceptos:

* [cite_start]**Image Captioning:** Es el proceso automático de generar texto que describe el contenido visual de una imagen. [cite_start]Imaginate que tenés una foto y querés que una computadora le ponga un "subtítulo" o una descripción, eso es `Image Captioning`.
* [cite_start]**BLIP (Bootstrap Language-Image Pre-training):** Este es el modelo de IA que se utiliza para el `Image Captioning`. [cite_start]Es un modelo de `transformers` que fue entrenado con muchísimas imágenes y textos, lo que le permite entender la relación entre lo visual y lo textual.
* [cite_start]**Traducción Automática:** Como el modelo BLIP genera las descripciones en inglés, se usa otro modelo para traducir automáticamente esas descripciones al español. [cite_start]Es como tener un traductor instantáneo para nuestro sistema.

### ⚙️ Instrucciones de Uso

Para ejecutar este cuaderno y probar el sistema de generación de descripciones, sigue estos pasos:

1.  **Abre el cuaderno en Google Colab:** Haz clic en el enlace "024 - Img Caption.ipynb" en el índice de arriba, o navega hasta el archivo en tu repositorio de GitHub y selecciónalo. Una vez en GitHub, haz clic en el botón "Open in Colab" (o "Abrir en Colab") en la parte superior.

2.  [cite_start]**Instala las dependencias:** Una vez abierto el cuaderno en Colab, busca la celda con el título `# @title Instalación de Dependencias`  [cite_start]y ejecútala. [cite_start]Esto instalará las librerías necesarias como `transformers`, `gradio`, `Pillow`, `accelerate` y `sentencepiece`. [cite_start]Se te indicará si debes reiniciar el entorno de ejecución.

3.  [cite_start]**Importa librerías y configura modelos:** Ejecuta la celda con el título `# @title Importando Librerías y Configuracion de Modelos`. [cite_start]Esto cargará los modelos de Inteligencia Artificial que realizan la magia de "leer" la imagen y traducirla. [cite_start]Incluye el `BlipProcessor`, `BlipForConditionalGeneration` y un modelo de traducción de inglés a español.

4.  [cite_start]**Define la función `generar_descripcion`:** Ejecuta la celda con el título `# @title Función generar_descripcion`. [cite_start]Esta función es el corazón del sistema, se encarga de procesar la imagen, generar la descripción en inglés y luego traducirla al español.

5.  [cite_start]**Inicia la interfaz de usuario:** Finalmente, ejecuta la celda con el título `# @title 🌐 Interfaz de Usuario`. [cite_start]Esta celda creará una interfaz web simple con Gradio. [cite_start]Una vez ejecutada, verás una URL (puede tardar unos segundos en aparecer). [cite_start]Haz clic en esa URL para abrir la interfaz de Gradio en tu navegador y ¡empezá a probar tu generador de descripciones! 

### [cite_start]📝 Instrucciones para Usar la Interfaz 

1.  [cite_start]**Subí una imagen:** Usá el campo de arriba que dice "Subí tu imagen acá". [cite_start]Podés arrastrar y soltar una foto, o **clickear** para seleccionarla desde tu computadora.
2.  [cite_start]**Generar la descripción:** Una vez que la imagen está cargada, **hacé clic** en el botón "Generar Descripción".
3.  [cite_start]**Observá los resultados:** Vas a ver un cuadro con formato JSON que te va a mostrar la descripción en inglés y la traducción al español.

### [cite_start]🤔 Para Pensar un Poco: Reflexiones 

Una vez que hayas probado el sistema, tómate un momento para reflexionar sobre lo siguiente:

* ¿Qué tan precisas te parecieron las descripciones que generó el modelo? ¿Te sorprendió alguna? 
* ¿Qué tipo de detalles captó mejor el modelo en las imágenes? [cite_start]¿Y cuáles no tanto? 
* [cite_start]Si tuvieras que mejorar algo, ¿cómo crees que se podría mejorar la calidad de las traducciones al español? 
* Pensando en el mundo real, ¿qué aplicaciones prácticas le ves a esta tecnología? ¿Dónde la usarías? 

---

## 🏆 Conclusión

¡Felicitaciones! 🎉 Has llegado al final de esta clase y has armado tu propio sistema de generación automática de descripciones de imágenes. Hoy aprendiste cómo los Modelos de Lenguaje-Visión (VLMs) pueden "entender" y "describir" el contenido de una imagen, y cómo puedes usar la traducción automática para que esos resultados estén en español.

Viste cómo se combinan diferentes modelos (uno para el captioning, otro para la traducción) y cómo `Gradio` te permite armar una interfaz de usuario muy rápido.

---

### 👉 Próximos Pasos 

La Inteligencia Artificial es un campo que crece muy rápido. Aquí te dejamos algunas ideas para que sigas investigando:

* [cite_start]**Experimentá con otros modelos:** En Hugging Face tenés un montón de modelos de `Image Captioning` y `Traducción` para probar. [cite_start]¿Hay alguno que funcione mejor? 
* **Mejorá la traducción:** A veces las traducciones automáticas no son perfectas. ¿Cómo podrías incorporar más contexto o incluso usar modelos de traducción más avanzados? 
* [cite_start]**Agregá funcionalidades:** ¿Qué tal si tu sistema pudiera identificar objetos específicos en la imagen o responder preguntas sobre ella?  [cite_start]Investigá sobre `Object Detection` o `Visual Question Answering`.
* **Optimizá el rendimiento:** Si querés que tu modelo sea más rápido, podrías investigar técnicas de cuantización o _distillation_.