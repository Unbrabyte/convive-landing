# Convive — Landing

Landing page para **Convive**, software de gestión de consorcios para Uruguay.

## Stack

- HTML estático
- Tailwind CSS (vía CDN)
- Google Fonts (Inter + Playfair Display)
- Iframe de YouTube para demo en video

## Estructura

```
.
├── index.html          # Landing single-page
├── assets/             # Logos de Convive
└── .nojekyll           # Para que GitHub Pages sirva archivos como están
```

## Desarrollo local

Abrí `index.html` en el navegador, o servilo con cualquier server estático:

```bash
python -m http.server 8000
# o
npx serve
```

## Deploy

Hosteado en GitHub Pages desde la rama `main`.
