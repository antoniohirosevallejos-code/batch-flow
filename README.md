# Batch Flow Video — paquete de publicación

Esta carpeta contiene la versión web lista para subir a la raíz del repositorio de GitHub Pages.

## Archivos
- `index.html`: página y estructura de la herramienta.
- `style.css`: diseño adaptable a teléfonos y computadores.
- `app.js`: acceso y procesamiento de video en el navegador.
- `assets/hero-skate.webp`: imagen optimizada de la portada.

## Publicar desde el teléfono
1. Abre el repositorio https://github.com/antoniohirosevallejos-code/batch-flow.
2. Sube/reemplaza `index.html`, `style.css`, `app.js` y `README.md` en la raíz. Sube también la carpeta `assets` con `hero-skate.webp` dentro.
3. En Settings → Pages, confirma que GitHub Pages publica la rama `main` desde la carpeta raíz.
4. Espera a que termine el despliegue y abre la web. La clave de acceso es `PandaFlow-20-Video`.

## Configuración de venta
La tienda proporcionada https://payhip.com/PandaNotas es la página general de la tienda, no necesariamente el checkout de este producto. Crea un producto individual a USD 20 y configura la entrega de la clave y el enlace de la herramienta en Payhip. No reutilices el checkout de Visualizer Flow.

## Comportamiento y límites
- Hasta 3 videos de entrada por tanda; se procesan de forma secuencial.
- Cada entrada puede durar hasta 3 min 30 s.
- Modo predeterminado: genera vertical 9:16, cuadrado 1:1 y horizontal 16:9 por cada video. Modo alternativo: solo un formato elegido.
- Exportación prevista a MP4 H.264/AAC, 30 fps, con el video principal completo y fondo desenfocado.
- El procesamiento de los videos ocurre en el navegador; esta página no sube los archivos a un servidor propio. La carga inicial de componentes sí necesita conexión a internet.
- La compatibilidad depende del navegador, el códec, la resolución y la memoria del dispositivo. No se garantiza conversión para todos los archivos o teléfonos; prueba con un video corto primero.
- La clave fija es una barrera básica, no seguridad robusta: el código de una página estática puede inspeccionarse.

## Verificación importante
Se revisaron la estructura de archivos y la sintaxis JavaScript. No se pudo ejecutar una conversión real en este entorno sin acceso a internet/CDN; por tanto, la carga del motor y la conversión final deben probarse en la web publicada desde el teléfono antes de vender el acceso.
