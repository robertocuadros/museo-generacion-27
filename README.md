# Museo Virtual de la Generación del 27

Prototipo WebXR en A-Frame para una actividad paralela al Congreso de la Generación del 27 (Sevilla, 2027).

## Estructura
- `index.html`: primera sala, «Sevilla 1927».
- `assets/img/`: imágenes de la exposición.
- `assets/video/`: vídeos.
- `.nojekyll`: evita procesamiento innecesario en GitHub Pages.

## Sustituir imágenes
Reemplaza `foto-01.svg`, `foto-02.svg`, etc. por fotografías optimizadas (JPG/WebP) y actualiza las rutas en `index.html`.

## Publicación
Repositorio público en GitHub + Settings > Pages > Deploy from a branch > `main` / root.

## Objetivo técnico
Mantener el museo ligero, accesible desde navegador y divisible en varias salas independientes para no cargar las ~70 fotografías a la vez.
