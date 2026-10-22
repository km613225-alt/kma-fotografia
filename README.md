# Kevin Molina Fotografía

Portafolio web de Kevin Molina Antonio (KMA): fotografía de paisaje, cielo nocturno, retrato y eventos en la Ciudad de México.

Sitio publicado con GitHub Pages: https://km613225-alt.github.io/kma-fotografia/

## Qué incluye

- **Portafolio**: galería justificada con filtros por tema y visor a pantalla completa.
- **Antes y después**: comparador interactivo de fotos sin editar y editadas.
- **Guía gratuita**: *Domina tu Canon EOS R50* (PDF), se desbloquea al seguir @photographer_kma_ en Instagram.
- **Servicios**: precios de referencia, reserva con contrato y cotización por WhatsApp.
- **Contacto**: correo, teléfono, WhatsApp e Instagram.

## Estructura

```
index.html            Página completa (HTML, CSS y JavaScript en un solo archivo)
404.html              Página para enlaces rotos
fotos/                Fotos completas con marca de agua (se usan en el visor)
fotos/t/              Miniaturas ligeras para la galería
fotos/antes-*.webp    Versiones sin editar para el antes y después
guia/                 PDF de la guía gratuita
fuentes/              Tipografías Jost y Cormorant Garamond (licencia SIL Open Font License)
og-image.jpg          Imagen que aparece al compartir el enlace en WhatsApp, Instagram o Facebook
favicon.svg, favicon-32.png, apple-touch-icon.png   Íconos del sitio
robots.txt, sitemap.xml                             Para que Google encuentre la página
```

## Cómo cambiar cosas comunes

- **Agregar o quitar fotos de la galería**: edita la lista `PHOTOS` dentro de `index.html` y sube la foto a `fotos/` y su miniatura a `fotos/t/`.
- **Cambiar precios o servicios**: busca la sección `id="servicios"` en `index.html`.
- **Cambiar el Instagram**: busca `photographer_kma_` en `index.html`.

## Dominio propio

1. Compra el dominio (por ejemplo, en Namecheap, Cloudflare o GoDaddy).
2. En el registrador, crea estos registros DNS:
   - Cuatro registros `A` para `@` apuntando a `185.199.108.153`, `185.199.109.153`, `185.199.110.153` y `185.199.111.153`.
   - Un registro `CNAME` para `www` apuntando a `km613225-alt.github.io`.
3. En GitHub: **Settings → Pages → Custom domain**, escribe el dominio y activa **Enforce HTTPS**.
4. Cambia la dirección base en `index.html` (etiquetas `canonical` y `og:`), `robots.txt` y `sitemap.xml`.

© 2026 Kevin Molina Antonio. Las fotografías están protegidas por derechos de autor y no se permite su uso sin autorización.
