---
layout: page
title: Acerca de
---

Este sitio recopila animaciones y videos usados en clases/presentaciones de geotecnia numérica (PLAXIS, FLAC, modelos constitutivos, FEM/FDM).

**Cómo agregar videos**
1. Subí tus MP4/WebM a `assets/videos/` o usá YouTube/Vimeo con `embed:`.
2. Agregá entradas en `_data/videos.yml`.
3. (Opcional) Subí una miniatura en `assets/posters/` y usá `poster:`.

**Sugerencias**
- MP4 H.264 (1080p), `-crf 22`, `-preset medium`, `-movflags +faststart`.
- Generá poster: `ffmpeg -i video.mp4 -ss 00:00:01 -vframes 1 assets/posters/mi_video.jpg`.
