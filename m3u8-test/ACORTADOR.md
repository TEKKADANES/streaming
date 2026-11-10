# Acortador sencillo de enlaces

Abre `acortador.html` en un navegador moderno. Introduce una URL HTTP/HTTPS, opcionalmente un alias de letras, números y guiones, y pulsa **Acortar enlace**.

La página no tiene servidor propio. Envía la URL y el alias a la API de is.gd, un proveedor externo, para crear un enlace público. Si el navegador impide leer la respuesta por CORS o conectividad, la app ofrece abrir la solicitud en otra pestaña. Comprueba el resultado y el destino antes de compartir. No introduzcas datos privados ni enlaces con credenciales.

Para acortar una lista M3U/M3U8, primero publica el archivo en una URL accesible (por ejemplo, la URL raw de un repositorio público) y pega esa dirección en el acortador. El acortador no aloja ni altera la lista.

La app se puede publicar con GitHub Pages junto al resto de archivos de `m3u8-test`; habilita Pages en **Settings → Pages** para obtener la dirección del sitio.
