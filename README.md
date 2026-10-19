# La Gran Pecera de las Combinaciones

Archivos públicos de la aplicación web: `index.html`, `styles.css`, `app.js`, `manifest.json` y `sw.js`.

## Publicar con GitHub Pages
1. Sube estos archivos a la raíz del repositorio (no subas `Code.gs`, claves, datos ni hojas de cálculo).
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, branch `main`, folder `/ (root)` y guarda.
4. Espera a que GitHub Pages indique que el sitio está publicado.

## Antes de usar con estudiantes
El frontend está configurado con la URL de Apps Script que se proporcionó durante la configuración. La respuesta `doGet` confirma disponibilidad del servicio, pero no demuestra que las acciones POST (registro, sincronización, recuperación y panel docente) funcionen. Prueba primero con datos ficticios y verifica que el servidor valide todas las acciones. Mantén la hoja de Google Sheets privada. No subas `Code.gs` a este repositorio público.
