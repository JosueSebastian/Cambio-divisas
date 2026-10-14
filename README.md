# Cambio de Divisas

Convertidor de divisas que funciona en el navegador, sin instalar nada. Escribes en cualquiera de las dos casillas y la otra se calcula sola.

- Cualquier par de monedas, con las tasas del Banco Central Europeo (a través de la API gratuita [Frankfurter](https://frankfurter.dev)).
- Gráfica de los últimos 30 días y dos relojes con selector de país.
- Recuerda tus últimas monedas y cantidad en tu propio dispositivo.
- Se puede instalar como app en el móvil.

## Cómo publicarlo con GitHub Pages (gratis)

1. Crea un repositorio **público** en GitHub (por ejemplo, `cambio-divisas`).
2. Pulsa *Add file > Upload files* y arrastra todos los archivos de esta carpeta (`index.html`, `manifest.json`, `sw.js` y los iconos). Pulsa *Commit changes*.
3. Ve a *Settings > Pages*. En *Build and deployment*, elige *Deploy from a branch*, rama `main` y carpeta `/ (root)`, y guarda.
4. Espera uno o dos minutos. Tu página estará en `https://TU-USUARIO.github.io/cambio-divisas/`. Ese enlace es el que compartes con tus amigos.

Los nombres de los menús de GitHub pueden cambiar un poco con el tiempo, pero el proceso es ese.

## Instalarlo en el móvil

- **iPhone (Safari):** botón Compartir, *Añadir a pantalla de inicio*.
- **Android (Chrome):** menú de los tres puntos, *Instalar aplicación* o *Añadir a pantalla de inicio*.

## Notas

- Necesita conexión para cargar las tasas. Las tasas del BCE se publican una vez por día laborable, no en tiempo real.
- Para probarlo en tu ordenador, abre `index.html` con doble clic (la instalación como app solo funciona desde la dirección publicada con https).
- Crédito del fondo: Katsushika Hokusai, *La gran ola de Kanagawa* (dominio público).
