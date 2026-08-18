# Changelog

Todas las modificaciones relevantes del skill.

## [1.2.0] — 2026-08-18

### Cambiado
- **Todas las instrucciones internas traducidas al inglés** (`SKILL.md`, `agentes.md`, `estructura-reporte.md`, `ejemplos.md`), por consistencia con el ecosistema de Agent Skills y para abrir el repo a contribuidores internacionales.

### Añadido
- **Regla de Language Lock** en `SKILL.md`, marcada como de máxima prioridad: el reporte se escribe siempre en el idioma del perfil del usuario, nunca en el de las instrucciones. Incluye tabla de encabezados canónicos ES/EN.
- **Glosario de etiquetas ES** en `estructura-reporte.md`: 25+ etiquetas de sección para que el reporte en español salga idéntico a la versión anterior, sin traducciones improvisadas.
- Avisos de idioma al inicio de cada archivo de `references/`.
- **Caso L** en `ejemplos.md`: qué hacer si el idioma de las instrucciones se filtra al output.

## [1.1.0] — 2026-08-18

### Añadido
- Sección **7. Higiene del Perfil** en el reporte: foto, banner, URL personalizada, Open to Work, idiomas, certificaciones y validaciones.
- Sección **8. Plan de Acción**: máximo 3 acciones priorizadas por impacto sobre el objetivo declarado.
- Tabla de **límites reales de LinkedIn** en `SKILL.md` (220 / 2.600 / 2.000 / 80 caracteres) y regla obligatoria de **front-loading**: rol y valor en los primeros ~70 caracteres del titular, gancho autónomo en los primeros ~300 del About.
- **Rúbrica de puntuación** en `agentes.md`: 5 dimensiones × bandas 0–3 con descriptores y factores de peso, más una verificación de coherencia score ↔ gaps.
- Contadores de caracteres visibles en la plantilla del reporte.
- Casos H–K en `ejemplos.md`: perfil sin métricas, ronda única de preguntas, perfil bilingüe, titular mal front-loaded.
- Regla de no reproducir datos de contacto personales del PDF en el reporte.
- Campo `license` en el frontmatter del skill.

### Corregido
- `references/ejemplos.md` **no estaba referenciado desde `SKILL.md`**, por lo que nunca se cargaba. Ahora se enlaza explícitamente.
- **Contradicción entre "About con prueba social con métricas" y la regla anti-invención.** Se define la vía de salida: evidencia cualitativa verificable + registrar la ausencia de métricas como gap prioritario.
- **Flujo de preguntas en varias rondas.** El Paso 1 ahora obliga a leer el material primero y consolidar contexto, ambigüedades y cobertura faltante en un único mensaje.
- **Regla de idioma frágil** ante perfiles bilingües: ahora se pregunta solo si el perfil mezcla idiomas.
- Enlace de instalación del README que apuntaba a una página de Releases vacía.
- Se elimina el mínimo rígido de 200 palabras del About, que empujaba al relleno y chocaba con la regla anti-invención. Se sustituye por un rango recomendado de 200–350 palabras con techo de 2.600 caracteres.
- `description` del frontmatter condensada (~740 → ~440 caracteres) sin perder disparadores.

## [1.0.0]
- Versión inicial: sistema multi-agente, cuestionario de contexto, regla anti-invención y reporte de 6 secciones.