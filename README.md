# Open Language Learning — MVP 0.1

Primera versión funcional: ejercicios breves de inglés, corrección orientativa local, estadísticas sencillas, guardado en el navegador, exportación/importación de respaldo y preparación PWA.

## Archivos
- `index.html`: interfaz.
- `styles.css`: diseño adaptable.
- `app.js`: ejercicios, corrección, progreso y respaldos.
- `manifest.webmanifest`: metadatos de instalación.
- `service-worker.js`: caché básica para uso sin conexión.
- `assets/icon.svg`: icono.

## Privacidad
No hay cuenta ni envío de respuestas a un servidor. El progreso se guarda en el navegador mediante `localStorage`. Borrar los datos del sitio, cambiar de navegador o reinstalar puede eliminarlo: exportá respaldos manuales.

## Probar
Para probar PWA y service worker, serví estos archivos en HTTPS o en localhost. Por ejemplo, desde esta carpeta ejecutá `python -m http.server 8000` y abrí `http://localhost:8000`.

## Limitaciones
La corrección usa reglas simples, no IA; puede equivocarse. La síntesis de voz depende del navegador. Las notificaciones no están implementadas. La selección A1/A2/B1 filtra ejercicios pero todavía no es una prueba diagnóstica. El modo offline debe probarse en cada dispositivo.

## Siguientes pasos
1. Probar en escritorio y teléfono.
2. Corregir errores detectados.
3. Mejorar el registro de errores por tema y los repasos espaciados.
4. Separar contenidos de idiomas de la lógica de la aplicación.
5. Verificar instalación y uso offline en Chrome y Brave.
