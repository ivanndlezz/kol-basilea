# Kol Basilea — Dirección de diseño web (v1)

## Referencias examinadas
- Klef Sonatta: `ivanndlezz/klef-sonatta-website/assets/styles/design-system.css` y `index.html`.
- NewFace, únicamente superficies públicas: `ivanndlezz/newfacecards-app/two-worlds/index.html`, `two-worlds/two-worlds.css`, `docs/index.html` y `docs/COMMERCIAL_SITE_STRATEGY.md`. No utilizar la App como referencia de interfaz.

## Principio
**Arquitectura Klef + claridad de NewFace + voz editorial propia.**

El sistema visual de Kol Basilea no debe reproducir el marketing tecnológico de NewFace ni la identidad corporativa de Klef. Adoptará sus prácticas de diseño modular y claridad narrativa para un medio centrado en lectura, historia, fe y fuentes.

## Tokens semánticos
- Fondo: `#FFFFFF`; fondo secundario: `#F5F6F7`.
- Texto principal: `#22323A`; texto secundario: `#6E6E73`.
- Acento editorial propio: `#6A604E` (propuesta, por validar).
- Bordes: `rgba(0,0,0,.08)`.
- Fuente de interfaz: `-apple-system, BlinkMacSystemFont, "SF Pro Display", "Segoe UI", sans-serif`.
- Fuente de lectura: Georgia, serif; titulares editoriales con serif, sin importar fuentes propietarias.
- Espaciado basado en escala 4, 8, 12, 16, 24, 32, 48, 64, 96, 128 px de Sonatta.
- Radios de componentes: 16, 18, 20, 24 y 32 px, aplicados con moderación en superficies editoriales.
- Animaciones: 150–300 ms y respeto a `prefers-reduced-motion`.

## Componentes
- `SiteHeader`: identidad y navegación responsiva.
- `EditorialHero`: propuesta del medio y contenido destacado.
- `StoryCard`: título, categoría, extracto, fecha, imagen opcional.
- `StoryIndex`: catálogo por sección y búsqueda futura.
- `ArticleLayout`: ancho de lectura limitado, tipografía, encabezados, citas y notas.
- `SourceNotes`: distinguir cita, reconstrucción narrativa, hipótesis y fuentes.
- `SiteFooter`: navegación secundaria e identidad.

## Arquitectura de contenido
Los archivos Markdown son la fuente canónica. El sitio público debe mostrar HTML navegable. La siguiente iteración implementará generación automática de páginas desde Markdown, en vez de mantener copias HTML manuales.

## Patrones aprendidos de NewFace
- El Home explica primero la propuesta de valor, después muestra ejemplos y profundiza por áreas.
- La documentación ofrece una portada clara, navegación por secciones y búsqueda.
- Las páginas públicas y la operación interna son superficies separadas.
- En Kol Basilea: portada editorial → historias destacadas → categorías → artículos; índice y fuentes navegables.

## Prioridades
1. Migrar el CSS actual a tokens semánticos coherentes.
2. Separar layout global de estilos de portada y artículo.
3. Añadir un índice real de Historias del Reino.
4. Automatizar el render de Markdown a HTML en GitHub Pages.
5. Añadir sitemap, metadatos sociales y pruebas responsive/accesibilidad.

## Guardrails
- No copiar logos, imágenes, material comercial ni código propietario entre proyectos.
- No mezclar el diseño de la App NewFace con el sitio público.
- No convertir opiniones teológicas o reconstrucciones literarias en hechos documentados.
- Priorizar lectura, rendimiento y accesibilidad sobre animaciones decorativas.
