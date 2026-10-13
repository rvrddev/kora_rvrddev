# Mi Horario

Aplicación web para ver y editar el horario semanal. Es una PWA: se puede instalar desde el navegador y conserva la pantalla principal para usarla sin conexión después de la primera visita.

## Publicar en GitHub Pages

1. En GitHub, abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
4. Abre la URL que GitHub Pages muestra en esa página. Para este repositorio normalmente será `https://rvrddev.github.io/kora_rvrddev/`.

GitHub Pages sirve el sitio con HTTPS, requisito para que el navegador permita instalarlo y usar el service worker. Si se cambia la rama o la carpeta publicada, hay que conservar juntos `index.html`, `manifest.json`, `sw.js`, `horario.json` y los dos iconos.

## Instalar

- **Android o escritorio:** abre el sitio publicado en Chrome o en un navegador compatible, toca **Opciones → Instalar aplicación**. También se puede usar la opción de instalación del menú del navegador.
- **iPhone o iPad:** abre el sitio en Safari, toca **Compartir → Agregar a pantalla de inicio**.

La primera visita debe completarse con conexión para guardar los recursos de la aplicación. Los cambios al horario se guardan en el almacenamiento local del dispositivo; exporta el JSON desde **Opciones → Descargar JSON** para trasladar o respaldar tus cambios.
