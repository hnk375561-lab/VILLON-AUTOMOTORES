# Automotores Villon · demo

Propuesta de sitio web para Automotores Villon (Villa Elisa, Entre Ríos). **Demo no oficial**: no está indexada y los datos no confirmados por el dueño no se publican.

Base técnica: sitio estático (HTML/CSS/JS) derivado de un proyecto anterior. Las unidades que se ven son de muestra.

## Comandos
- `npm install` · una vez.
- `npm run dev` · servidor local en http://localhost:8080
- `npm run prerender && npm test` · después de cada cambio en `STOCK` o `NEGOCIO`.
- `npm run audit` · lista afirmaciones que prometen servicios.
- `npm run images -- <slug> <carpeta>` · variantes de fotos de una unidad.
- `node scripts/build-site.mjs` · genera `_site/` para publicar.

Reglas de mantenimiento en `CLAUDE.md`.
