**********************************************************<h1 style="Color:red;"> INSTRUMENTOS DE EVALUACION</h1>************************************************




*<h2 style="Color:red;"> GENERAR INSTRUMENTOS DE EVALUACION DE DIAGNOSTICO </h2>*


# VARIABLES (Cambiar solo estas líneas)
TEMA = "DESARROLLO DE APPS WEB"
NUM_PREGUNTAS = 10
TIPO_PREGUNTA = "opción múltiple"   # Opción múltiple
NUM_OPCIONES = 4                     # Número de opciones por pregunta
INCLUIR_RESPUESTAS = "sí"           # "sí" o "no"
INCLUIR_RESULTADOS_APRENDIZAJE = "sí"  # "sí" o "no"
NUM_RESULTADOS = 3                   # Número de resultados de aprendizaje

# PROMPT PRINCIPAL
Genera contenido educativo para la asignatura **{TEMA}**, usando las siguientes instrucciones:

1. **Preguntas de diagnóstico**:
   - Crear **{NUM_PREGUNTAS} preguntas** sobre los conceptos fundamentales del tema {TEMA}.
   - Cada pregunta debe presentarse en **{TIPO_PREGUNTA}**, con **{NUM_OPCIONES} opciones** identificadas con las letras a, b, c, d (ajustar según {NUM_OPCIONES}).
   - Los temas pueden incluir: interfaz de usuario, usabilidad, UX, wireframes, mockups, jerarquía visual, colores, tipografía, prototipos, feedback del usuario.
   - Las **respuestas correctas** deben estar listadas al final en una **tabla con el siguiente formato**:

| N° | Respuesta |
|----|-----------|
| 1  | c) Opción correcta de la pregunta 1 |
| 2  | b) Opción correcta de la pregunta 2 |
| 3  | a) Opción correcta de la pregunta 3 |
| …  | …         |

2. **Resultados de aprendizaje**:
   - Si {INCLUIR_RESULTADOS_APRENDIZAJE} es "sí", generar **{NUM_RESULTADOS} resultados de aprendizaje** claros y concisos, enfocados en:
     - Identificación de principios, elementos y estructuras de la interfaz.
     - Aplicación de técnicas de diseño y evaluación de prototipos.
     - Uso de herramientas digitales para organizar información y mejorar la experiencia del usuario.
   - Presentar los resultados en **viñetas**.

3. **Formato de salida**:
   - Preguntas numeradas y limpias, listas para imprimir o aplicar en clase.
   - Instrucciones al estudiante al inicio:  
     "A continuación, se presentan una serie de preguntas de opción múltiple. Cada una incluye un enunciado seguido de cuatro posibles respuestas identificadas con las letras a, b, c y d. Solo una opción es correcta. Lea cuidadosamente cada pregunta y seleccione la respuesta que considere adecuada."
   - Tabla de respuestas al final, siguiendo el formato especificado.




AL FINALIZAR: GENERA UN ARCHIVO DE TIPO WORD DOCX

*<h2 style="Color:red;"> AUTOMATIZAR LA SUBIDA DE PREGUNTAS </h2>*


MENSAJE DE BIENVENIDA PARA LOS ESTUDIANTES DE 3A DE LA CARRERA DESARROLLO DE SOFTWARE EN LA MATERIA DE PROGRMACION WEB.


PONER LOS LITERALES EN a),b),c),d) en mayusculas A),B),C),D) Y AL FINALK DE CADA PREGUNTA EL LITERAL CORRECTOS CON EL TERMINO: ANSWER: y la letra de las respeusta correcta:1.   (AGREGAR LAS PREGUNTAS Y EL BANCO DE RESPEUSTA )

