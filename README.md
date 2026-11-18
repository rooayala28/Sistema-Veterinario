# Sistema Veterinario · app compañera para el MVZ

Expediente, consulta guiada, recetas, hospitalización y turno del día, en una app web que funciona en iPhone, iPad y computadora.

- Versión: 0.9.6.1
- Datos: se guardan en el dispositivo (IndexedDB). Descarga respaldos desde Ajustes.
- Funciona sin internet una vez abierta (service worker `sw.js`).
- Al publicar una versión nueva, cambia `VERSION` en `sw.js` para que la app avise "Hay una versión nueva".

## Archivos
- `index.html` — la app completa
- `sw.js` — funcionamiento sin internet y aviso de actualización
- `manifest.json`, `icon-192.png`, `icon-512.png` — instalación en pantalla de inicio y accesos rápidos
