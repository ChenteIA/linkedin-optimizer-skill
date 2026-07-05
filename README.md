# 🚀 LinkedIn Optimizer — Skill para Claude

<p align="center">
  <img src="./assets/banner.svg" alt="LinkedIn Optimizer — Claude Skill by ChenteIA" width="100%">
</p>

<h1 align="center">🚀 LinkedIn Optimizer — Skill para Claude</h1>

<p align="center">
  Auditoría y optimización completa de perfiles de LinkedIn con un sistema multi-agente de IA.<br>
  Creado por <a href="https://github.com/ChenteIA"><b>ChenteIA</b></a> 🇵🇪 · Universidad Nacional San Luis Gonzaga de Ica
</p>

> Auditoría y optimización completa de perfiles de LinkedIn con un sistema multi-agente de IA.
> Creado por **[ChenteIA](https://github.com/ChenteIA)** 🇵🇪 · Universidad Nacional San Luis Gonzaga de Ica

![Claude Skill](https://img.shields.io/badge/Claude-Skill-8A63D2)
![Idioma](https://img.shields.io/badge/idioma-multiidioma-blue)
![Licencia](https://img.shields.io/badge/licencia-MIT-green)

---

## ¿Qué hace?

Convierte a Claude en un **Lead LinkedIn Optimizer**: subes tu perfil de LinkedIn (PDF exportado, capturas de pantalla, o ambos) y recibes un reporte accionable con textos **listos para copiar y pegar**:

| Sección | Qué obtienes |
|---|---|
| 📊 Diagnóstico Estratégico | Score global, objetivo, ICP, gaps y fortalezas |
| ✍️ Titular (Headline) | Versión optimizada con keywords SEO, máx. 220 caracteres |
| 📖 Acerca de (About) | Reescritura completa con hook, valor, prueba social y CTA |
| 💼 Experiencia | Descripción con métricas de impacto y keywords técnicas |
| ⭐ Destacados y Skills | Top 3 skills + keywords ATS + propuestas de Featured |
| 🤝 Recomendaciones | Guión de DM personalizado para pedir recomendaciones |

## 🤖 Sistema multi-agente

El análisis lo hacen 3 agentes virtuales internos, consolidados por un Lead Optimizer:

- 🕵️‍♂️ **Headhunter Senior** — evalúa el perfil como lo haría un reclutador en 8 segundos
- ✍️ **Copywriter B2B** — redacta los textos optimizados (persuasión, métricas, SEO)
- 🧠 **Estratega de Autoridad** — define el posicionamiento y la prueba social

## ✨ Características

- ✅ **Multiidioma** — el reporte sale en el idioma de tu perfil
- ✅ **Multi-formato** — acepta PDF de LinkedIn, capturas de pantalla, o ambos
- ✅ **Cuestionario previo** — pregunta tu objetivo real antes de auditar (empleo, clientes, marca personal, networking, becas, inversionistas... el que sea)
- ✅ **Cero invenciones** — si un dato es ambiguo o falta, te pregunta en vez de inventarlo
- ✅ **Objetivo abierto** — todo el reporte se adapta a *tu* meta, no a un molde genérico

## 📦 Instalación

### En Claude.ai

1. Descarga el archivo [`linkedin-optimizer.skill`](../../releases) (o empaquétalo tú mismo, ver abajo)
2. Súbelo a un chat de Claude
3. Haz clic en **"Save skill"** en la tarjeta del archivo

### Empaquetar desde el código fuente

```bash
# El .skill es un zip con la carpeta del skill dentro
cd linkedin-optimizer-repo
zip -r linkedin-optimizer.skill linkedin-optimizer/
```

## 🎯 Uso

1. Descarga tu perfil desde LinkedIn: **Perfil → "Recursos" → "Guardar en PDF"** (o toma capturas de pantalla)
2. En Claude, escribe algo como: *"Optimiza mi LinkedIn"* y adjunta el archivo
3. Responde el cuestionario corto (objetivo, puesto al que apuntas, audiencia)
4. Recibe tu reporte completo — copia y pega los textos directamente en LinkedIn

## 📂 Estructura del proyecto

```
linkedin-optimizer/
├── SKILL.md                          # Instrucciones core del skill
└── references/
    ├── agentes.md                    # Criterios de los 3 agentes
    ├── estructura-reporte.md         # Plantilla exacta del reporte
    └── ejemplos.md                   # Casos de flujo esperado
```

## 🤝 Contribuir

¿Ideas para mejorar el skill? Abre un issue o un pull request. Algunas ideas en el roadmap:

- [ ] Análisis comparativo contra perfiles top del mismo sector
- [ ] Modo "antes/después" con score proyectado
- [ ] Soporte para páginas de empresa

## 📄 Licencia

MIT — úsalo, modifícalo y compártelo libremente. Ver [LICENSE](LICENSE).

---

Hecho con 💙 por **ChenteIA** — datos, ML y decisiones basadas en evidencia.
