VocalEar Studio — Prototipo inicial
===================================

QUÉ INCLUYE
- Pantallas de inicio, afinación visual, teoría, escalas, acordes, progreso y zona docente.
- Diseño adaptable a móvil con paleta azul noche, negro y dorado.
- Navegación y controles interactivos.
- Manifest y service worker básicos para preparar la experiencia PWA.

IMPORTANTE
- La afinación es SIMULADA en esta primera versión. No usa el micrófono ni mide tu voz.
- Los datos de progreso son demostrativos y todavía no se guardan en una cuenta.
- La selección de archivos solo muestra el nombre local; no sube nada a un servidor.
- No hay todavía cuentas, base de datos, pagos ni sincronización entre dispositivos.

CÓMO PROBAR DESDE UN TELÉFONO ANDROID
1. Descarga y extrae VocalEar_Studio.zip con la app Archivos de tu teléfono.
2. Para probarla rápidamente, abre index.html con un navegador compatible si tu teléfono permite abrir archivos HTML.
3. Para instalarla como PWA y que funcione sin conexión, debe alojarse primero en un sitio HTTPS (por ejemplo, GitHub Pages). Abrir el archivo local no habilita todas las funciones PWA.
4. La siguiente etapa será publicar estos archivos en un alojamiento HTTPS y luego implementar el afinador real con micrófono.

ARCHIVOS
- index.html: aplicación completa en un único archivo.
- manifest.json: metadatos de instalación PWA.
- sw.js: caché básica para uso offline después de alojar en HTTPS.
