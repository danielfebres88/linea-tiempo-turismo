# Línea del tiempo · Ocio y Turismo en la Edad Antigua (Grecia y Roma)

Página web (una sola página) para la Maestría en Planificación y Gestión del Turismo — Teoría del Turismo.
Incluye: los 7 hitos, contexto social/económico de cada civilización, un mapa interactivo, galería
de imágenes ampliables, animaciones al hacer scroll, filtro Grecia/Roma y conexión con las lecturas del curso.

## Contenido de la carpeta

```
index.html            → la página
assets/img/           → las imágenes (ya incluidas)
README.md             → este archivo
```

Las imágenes van **dentro** del proyecto (no dependen de enlaces externos). El único contenido
que se carga de internet son: el video de Baiae (YouTube), el mapa (OpenStreetMap) y las
librerías visuales (animaciones, galería) desde su CDN. Todo eso funciona sin configurar nada.

## Cómo publicarlo en GitHub Pages (paso a paso)

1. Entra a https://github.com e inicia sesión (o crea una cuenta gratis).
2. Arriba a la derecha, **+ → New repository**. Ponle un nombre, por ejemplo `linea-tiempo-turismo`.
   Déjalo **Public** y crea el repositorio.
3. En la página del repositorio nuevo, haz clic en **“uploading an existing file”**
   (o **Add file → Upload files**).
4. Arrastra **el contenido de esta carpeta**: el archivo `index.html`, la carpeta `assets`
   (con `assets/img/…`) y el `README.md`. Importante: que `index.html` quede en la **raíz** del
   repositorio, no dentro de otra carpeta.
5. Abajo, escribe un mensaje (“primera versión”) y pulsa **Commit changes**.
6. Ve a **Settings** (ajustes del repo) → en el menú izquierdo, **Pages**.
7. En **Build and deployment → Source**, elige **Deploy from a branch**.
   En **Branch** selecciona **main** y carpeta **/ (root)**, y pulsa **Save**.
8. Espera 1–2 minutos y recarga esa página de Pages: aparecerá el enlace público, del tipo
   `https://TU-USUARIO.github.io/linea-tiempo-turismo/`.
9. Ese enlace es el que subes al aula virtual. ✅

> Consejo: para verlo antes de publicar, puedes abrir `index.html` con doble clic en tu
> computador (con internet). El mapa, el video y las animaciones necesitan conexión.

## Cómo editarlo

- Los textos están en `index.html` (busca cada tarjeta por su título).
- Para cambiar una imagen, reemplaza el archivo dentro de `assets/img/` manteniendo el mismo nombre.
- Los colores están al inicio de `index.html`, en el bloque `:root { ... }`.

## Créditos

Imágenes: Wikimedia Commons (Creative Commons / dominio público). Video: YouTube.
Mapa: © OpenStreetMap. Librerías: AOS, GLightbox y Leaflet (código abierto vía CDN).
