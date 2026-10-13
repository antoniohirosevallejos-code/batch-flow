# Batch Flow Video — publicación

Archivos estáticos preparados para GitHub Pages. Clave fija de esta entrega: **PandaFlow-20-Video**.

## Publicar desde el celular
1. Descarga y descomprime el ZIP.
2. Entra a https://github.com/antoniohirosevallejos-code/batch-flow y sube los cuatro archivos (`index.html`, `style.css`, `app.js`, `README.md`) a la raíz del repositorio.
3. En Settings → Pages, selecciona la rama `main` y carpeta `/ (root)`. Guarda y espera la URL HTTPS.
4. Prueba primero con un MP4 pequeño, con y sin audio, y revisa el video exportado antes de venderlo.

## Payhip
El enlace proporcionado, https://payhip.com/PandaNotas, es la tienda general, no necesariamente la página de compra de Batch Flow Video. Crea un producto independiente a USD 20 y utiliza su enlace individual para dirigir compradores a ese producto. No reutilices el enlace de Visualizer Flow por error.

## Límites y honestidad
- Hasta 3 videos por lote, secuenciales; duración máxima por archivo 210 segundos.
- Exporta MP4 H.264/AAC a 30 fps con fondo desenfocado y el video completo centrado.
- El motor FFmpeg.wasm y JSZip se cargan desde CDN, así que se necesita internet. Los videos se procesan en el navegador y no se envían a un servidor propio.
- La clave fija es una barrera básica, no una protección segura: el JavaScript del sitio es público y alguien técnico puede extraerla o saltarse el control.
- El límite de duración no garantiza compatibilidad universal. Resolución, códec, memoria y navegador pueden provocar fallos; ZIP puede consumir memoria extra.
- Se comprobó la integridad del ZIP y la sintaxis JavaScript cuando Node está disponible. Eso no equivale a una prueba real de conversión en todos los teléfonos. Antes de vender, prueba con archivos reales en el dispositivo de destino.
