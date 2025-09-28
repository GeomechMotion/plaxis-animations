# GeomechMotion – PLAXIS (Hyde)

Paquete listo para GitHub Pages con el tema **Hyde**.

## Publicar
1) Subí este contenido al repo `plaxis-animations` (branch `main`).  
2) **Settings → Pages → Deploy from branch** (`main` / `/ (root)`).  
3) Abrí `https://geomechmotion.github.io/plaxis-animations/`.

## Editar
- `_config.yml`: título, descripción, `url`, `baseurl`.
- `_layouts/default.html`: paleta (`theme-base-0d`) y sidebar derecha (`layout-reverse`).
- `_data/videos.yml`: tus videos (MP4/WebM o `embed:`).
- `assets/posters/`: miniaturas (jpg/png).
- `assets/videos/`: tus MP4/WebM (clips chicos; para pesados, usá Releases).

## Notas
- Si usás rutas locales (empiezan con `/`), ya usamos `| relative_url` en la galería para que funcionen con `baseurl`.
