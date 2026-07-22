# Betancourt Building Miami — Sitio Web

Sitio de una sola página para Betancourt Building Miami, contratista de pérgolas,
cocinas exteriores, cercas, decks y driveways en Miami. Basado en el perfil de
Instagram @betancourt_building_miami (11.2K seguidores, 164 posts).

Este proyecto reutiliza el mismo diseño, estructura, código, repo y deploy que
originalmente se construyeron para **Yela Pérgolas** → **Titan Outdoor Living**.
Por instrucción explícita del usuario, se mantuvo el diseño/estructura/fotos
intactos y solo se cambió la información del negocio (mismo repo, no uno nuevo).

- **Register:** brand / marketing (landing page de negocio local).
- **Idioma:** español por defecto, con toggle a inglés.
- **Contacto principal:** WhatsApp (+1 786-821-8275).
- **Área de servicio:** Miami y áreas circundantes.
- **Identidad visual:** paleta Azul Petróleo & Coral, blanco predominante (heredada de Yela/Titan).
- **Tipografía:** Fraunces (display) + Inter (body).
- **Puerto de preview:** 3462 (`titan-outdoor-living` en `.claude/launch.json` — nombre interno del launch config sin cambiar).
- **Repo:** https://github.com/arodrod00/titan-outdoor-living (mismo historial de commits; nombre del repo sin cambiar, pendiente si se decide renombrar).
- **Proyecto de Vercel:** renombrado de `titan-outdoor-living` → `betancourt-building-miami` (2026-07-22).
- **Producción:** https://betancourtbuildingmiami.vercel.app (única URL activa; `betancourt-building-miami.vercel.app` con guiones no estaba disponible — ya en uso por otra cuenta de Vercel). El alias anterior **titan-outdoor-living.vercel.app** se eliminó a pedido del usuario (2026-07-22) — ahora da 404.
- **Hero:** mismo video de fondo (`hero.mp4`) heredado de Yela/Titan — contenido
  genérico no atribuible a ninguna marca específica, se mantuvo sin cambios.
- **Galería:** misma funcionalidad interactiva (slider antes/después, filtros por
  categoría, lightbox) y las mismas fotos de stock ya usadas en Yela/Titan —
  no se sustituyeron por fotos reales de Betancourt (el usuario solo compartió
  un screenshot del perfil de Instagram, no archivos descargables).

## Cambios de contenido vs. la versión Titan Outdoor Living (2026-07-22)
- Nombre de marca: Titan Outdoor Living → Betancourt Building Miami.
- Se removió la mención a "Marco Paulin" (líder nombrado de Titan) — no se
  conoce el nombre del/los dueño(s) de Betancourt, así que "Nosotros" habla del
  negocio en general, sin atribuir a una persona específica.
- Área de servicio: "todo el sur de la Florida" → "Miami y áreas circundantes"
  (Betancourt se presenta como negocio de Miami específicamente).
- Servicios reordenados/renombrados para reflejar las especialidades reales de
  Betancourt (bio de Instagram: "Especialistas en pergolas y cocinas de
  exterior"; Linktree/Facebook: "Fences / Decks / Driveways / Pergolas"):
  - Pérgolas con Techo Insulado (se mantiene, coincide con las fotos existentes)
  - Pérgolas de Aluminio (sin cambios)
  - **Cocinas Exteriores** (antes "Remodelación de Terrazas") — especialidad
    confirmada en el bio de Instagram.
  - **Cercas** (antes "Mallas y Aluminio Estructural") — confirmado en Linktree/Facebook.
  - **Decks y Driveways** (antes "Cielos de Aluminio Estilo Madera") — confirmado en Linktree/Facebook.
  - Antes y Después (sin cambios, enlaza a galería).
- Sección "Por Qué Elegirnos": se reemplazó "Múltiples estilos" por
  **"Financiamiento Disponible"**, ya que el bio de Instagram destaca
  explícitamente "Hacemos financiamiento y cobros con tarjeta" — un
  diferenciador real que no existía en la versión Titan.
- Sección "Reseñas": Titan (negocio nuevo) invitaba a "seguir los primeros
  proyectos"; Betancourt ya tiene 11.2K seguidores en Instagram, así que ahora
  cita esa cifra en vez de una afirmación de "negocio nuevo".
- Formulario de cotización: opciones de servicio actualizadas a Pérgola /
  Cocina Exterior / Cerca / Deck-Driveway / Otro.

## Pendiente / a confirmar con el cliente
- **Teléfono:** se confirmó usar **786-821-8275** (el del screenshot de
  Instagram que compartió el usuario), pese a que una búsqueda web del
  Linktree de Betancourt mostró 786-621-8275 (un dígito distinto). Decisión
  explícita del usuario (2026-07-22): usar el del screenshot "de momento" —
  revisar de nuevo si el cliente confirma un número distinto más adelante.
- Horario de atención: se mantuvo "Lunes – Sábado 8am–6pm" por convención del
  sitio original (Yela/Titan) — no confirmado con Betancourt Building Miami.
- Fotos reales: la galería sigue usando las fotos de stock heredadas de
  Yela/Titan. Si se quiere usar fotos reales de los proyectos de Betancourt
  (visibles en su Instagram), hay que descargarlas y reemplazar los archivos
  en `images/` (mismos nombres de archivo, mismo patrón `photo-frame`).
- Dominio: `betancourtbuildingmiami.com` existe pero está "en mantenimiento"
  según su Linktree — no hay sitio en vivo con el que contrastar contenido.
- Nombre del/los dueño(s): no confirmado (el perfil de Instagram muestra dos
  personas en la foto, posiblemente socios/familia Betancourt).