1. ¿Cuál es el propósito principal de un wireframe en el proceso de diseño de una app 
web? 
a) Crear la versión final con colores y tipografías definitivas. 
b) Probar las APIs y la lógica del servidor. 
c) Esbozar la estructura y la disposición de los elementos en pantalla (layout) de forma 
sencilla. 
d) Redactar el contenido y la copia de marketing. 
2. ¿Qué describe mejor el concepto de usabilidad? 
a) Que la interfaz sea visualmente atractiva sin importar la facilidad de uso. 
b) La facilidad con la que usuarios pueden aprender a usar y alcanzar sus objetivos con un 
producto. 
c) La velocidad de respuesta del servidor. 
d) La seguridad criptográfica de la aplicación. 
3. ¿Qué entiende la jerarquía visual en diseño de interfaces? 
a) La paleta de colores utilizada exclusivamente. 
b) La organización y priorización de elementos en pantalla para guiar la atención del 
usuario. 
c) Solo el tamaño de la tipografía. 
d) El proceso de testeo de backend. 
4. ¿Cuál es una buena práctica para asegurar contraste de color accesible en una 
interfaz? 
a) Usar colores muy suaves sin importar la legibilidad. 
b) Garantizar ratios de contraste suficientes entre texto y fondo según estándares (por 
ejemplo WCAG). 
c) Evitar texto y usar únicamente iconos. 
d) Colocar texto encima de imágenes sin sombreado. 
5. ¿Cuál es el objetivo principal de crear un prototipo (interactivo) durante el diseño? 
a) Generar el código final listo para producción. 
 
b) Validar interacciones, flujos y supuestos con usuarios antes de desarrollar. 
c) Reemplazar la documentación técnica. 
d) Optimizar la base de datos. 
6. ¿Cuál de estas herramientas está diseñada principalmente para crear mockups y 
prototipos de interfaces? 
a) Figma. 
b) GitHub. 
c) Postman. 
d) MySQL. 
7. ¿Para qué se utiliza el feedback de usuarios en el ciclo de diseño? 
a) Para eliminar funciones sin más criterio. 
b) Para identificar problemas reales, priorizar mejoras y refinar el diseño. 
c) Solo para justificar decisiones de marketing. 
d) Para aumentar el precio del producto automáticamente. 
8. Al planear una prueba de usabilidad, ¿qué acción es más efectiva? 
a) Preguntar únicamente al equipo de desarrollo qué les parece la interfaz. 
b) Observar a usuarios reales realizando tareas concretas y medir éxito/errores y tiempo. 
c) Solo enviar cuestionarios por correo sin observar interacción. 
d) Implementar cambios en producción sin probar. 
9. ¿Qué significa diseño responsive? 
a) Un diseño con tamaño fijo pensado solo para escritorio. 
b) Un diseño que adapta su layout y comportamiento a distintos tamaños de pantalla y 
dispositivos. 
c) Un sistema de diseño (design system) exclusivamente. 
d) Una herramienta de accesibilidad automática. 
10. ¿Cuál de las siguientes métricas suele indicar directamente problemas o aciertos en la 
experiencia de usuario durante una tarea? 
a) Número de líneas de código en el proyecto. 
b) Tiempo para completar la tarea y tasa de éxito en la tarea. 
c) Uso de memoria del servidor. 
d) Número de endpoints en la API.



RESPUESTA

N° Respuesta 
1 c) Esbozar la estructura y la disposición de los elementos en pantalla (layout) de forma sencilla. 
2 b) La facilidad con la que usuarios pueden aprender a usar y alcanzar sus objetivos con un 
producto. 
3 b) La organización y priorización de elementos en pantalla para guiar la atención del usuario. 
4 b) Garantizar ratios de contraste suficientes entre texto y fondo según estándares (por ejemplo 
WCAG). 
5 b) Validar interacciones, flujos y supuestos con usuarios antes de desarrollar. 
6 a) Figma. 
7 b) Para identificar problemas reales, priorizar mejoras y refinar el diseño. 
8 b) Observar a usuarios reales realizando tareas concretas y medir éxito/errores y tiempo. 
9 b) Un diseño que adapta su layout y comportamiento a distintos tamaños de pantalla y 
dispositivos. 
10 b) Tiempo para completar la tarea y tasa de éxito en la tarea.
