# Sebastian Romero · Portafolio

Sitio estático del portafolio freelance: automatización, dashboards e informes operativos.

**Live:** [https://crearbots.github.io/portafolio/](https://crearbots.github.io/portafolio/)

## Stack

- [Astro](https://astro.build/) (static)
- CSS plano (sin frameworks)
- Español (`lang="es"`)
- GitHub Pages (`base: /portafolio/`)

## Desarrollo local

Requiere Node.js ≥ 22.

```bash
npm install
npm run dev
```

Abre la URL que imprime Astro (por defecto `http://localhost:4321/portafolio/`).

## Build

```bash
npm run build
npm run preview
```

La salida queda en `dist/`.

## GitHub Pages

- `astro.config.mjs`: `site: https://crearbots.github.io`, `base: /portafolio/`
- **Deploy actual:** rama `gh-pages` con el contenido de `dist/` + archivo `.nojekyll` (necesario para la carpeta `_astro`)
- Source de Pages: branch `gh-pages` / root

### Redeploy manual

```bash
npm run build
# publicar contenido de dist/ en la rama gh-pages (incluye .nojekyll)
```

Opcional: cuando el token de autenticación tenga scope `workflow`, se puede añadir `.github/workflows/deploy.yml` (Actions → Pages) y cambiar el source de Pages a GitHub Actions.

## Contacto

- WhatsApp: [wa.me/573138793438](https://wa.me/573138793438)
- GitHub: [github.com/crearbots](https://github.com/crearbots)
