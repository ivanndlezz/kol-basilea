# Kol Basilea — Contexto fundacional para IA

## Origen

Kol Basilea nace como un proyecto editorial dedicado a explorar la fe cristiana, la teología, la historia, las Escrituras y la experiencia humana mediante investigación, reflexión y narración.

Su nombre combina creativamente *kol* (voz, en hebreo) y *basileia* (reino, en griego). Es una identidad editorial, no una frase bíblica original.

## Perspectiva teológica

La visión fundacional enfatiza el monoteísmo bíblico, el Shemá de Deuteronomio 6:4 y la identidad de Jesús como YHWH encarnado. Se trata de una perspectiva confesional propia, no del consenso de todas las tradiciones cristianas.

Los estudios pueden abordar cristología, historia doctrinal, antropología hebrea, lenguas bíblicas, literatura antigua y tradiciones interpretativas. Las diferencias doctrinales deben describirse con precisión y respeto.

## Áreas editoriales

- Estudios bíblicos y exégesis.
- Teología y cristología.
- Historia del cristianismo y fuentes antiguas.
- Reflexiones y devocionales.
- **Historias del Reino:** testimonios, narraciones y relatos sobre transformación, esperanza, comunidad y fe.

## Reglas para IA

Distinguir fuentes primarias, análisis, inferencias y convicciones. No inventar citas ni presentar hipótesis discutidas como certezas. Identificar cuándo una historia es ficción o testimonio. Preservar una voz clara, cálida, reflexiva y rigurosa. Leer `AGENTS.md` antes de editar contenidos.

## Arquitectura editorial y URLs

Los artículos se organizan por sección y por slug, con un directorio dedicado y `index.html` como punto de entrada. Esto facilita URLs limpias, recursos por publicación y crecimiento modular.

```text
historias-del-reino/
└── el-evangelio-antes-de-jesus/
    └── index.html
```

La URL canónica termina en `/`: `/historias-del-reino/el-evangelio-antes-de-jesus/`. Evitar nuevas publicaciones como `el-evangelio-antes-de-jesus.html`. Si una página cambia de ruta, preservar redirección desde la URL antigua y actualizar todas las rutas relativas, enlaces y metadatos.

La experiencia de lectura debe mantener al usuario en contexto: las referencias a personajes o conceptos presentan un resumen en bottom sheet (móvil) o side sheet (escritorio), con una acción explícita para abrir la ficha completa. Las fichas tienen URL propia y siguen siendo accesibles directamente.
