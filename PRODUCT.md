# Titan Outdoor Living — Sitio Web

Sitio de una sola página para Titan Outdoor Living, contratista de pérgolas y
estructuras de aluminio en el sur de la Florida (South Florida), liderado por
Marco Paulin. Basado en el perfil de Instagram @titan_outdoorliving.

Este proyecto reutiliza el mismo diseño, estructura, código, repo y deploy que
originalmente se construyeron para **Yela Pérgolas** (mismo nicho de negocio).
Por instrucción explícita del usuario, se mantuvo el diseño/estructura intactos
y solo se cambió la información del negocio (mismo repo renombrado, no uno nuevo).

- **Register:** brand / marketing (landing page de negocio local).
- **Idioma:** español por defecto, con toggle a inglés.
- **Contacto principal:** WhatsApp (+1 305-713-2450).
- **Área de servicio:** Todo el sur de la Florida (South Florida) — no limitado a
  Miami-Dade, a diferencia del sitio original de Yela Pérgolas.
- **Identidad visual:** paleta Azul Petróleo & Coral, blanco predominante (heredada de Yela).
- **Tipografía:** Fraunces (display) + Inter (body).
- **Puerto de preview:** 3462 (`titan-outdoor-living` en `.claude/launch.json`).
- **Repo:** https://github.com/arodrod00/titan-outdoor-living (renombrado desde `yela-pergolas`, mismo historial de commits)
- **Producción:** https://titan-outdoor-living.vercel.app (proyecto de Vercel renombrado desde `yela-pergolas`)
- **Hero:** mismo video de fondo (`hero.mp4`, 26.7MB optimizado) que Yela Pérgolas —
  contenido genérico no atribuible a ninguna de las dos marcas, se mantuvo sin cambios.
- **Galería:** misma funcionalidad interactiva (slider antes/después, filtros por
  categoría, lightbox) — ver detalle de fotos abajo.

## Diferencias de contenido importantes vs. la versión Yela Pérgolas (2026-07-06)
El Instagram de Titan Outdoor Living muestra un badge **"NEW"**, solo 8 posts y
10 seguidores — es un negocio nuevo. Por eso, a diferencia de Yela Pérgolas
(que sí afirma "+10 años de experiencia"), en este sitio **se removieron todas
las afirmaciones de años de experiencia y de reseñas de clientes**, ya que
serían falsas para un negocio recién creado. En su lugar:
- Los stats del hero y "Por qué elegirnos" usan afirmaciones honestas (100%
  aluminio, múltiples estilos de pérgola, cobertura en South Florida, respuesta
  en 24h) en vez de "años de experiencia".
- "Nosotros" menciona a Marco Paulin como líder del negocio, sin reclamar una
  década de trayectoria.
- La sección de "reseñas" invita a seguir el Instagram nuevo en vez de citar
  reseñas de clientes o mostrar un rating de estrellas inventado.
- El servicio "Buzones de Aluminio" (específico de Yela) se reemplazó por
  "Cielos de Aluminio Estilo Madera", que sí aparece en las fotos reales del
  Instagram de Titan (techos con acabado imitación madera).

## Fotos de la galería — pendiente
El usuario solo compartió un screenshot del perfil de Instagram de Titan (grid
de miniaturas), no archivos de foto individuales descargables. Por eso **la
galería y la sección "Nosotros" quedaron con placeholders** (mismo patrón
`photo-frame` con `data-label`) en vez de reutilizar las fotos de stock que se
habían usado para Yela Pérgolas — usar las mismas fotos de stock en dos sitios
de negocios reales distintos habría sido confuso/deshonesto si alguien comparara
ambos sitios.

Nombres de archivo esperados en `images/` (con solo copiarlos ahí se activan):
`gallery-lounge-night.jpg`, `gallery-patio-white.jpg`, `gallery-playground-cover.jpg`,
`gallery-team.jpg`, `gallery-mailbox.jpg`, `gallery-team-2.jpg`, `gallery-before.jpg`,
`gallery-after.jpg`, `gallery-project.jpg` (foto de "Nosotros").

## Pendiente
- Reemplazar los `photo-frame` placeholder en `images/` con fotos reales de
  proyectos de Titan Outdoor Living (idealmente descargadas directamente de
  Instagram, no solo el screenshot del perfil).
- Confirmar horario real de atención (se mantuvo L–S 8am–6pm por convención
  del sitio original; no confirmado con el cliente).
- Confirmar que el número +1 305-713-2450 tiene WhatsApp activo.
