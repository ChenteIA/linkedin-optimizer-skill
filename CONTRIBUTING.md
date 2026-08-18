# Contribuir

Gracias por el interés. Este skill es texto: no hay build ni dependencias.

## Cómo proponer un cambio

1. Haz fork y crea una rama descriptiva (`fix/score-rubrica`, `feat/soporte-paginas-empresa`).
2. Edita los archivos bajo `linkedin-optimizer/`.
3. **Pruébalo antes del PR**: empaqueta y súbelo a un chat de Claude.
   ```bash
   zip -r linkedin-optimizer.skill linkedin-optimizer/
   ```
   Corre al menos un perfil real o ficticio de punta a punta y pega el output resultante en el PR.
4. Actualiza `CHANGELOG.md`.

## Reglas del proyecto

- **Nada de datos inventados.** Cualquier cambio que permita al modelo rellenar métricas, fechas o logros que no estén en el material del usuario será rechazado.
- **Todo archivo en `references/` debe estar referenciado desde `SKILL.md`.** Si no se enlaza, el modelo no lo lee y es peso muerto.
- **Los números de LinkedIn se citan con fuente y fecha.** Los límites de caracteres cambian; si actualizas uno, indica de dónde lo sacaste.
- **Reglas rígidas solo si tienen vía de escape.** Un mínimo obligatorio sin alternativa documentada empuja al modelo a rellenar con paja.
- Mantén el reporte en su estructura fija: si añades una sección, va a `estructura-reporte.md`, no como excepción suelta en `SKILL.md`.

## Reportar un problema

Abre un issue con: qué pediste, qué material subiste (sin datos personales), qué esperabas y qué salió.
