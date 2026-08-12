# Caja de chats

Componente de UI tipo chat (burbujas de mensaje + input de escritura), hecho solo con HTML y CSS.

## Qué practica

- Variables CSS (`--dark-color`, `--bg-color`) combinadas con `color-mix()` para generar variantes de un mismo color sin escribirlas a mano.
- Pseudo-elemento `::before` + `clip-path` para dibujar la "colita" del globo de chat.
- `flex-direction: column` para apilar mensajes y `margin-left: auto` para alinear los propios a la derecha.
- Estados de interacción (`:hover`, `:focus`, `:active`) en los botones de emoji y enviar.
- Iconos de Google Material Symbols vía `<link>` en el `<head>`.

## Cómo verlo

Abre `index.html` en el navegador, no requiere servidor ni instalación.

## Ideas pendientes

- [ ] Auto-scroll al último mensaje.
- [ ] Indicador de "escribiendo..." animado con CSS puro.
- [ ] `overflow-y: auto` en `.chat__content` con altura máxima fija.
