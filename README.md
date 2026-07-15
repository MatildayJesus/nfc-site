# Mis tags NFC

Plantilla lista para colgar imágenes y sonidos en GitHub Pages y acceder a ellos con tags NFC.

## 1. Subir esto a GitHub

1. Crea una cuenta en https://github.com si no tienes.
2. Crea un repositorio nuevo (por ejemplo `nfc-site`), público.
3. Sube TODOS los archivos y carpetas de este paquete al repositorio
   (botón "Add file" → "Upload files", arrastra todo).
4. Ve a **Settings → Pages** del repositorio.
5. En "Branch" elige `main` y carpeta `/ (root)`, guarda.
6. En un par de minutos tu sitio estará en:
   `https://TU-USUARIO.github.io/nfc-site/`

## 2. Añadir tus propias imágenes y sonidos

Por cada imagen o sonido nuevo:

1. Sube el archivo a `assets/images/` o `assets/sounds/`.
2. Copia `items/foto1.html` o `items/sonido1.html`, renómbralo
   (ej. `foto2.html`) y cambia la ruta del `src` al nombre de tu archivo.
3. (Opcional) añade un enlace en `index.html` para verlo también desde la web.

## 3. Grabar los tags NFC

1. Instala la app **NFC Tools** (Android / iOS, gratis).
2. Pulsa "Escribir" → "Añadir un registro" → "URL/URI".
3. Pega la URL de la página del ítem, por ejemplo:
   `https://TU-USUARIO.github.io/nfc-site/items/foto1.html`
4. Pulsa "Escribir" y acerca el tag NFC al móvil.

Listo: al acercar el móvil al tag, se abrirá el navegador directo en esa
imagen o sonido.

## Notas

- Los nombres de archivo no deben llevar espacios ni tildes (usa `foto1.jpg`, no `foto 1.jpg`).
- El audio no siempre se reproduce automáticamente por restricciones del
  navegador; por eso la página de sonido incluye un botón "Reproducir".
- GitHub Pages es gratis y no tiene límite de tráfico razonable para uso personal.
