# Zener Soluciones — Landing

Landing page de una sola sección para captar clientes y derivarlos a WhatsApp.

## Estructura

```
index.html      → estructura y contenido
css/styles.css  → estilos (mobile-first, con variables de diseño)
js/script.js    → animaciones al scrollear (sin dependencias)
```

## Cómo publicarla (GitHub Pages)

1. Subí esta carpeta a un repositorio en GitHub.
2. En el repo: **Settings → Pages → Source**, elegí la rama principal (`main`) y carpeta `/root`.
3. GitHub va a publicar el sitio en `https://tu-usuario.github.io/nombre-repo/`.

## Antes de publicar, revisá:

- **Número de WhatsApp**: está como `https://wa.me/5491170246803` en `index.html` (header, hero, CTA final, footer y botón flotante). Si el número o el prefijo (54 9 = Argentina móvil) no es correcto, buscá y reemplazá esas apariciones.
- **Teléfono para llamar**: `tel:+541170246803`.
- **Textos de servicios**: ajustá precios o aclaraciones si querés sumarlas.

## Stack

- HTML + CSS + JS puro, sin frameworks ni build step.
- Tipografías: [Archivo Black](https://fonts.google.com/specimen/Archivo+Black) (títulos) e [Inter](https://fonts.google.com/specimen/Inter) (texto), cargadas desde Google Fonts.
