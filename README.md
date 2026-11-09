# Polifilm, S.A. — Sitio web moderno

Sitio estático (HTML/CSS/JS) con animaciones de scroll, parallax y rollo 3D.

## Estructura
- `index.html` — página principal
- `img/` — imágenes (nombres en minúsculas para compatibilidad con GitHub Pages)
- `fonts/` y `fonts.css` — tipografías locales (funciona offline)
- `.nojekyll` — desactiva Jekyll en GitHub Pages

## Publicar en GitHub Pages
1. Sube **todo el contenido de esta carpeta** (incluyendo `img/`, `fonts/`, `.nojekyll`) a la raíz del repositorio.
2. En el repositorio: Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / root.
3. Espera ~1 minuto; el sitio estará en `https://<usuario>.github.io/<repo>/`.

> Importante: sube la carpeta `img/` completa; si solo subes `index.html`, las fotos no aparecerán.
