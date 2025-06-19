# Sesgo Algorítmico y Metadata: Generación de Datos Sintéticos con Faker

Este cuaderno de Colab titulado **[026 - faker](026%20-%20faker.ipynb)** explora, mediante un enfoque práctico, cómo surgen los **sesgos algorítmicos** en datasets y la importancia de la **metadata** para su gobernanza. Utiliza la librería `Faker` para crear datos sintéticos de empleados y documenta su estructura y sesgos en una metadata detallada.

## Introducción Teórica

Este notebook está orientado a fomentar buenas prácticas de **Gobernanza de la IA**. Se centra en:
- La generación de datos sintéticos con sesgos intencionales.
- La creación de metadata explicativa para transparentar y mitigar dichos sesgos.
- La conexión con casos reales como el de Amazon, donde el sesgo algorítmico en procesos de contratación tuvo consecuencias importantes.

El hilo conductor:  
**"Sesgos Algorítmicos: ¿Cómo los detectamos y combatimos desde la base? La Gobernanza de la IA empieza en los datos."**

## ¿Qué Vas a Aprender?

- Usar `Faker` para crear perfiles sintéticos de empleados.
- Introducir sesgos intencionales (ej. desbalance de género).
- Construir metadata completa y responsable para un dataset.
- Reflexionar sobre el rol ético de quien diseña y alimenta modelos de IA.

## Uso del Cuaderno

1. **Abrí el cuaderno en Google Colab**:  
   Haz clic en el archivo `026 - faker.ipynb` para abrirlo en Colab.

2. **Ejecutá las celdas en orden**:  
   - Con `Shift + Enter`, o desde el menú: `Entorno de ejecución > Ejecutar todo`.

3. **Flujo del cuaderno**:
   - Instalación de librerías (`Faker`, `pandas`).
   - Generación de un dataset sesgado de empleados.
   - Cálculo y visualización de la distribución de género.
   - Construcción de un diccionario de metadata detallado en JSON.
   - Reflexiones sobre gobernanza de IA y ejercicios adicionales.

## Bibliotecas Utilizadas

- **Faker**: Para generar nombres, apellidos, fechas y datos sintéticos.
- **pandas**: Para estructurar la información en tablas.
- **json / datetime**: Para construir y dar formato a la metadata.
- **random**: Para definir la probabilidad de aparición de ciertos valores.

## Recomendaciones

> Este dataset **no representa datos reales** y fue creado solo con fines educativos.  
> La metadata documenta explícitamente el **sesgo de género intencional** y su posible impacto si se entrenara un modelo sin mitigación.

---

**Explorá, modificá y reflexioná** sobre cómo pequeños cambios en los datos pueden tener grandes efectos en los modelos.

