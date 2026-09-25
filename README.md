# Tecnocracia — Newsletter

Sitio estático (GitHub Pages + Jekyll) con las ediciones de Tecnocracia, la newsletter semanal de tecnología y derecho digital.

- Sitio: <https://tecnocracia.github.io/newsletter/>
- Las ediciones están en [`newsletters/`](newsletters/), numeradas en orden secuencial (N° 1 = más antigua, N° 9 = más reciente).
- [`index.md`](index.md) lista las ediciones de la más reciente a la más antigua.

## Publicar una nueva edición

1. Crear `newsletters/newsletter-NN.md` con front matter (`layout: default`, `title`, `permalink: /newsletters/newsletter-NN/`).
2. Agregar el enlace **al principio** de la lista en `index.md`.
3. Hacer push a `main`; GitHub Pages reconstruye el sitio automáticamente.
