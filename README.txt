BATCH FLOW VIDEO V4 — CARGA DEL MOTOR DESDE INTERNET

Archivos para subir a la raíz del repositorio GitHub Pages:
- index.html
- style.css
- app.js
- hero-skate.webp

No incluye el motor FFmpeg pesado. La aplicación lo descarga al usar la herramienta, con dos mirrors (jsDelivr y unpkg) y crea un Worker local de tipo Blob para evitar el fallo anterior de Worker cross-origin. El motor y JSZip necesitan conexión a internet durante la carga.

PRUEBA: sube estos cuatro archivos a la raíz, espera la publicación y prueba primero un MP4 corto. La descarga inicial del motor es de aproximadamente 32 MB y puede tardar. Si el teléfono cierra la pestaña o el navegador bloquea los CDN, la conversión puede fallar; esta versión todavía necesita una prueba real en el teléfono.

La aplicación usa @ffmpeg/ffmpeg 0.12.10 (MIT) y @ffmpeg/core 0.12.10 (GPL-2.0-or-later), cargados desde sus distribuidores CDN. Revisa y cumple las licencias antes de distribuir comercialmente.
