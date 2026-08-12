# Página animada (portafolio)

One-page tipo portafolio personal: perfil, sección de portfolio y formulario de contacto, con animaciones activadas por scroll.

## Qué practica

- **Scroll-driven animations nativas** (`animation-timeline: scroll()` y `animation-timeline: view()`) sin ninguna librería JS — el header cambia de color al hacer scroll y las secciones aparecen con fade-in al entrar en pantalla.
- **Container queries** (`container-type: inline-size` + `@container`) para que cada sección (perfil, portfolio, formulario) sea responsive según su propio ancho, no el del viewport.
- **CSS Grid** con `grid-template-areas` para reordenar el formulario de contacto en pantallas grandes.
- Checkbox hack para el menú hamburguesa en móvil (`input:checked ~ .header__nav`).
- `text-wrap: balance` para que los títulos no corten mal en varias líneas.

## Cómo verlo

Abre `index.html` en un navegador reciente (Chrome/Edge 115+, o Safari 17.4+ para las scroll-driven animations).

## Ideas pendientes

- [ ] Reemplazar las tarjetas de "PROYECTO" vacías con proyectos reales.
- [ ] Conectar el formulario a un servicio como Formspree para que envíe correos de verdad.
- [ ] Modo oscuro con `prefers-color-scheme`.
