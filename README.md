# usainbluntmx.xyz — Ricardo Fuentes

Sitio personal de Ricardo “Richi” Fuentes. HTML, CSS y un poco de JavaScript; sin framework, sin build step.

## Páginas

- `index.html` — español (canonical `https://usainbluntmx.xyz/`)
- `en.html` — inglés (canonical `https://usainbluntmx.xyz/en.html`)
- `og.png` — tarjeta social en español (1200×630)
- `og-en.png` — tarjeta social en inglés (1200×630)

El selector ES/EN está en la barra superior y apunta entre las dos páginas. Ambas declaran `hreflang`, `og:locale` y contenido estático; no hay i18n en JavaScript.

## Diseño

Sistema **Bodega**: concreto (`#D7D4CC`), acero (`#121212`), amarillo de seguridad (`#F2C200`) y papel (`#FCFBF7`). Archivo variable + IBM Plex Mono, ambos embebidos en el HTML para no depender de Google Fonts.

La página se lee como un almacén: manifiesto de piezas, ficha, libro de trabajo. El retrato no se usa; la foto anterior era una imagen generada con marca de agua.

## Deploy

Dokploy. Un push a `main` reconstruye y publica. No hay Vercel ni GitHub Pages.

## Archivos que no se tocan

- `richi-profile.png` — imagen legada; no se referencia desde las páginas nuevas.
- `.gitignore`

## Verificación

Las dos páginas se midieron en 1440, 1024, 820, 768 y 390 px: sin scroll horizontal, texto mínimo de 11 px, taps de 44 px, contraste AA. Los enlaces externos se comprobaron con `curl` (200 o páginas que bloquean bots pero existen).
