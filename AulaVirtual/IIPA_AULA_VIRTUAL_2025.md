*<h2 style="Color:red;"> INFOGRAFIAS HTML -CLAUDE</h2>*

Tarea: Genera un único archivo llamado guia-estudio.html que sea completamente auto-contenido y que cumpla todas las especificaciones siguientes. El archivo debe estar listo para abrir en cualquier navegador y para exportar/guardar como PDF manteniendo el mismo diseño vertical.
Idioma: Español.
Restricción clave: El único punto que el usuario debe editar para cambiar todo el contenido de la guía es una variable tema ubicada en la primera línea del bloque <script>.

Requisitos funcionales y estructurales

Primera líneas del <body>/<script>: declara exactamente esta variable editable como primer elemento del script:

<script>
const tema = "Sitio Web vs. Aplicación Web";
</script>


Dentro del mismo archivo, implementa un objeto temasData (o similar) que mapee tema a todo el contenido (títulos, subtítulos, párrafos, imágenes en data-URL, actividades, y referencias). El código debe:

Si tema existe en temasData, renderizar su contenido automáticamente en todas las secciones.

Si tema no existe, mostrar una plantilla editable con instrucciones y campos vacíos listos para completar.

Estructura del HTML (orden y anclas): Barra de navegación fija con logo/ícono + enlaces de ancla a estas secciones: Inicio, Objetivos, Contenido, Actividades, Referencias.

Secciones obligatorias y su contenido dinámico:

Inicio / Presentación: título grande, subtítulo, breve introducción automática basada en tema y al menos 1 imagen embebida (data URL o SVG inline) con atribución en comentarios.

Objetivos del Tema: lista (mínimo 3) de metas de aprendizaje generadas dinámicamente.

Contenido Teórico: textos largos, bloques con íconos explicativos (usar iconos via CDN), y al menos 1 imagen embebida. Soporta subsecciones con headings h2/h3.

Actividades Prácticas: incluye mínimo 3 ejercicios interactivos; al menos uno debe ser un quiz de opción múltiple en JavaScript con retroalimentación inmediata y marcador de resultado. Añade también una actividad tipo “arrastrar y soltar” o un ejercicio autocorregible (siempre implementado en JS puro).

Referencias: lista mínima de 3 enlaces académicos reales y verificados (DOI, repositorios universitarios o artículos). Si el generador no puede verificar automáticamente DOIs, inserta entradas reales de ejemplo y marca claramente en comentarios qué URL deben verificarse.

Accesibilidad y UX:

HTML semántico (header, nav, main, section, footer).

Soporte para navegación por teclado y atributos ARIA relevantes.

Interactividad y comportamiento:

Navegación suave (smooth scroll) entre secciones sin recargas.

Al cambiar el valor de tema y recargar la página, todo se actualiza automáticamente.

Botón para alternar modo claro/oscuro. Estado guardado en localStorage.

Estilos y descarga/impresión:

Todo el CSS dentro de una sola etiqueta <style> en el <head>. No archivos CSS externos salvo librerías por CDN autorizadas (ver sección de librerías).

Provee reglas @media print para que la exportación a PDF sea vertical, una columna, sin barra de navegación fija, sin animaciones, con tipografía y espaciado adecuados, y con saltos de página lógicos (page-break-inside: avoid en elementos card).

Asegúrate de que las imágenes embebidas se escalen correctamente en impresión y mantengan calidad razonable.

Scripts:

Todo el JavaScript debe estar dentro de una sola etiqueta <script> al final del <body>.

Código modular y comentado; funciones claras que generen DOM a partir de temasData[tema].

Seguridad y permisos:

No usar librerías de pago ni recursos con licencia restrictiva.

Imágenes libres de derechos: si usas imágenes externas como referencia, incluye la imagen embebida en data URL y deja la URL original en un comentario de atribución (por ejemplo: /* Fuente: https://unsplash.com/… */).

Calidad del código:

Comentarios claros que expliquen dónde editar tema y cómo agregar nuevos temas al temasData.

Código optimizado y legible, sin dependencias innecesarias.

Librerías permitidas (via CDN)

Bootstrap 5 (CDN) para layout y componentes.

Bootstrap Icons o Font Awesome (CDN) para iconos.

Opcional: AOS (Animate On Scroll) por CDN para animaciones (pero deshabilitado automáticamente en @media print).

Requisitos visuales y extras recomendados

Diseño moderno y profesional, paleta de colores sobria.

Uso de cards, tooltips y modales de Bootstrap para presentar contenido y respuestas del quiz.

Al menos un modal que muestre instrucciones de uso y la nota: “Para cambiar el tema edite únicamente la variable tema en la primera línea del bloque <script>”.

Exportación a PDF / impresión

Asegúrate de que al usar “Imprimir” → “Guardar como PDF” en el navegador se mantenga el diseño vertical y que la barra de navegación quede oculta.

Añade un botón visible “Exportar a PDF” que llame a window.print() y muestre instrucciones breves para obtener el mejor resultado (por ejemplo: márgenes pequeños, escala 100%).

Entrega

Devuelve un único archivo guia-estudio.html.

Incluye comentarios iniciales (arriba del archivo) que expliquen cómo editar tema y cómo añadir nuevas entradas a temasData.

Si por tamaño/limitación alguna imagen no puede ser embebida, deja un comentario claro indicando por qué y cómo reemplazarla por una data-URL.

Nota final para el generador: Prioriza que el archivo sea inmediato y plug-and-play: el usuario debería descargarlo, abrirlo en un navegador y ver una guía completa funcionando. El único cambio que debe hacer para adaptar la guía a otro tema es editar la variable tema al inicio y recargar la página.

*<h2 style="Color:red;">CLAUD </h2>*

Genera con html, css y javascript usan bootstrap una guia moderna y responsive del siguiente tema:Sitio Web vs. Aplicación Web con bibliografias y link de referencias de cada infromacion, debe tener una seccion de maro teorico informacion teorica con fuente confiables, seccion de ejemplos reales, secciones de comparaciones y caracteristicas, mucha informacion y referencias

*<h2 style="Color:red;">TRABAJOS EN CLASES-CHATGPT 5 </h2>*




*<h2 style="Color:red;">BIBLIOGRAFIAS--CHATGPT 5 </h2>*

“Busca libros y artículos científicos recientes (últimos 4 años) sobre \[*tema Sistema de inventarios*].

Prioriza fuentes académicas con DOI o URL permanentes (no enlaces rotos).

Verifica que cada enlace funcione correctamente y lleve al texto completo o al resumen del artículo/libro.

Entrega los resultados en formato de referencia APA 7 (incluyendo autor(es), año, título, editorial o revista, volumen/número si aplica, DOI o URL).

Si el DOI está disponible, debe figurar en la referencia.

Proporciona además una cita en el texto (formato autor, año) para cada fuente.

Excluye blogs, wikis, páginas sin revisión académica o enlaces caídos.

Incluye al menos \[número de referencias deseado, ej. 8] referencias de calidad.”


<iframe id="resourceobject" src="http://eva.istae.edu.ec/pluginfile.php/11105/mod_resource/content/1/guia-estudio.html?embed=1" style="width: 563px; height: 400px;">
    Haga clic en <a href="http://eva.istae.edu.ec/pluginfile.php/11105/mod_resource/content/1/guia-estudio.html" >guia-estudio.html</a> para ver el archivo.
  </iframe>


Tu historial de chat
}
