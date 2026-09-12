# Arquitectura — Simulador Monte Carlo

Simulación Monte Carlo sobre un modelo de Excel, en el navegador: entradas con distribuciones y correlación, Latin Hypercube, tornado, Sobol, punto de equilibrio, procesos estocásticos; informe con percentiles y VaR. Público en montecarlo.inicon.com.co.

**Diagrama interactivo:** [docs/arquitectura/arquitectura.html](docs/arquitectura/arquitectura.html)
(abrir con doble clic; tema claro/oscuro, vistas guiadas, exportar PNG/SVG).
**Fuente del diagrama:** [docs/arquitectura/arquitectura.architecture.json](docs/arquitectura/arquitectura.architecture.json).

## Cómo actualizarlo

El diagrama se genera con [Archify](https://github.com/tt-a1i/archify) a partir del JSON. Tras cambiar la
arquitectura, editar el JSON y regenerar:

```bash
node ~/.agents/skills/archify/bin/archify.mjs deliver architecture docs/arquitectura/arquitectura.architecture.json docs/arquitectura/arquitectura.html --quality showcase
```

Generado el 2026-09-12 con Claude Code, a partir de la lectura del código de este repositorio.
