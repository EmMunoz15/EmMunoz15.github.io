NEUROLAB — PLANTILLA DEL SITIO (Parcial N°1, Ingeniería Web)
=============================================================

ESTRUCTURA DE CARPETAS
-----------------------
/html   -> index.html, acerca.html, contacto.html
/css    -> styles.css (toda la hoja de estilos del sitio)
/js     -> script.js (menú móvil + validación y guardado del formulario)
/img    -> logo.svg y el gráfico decorativo de la red neuronal
/video  -> coloca aquí tu video real (ver punto 3)
/audio  -> coloca aquí tu audio real (ver punto 3)

IMPORTANTE: la indicación pide una carpeta primaria con los apellidos
de los 2 integrantes. Renombra esta carpeta antes de subirla a Teams,
por ejemplo: "Muñoz_Apellido2-Parcial1".

QUÉ REEMPLAZAR ANTES DE ENTREGAR
---------------------------------
Busca los comentarios "<!-- Reemplazar... -->" y los recuadros con la
X (los que dicen "Imagen") en cada página. Son las partes marcadas
como plantilla:

1. Textos: cambia los párrafos de ejemplo por información real y
   verificada sobre el tema asignado.

2. Imágenes: sustituye cada <div class="placeholder-img">...</div>
   por una etiqueta <img src="../img/tu-imagen.jpg" alt="..."> con tus
   propias imágenes guardadas dentro de /img.

3. Video y audio (página acerca.html): agrega tus archivos reales en
   /video y /audio, y actualiza el atributo "src" de las etiquetas
   <video> y <audio> con el nombre de tu archivo.

4. Redes sociales y enlaces: cambia los href="https://www.tiktok.com/"
   (y los de Instagram y X) por los perfiles reales, y ajusta el
   teléfono/correo de la página de contacto.

5. Mapa de Google (contacto.html): el recuadro grande ya tiene un
   mapa funcional de ejemplo (Universidad Tecnológica de Panamá).
   Para poner tu propia ubicación:
     a) Abre Google Maps y busca tu dirección real.
     b) Haz clic en "Compartir" → pestaña "Insertar un mapa".
     c) Copia el código <iframe ...>...</iframe> que te da Google.
     d) Pégalo dentro de <div class="map-frame"> reemplazando el
        <iframe> actual.
   (La forma rápida que ya está puesta, cambiando solo el texto
   después de "q=" en el src, también funciona si no quieres usar
   el paso a-c.)

SOBRE EL FORMULARIO DE CONTACTO
---------------------------------
El formulario valida en el navegador (nombre, apellido, correo,
teléfono, asunto y mensaje) y, al enviarse correctamente, guarda cada
registro en el almacenamiento local del navegador y descarga un
archivo "contactos.json" con los datos — así se cumple el punto de
"guardar los datos en un archivo de datos" sin necesitar un servidor.
Si tu profesora pide que se guarde en el servidor, deberás reemplazar
esa parte de /js/script.js por una petición (fetch) a un backend en
PHP, Node.js, etc.

TÉCNICA DE DISEÑO UTILIZADA
------------------------------
Wireframes de baja fidelidad (los que te compartieron) como base del
diseño. Recuerda mencionar esta técnica en tu entrega, como pide la
indicación 4 del parcial.

SUBIR A HOSTING GRATUITO
---------------------------
Servicios gratuitos donde puedes subir esta carpeta (o solo el
contenido de /html, /css, /img, /js) tal cual: Netlify Drop, GitHub
Pages o Vercel. Recuerda que index.html debe quedar accesible en la
raíz del sitio publicado.
