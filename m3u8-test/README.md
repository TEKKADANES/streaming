# Creador de listas M3U para YouTube

Herramienta educativa estática que permite añadir enlaces públicos de YouTube y generar o descargar una lista `.m3u` directamente en el navegador.

## Uso

Abre `index.html` en un navegador moderno. Añade un enlace a la vez o pega varios (uno por línea); para indicar títulos, usa `Título | URL`. Genera la lista y descárgala como `lista-videos.m3u`.

La aplicación no necesita servidor, dependencias, ni envía los enlaces a ningún servicio. Para compartir una lista como archivo raw, publica el `.m3u` descargado en un repositorio público y comparte su URL `raw.githubusercontent.com`.

## Compatibilidad y permisos

La lista contiene las direcciones de las páginas de YouTube, no las direcciones directas de los flujos de video. Por eso, que un reproductor pueda abrirla depende de su compatibilidad con YouTube y puede cambiar. La aplicación no descarga, convierte ni retransmite videos. Utiliza únicamente videos propios o para los que tengas permiso y considera las reglas escolares y las condiciones de YouTube.

## Publicación

El archivo está en `m3u8-test/index.html`. Para servir la aplicación como sitio web, configura GitHub Pages para publicar desde la rama `main` y la carpeta `/ (root)` del repositorio; como alternativa, mueve/copia el archivo a la raíz del sitio publicado. La URL de GitHub Pages aparecerá en **Settings → Pages** cuando la publicación esté habilitada.
