# Carbón Apunto: web institucional

**El dueño de las brasas.** Sitio estático (HTML, CSS y JavaScript, sin compilación) publicado en Vercel.

## Archivos

- `index.html`: contenido de todas las secciones (Inicio, Nosotros, Productos, Clientes, Mayoristas, Contacto).
- `styles.css`: diseño (colores en `:root`, al principio del archivo).
- `script.js`: menú del celular, animaciones y formulario que abre WhatsApp.
- `img/`: fotos y videos.

## Cómo reemplazar un recuadro gris por una foto o video

Cada `<div class="media-ph" data-label="..."></div>` es un lugar reservado. Reemplazalo por:

```html
<img class="media" src="img/mi-foto.jpg" alt="Descripción de la foto">
<video class="media" src="img/mi-video.mp4" autoplay muted loop playsinline></video>
```

## Verlo en tu compu

Abrí `index.html` en el navegador.

## Publicación

Vercel publica automáticamente cada cambio que se sube a la rama `main`.
