# Sebastian Romero · Portfolio

Sitio estático del portfolio freelance: automatización, dashboards e informes operativos.

**Live:** [https://crearbots.github.io/portfolio/](https://crearbots.github.io/portfolio/)

## Stack

- [Astro](https://astro.build/) (static)
- CSS plano (sin frameworks)
- Español (`lang="es"`)
- GitHub Pages (`base: /portfolio/`)

## Desarrollo local

Requiere Node.js ≥ 22.

```bash
npm install
npm run dev
```

Abre la URL que imprime Astro (por defecto `http://localhost:4321/portfolio/`).

## Build

```bash
npm run build
npm run preview
```

La salida queda en `dist/`.

## GitHub Pages

- `astro.config.mjs`: `site: https://crearbots.github.io`, `base: /portfolio/`
- Deploy automático con GitHub Actions (`.github/workflows/deploy.yml`) al hacer push a `main`
- Source de Pages: **GitHub Actions**

## Contacto

- WhatsApp: [wa.me/573138793438](https://wa.me/573138793438)
- GitHub: [github.com/crearbots](https://github.com/crearbots)
