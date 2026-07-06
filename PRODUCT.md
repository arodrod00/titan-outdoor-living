# Yela Pérgolas — Sitio Web

Sitio de una sola página para Yela Pérgolas, contratista de Miami especializado en
terrazas insuladas y estructuras de aluminio (pérgolas, remodelaciones, mallas,
buzones a la medida). Basado en el perfil de Instagram @yelapergolas.

- **Register:** brand / marketing (landing page de negocio local).
- **Idioma:** español por defecto (audiencia primaria), con toggle a inglés.
- **Contacto principal:** WhatsApp (+1 786-790-2569), no llamadas ni formulario tradicional.
- **Identidad visual:** paleta ámbar/terracota + carbón cálido, tomada del logo real
  del negocio (círculo dorado sobre fondo oscuro). Deliberadamente distinta del azul/bronce
  usado en el sitio hermano AluminumLuxuryDecor (mismo nicho, mismo repo).
- **Tipografía:** Fraunces (display) + Inter (body).
- **Puerto de preview:** 3462 (`yela-pergolas` en `.claude/launch.json`).
- **Repo:** https://github.com/arodrod00/yela-pergolas (público)
- **Producción:** https://yela-pergolas.vercel.app (auto-deploy conectado al repo de GitHub, rama `master`)
- **Paleta actual:** Azul Petróleo & Coral, blanco predominante (petróleo solo en
  hero/footer/tarjeta de WhatsApp; el resto de secciones son claras).
- **Hero:** video de fondo (`hero.mp4`, cortesía Kling AI, 26.7MB tras optimizar —
  ver nota de video abajo), con overlay reforzado para legibilidad de texto.
- **Galería:** interactiva — slider de antes/después arrastrable (`#ba-slider`),
  filtros por categoría (Todos/Pérgolas/Terrazas/Detalles/Equipo) y lightbox con
  navegación por teclado/flechas. Todo funciona ya con los `photo-frame` placeholder;
  con solo colocar los archivos reales en `images/` con los nombres esperados se
  activan las fotos automáticamente (ver lista de nombres en el HTML, sección GALLERY).

## Nota sobre imágenes de referencia (2026-07-06)
El usuario compartió `C:\Users\a2adr\OneDrive\Desktop\yela` con fotos para la galería,
pero resultaron ser imágenes de stock / de otras marcas (incluye foto de producto de
"PurpleLeaf", un competidor). Por decisión del usuario, esas imágenes se usaron
**solo como referencia visual de estilo** (pérgolas de aluminio oscuro, minimalistas,
con piscina) y NO se publicaron en el sitio. La galería sigue con placeholders hasta
recibir fotos reales de proyectos de Yela Pérgolas.

## Nota sobre el video del hero (2026-07-06)
El video original (`kling_20260707_VIDEO_empieza_co_173_0.mp4`, 54.7MB, 4K portrait
2160×3840, bitrate ~43.5 Mbps) se optimizó con ffmpeg: audio removido (el video va
muted igual), reescalado a 1920px de ancho, recodificado en H.264 CRF 20 + faststart.
Resultado: 26.7MB (-51%) sin pérdida de calidad perceptible. Se generó también
`images/hero-poster.jpg` como poster de carga instantánea.

## Pendiente
- Reemplazar los `photo-frame` placeholder en `images/` con fotos reales del negocio.
- Confirmar horario real de atención y área de servicio exacta (se asumió Miami-Dade
  y L–S 8am–6pm por convención del sitio hermano; no confirmado con el cliente).
- Las reseñas ("Opiniones") enlazan a Instagram en vez de citar testimonios inventados.
