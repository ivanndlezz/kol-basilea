# Kol Basilea — Guía para agentes

Kol Basilea es un proyecto editorial sobre fe, Biblia, teología, historia del cristianismo y relatos llamados **Historias del Reino**.

## Principios de colaboración

- Investigar y citar fuentes comprobables.
- Distinguir texto bíblico, interpretación, hipótesis histórica y convicción doctrinal.
- Examinar las lenguas originales en contexto, evitando etimologías especulativas presentadas como hechos.
- Escribir en español claro, reflexivo y respetuoso.
- No inventar citas, bibliografía, testimonios ni consensos.
- Identificar los relatos como ficción, reconstrucción o testimonio.
- Respetar la visión fundacional de monoteísmo bíblico y Jesús como YHWH encarnado, sin atribuirla a todas las tradiciones cristianas.
- Exponer con fidelidad perspectivas divergentes.

Antes de cambiar la visión editorial o una tesis doctrinal central, solicitar revisión humana.

Consultar `README.md` y `AI_CONTEXT.md` para conocer el proyecto.

## Convención de rutas y estructura de artículos

- Cada artículo publicado debe tener una carpeta propia con un `index.html`, no un archivo HTML suelto con el slug del artículo.
- Estructura canónica: `<seccion>/<slug-del-articulo>/index.html`.
- URL pública canónica: `/<seccion>/<slug-del-articulo>/` (con barra final).
- Ejemplo: `historias-del-reino/el-evangelio-antes-de-jesus/index.html` → `/historias-del-reino/el-evangelio-antes-de-jesus/`.
- Usar slugs en minúsculas, separados por guiones, sin espacios ni tildes. Mantener los archivos compartidos (CSS, JavaScript e imágenes reutilizadas) en `assets/`.
- Al crear o mover artículos, actualizar enlaces del inicio, listados, guardados, referencias internas, URL canónica y rutas relativas de recursos; comprobar que las fichas contextuales sigan funcionando.
- Al migrar una URL ya publicada, conservar una redirección desde la dirección anterior para no romper enlaces existentes.
- Los enlaces editoriales a personajes o conceptos deben abrir una vista previa contextual (bottom sheet en móvil y side sheet en escritorio) cuando esté disponible; la navegación a la ficha completa queda a elección del lector.
