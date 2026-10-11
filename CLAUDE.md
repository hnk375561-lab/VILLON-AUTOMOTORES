# Guía de mantenimiento · Automotores Villon

1. **Cero datos inventados.** Horarios, precios, marcas, servicios y antigüedad solo se cargan con confirmación escrita del dueño o fuente pública citada. Si falta, el dato no se publica.
2. **Todo dato nuevo se registra** en `golive/AFIRMACIONES-A-CONFIRMAR.md` con fuente y fecha, y se refleja en `data/dealership.json`.
3. Los datos del negocio viven en `data/dealership.json` **y** en el bloque `NEGOCIO` de `index.html`; deben coincidir (`npm test`). `404.html`, `privacidad.html` y `reserva.html` (`CONFIG.whatsapp` en `js/reserva.js`) repiten WhatsApp y teléfono: si cambian, actualizarlos también.
4. Cambio mínimo: no reescribir secciones enteras. No cargar datos personales del dueño ni de su familia ni de empleados.
5. Mientras sea demo: `publicIndexing: false`, `noindex, nofollow` en las 4 páginas, `Disallow: /` en `robots.txt` y aviso de propuesta no oficial.
6. Los archivos internos (`golive/`, `data/`, `docs/`, `scripts/`) no se publican (ver `netlify.toml`).
7. Conflictos entre fuentes viven en `data/sources.json`. No se resuelven por cuenta propia: el sitio no muestra el dato.
8. Fotos y videos solo con autorización documentada.
