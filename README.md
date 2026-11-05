# Javier Piratova — Professional Portfolio

Portafolio profesional estático en HTML5, CSS3 y JavaScript vanilla. No requiere Node.js, framework, backend ni dependencias de runtime.

## Desarrollo local

Abre `index.html` en el navegador o ejecuta:

```bash
python -m http.server 8080
```

Luego visita http://localhost:8080.

## Publicación: Cloudflare Pages

El sitio se publica en **Cloudflare Pages**: https://portafolio-cal.pages.dev/

La integración recomendada es conectar este repositorio desde Cloudflare Pages mediante **Workers & Pages → Create → Pages → Connect to Git**:

- Production branch: `main`
- Build command: dejar vacío (sitio estático sin build).
- Build output directory: `/` (raíz del repositorio).

Cloudflare realizará el despliegue de producción al recibir cambios en `main`. Las ramas/PR pueden generar Preview Deployments si están habilitados en la configuración del proyecto.

GitHub Actions ejecuta validaciones de calidad en cada Pull Request y push a `main`; no publica en GitHub Pages ni mantiene un segundo hosting.

## Estructura

- `index.html`: contenido, metadatos SEO y datos estructurados.
- `styles.css`: diseño responsive, accesibilidad y estilos.
- `script.js`: interacciones pequeñas sin dependencias.
- `assets/`: fotografía, favicon e imagen Open Graph.
- `sitemap.xml` y `robots.txt`: descubrimiento por buscadores.
- `.github/workflows/ci.yml`: validación del sitio.

## Fotografía profesional

La fotografía profesional de Javier fue recibida para esta actualización, pero todavía debe incorporarse como archivo binario en `assets/javier-piratova.webp`. Mientras tanto, la página conserva el monograma JP para evitar una referencia rota. Una vez agregado el archivo, actualizar el `src` del elemento de perfil en `index.html`.

## Contenido y privacidad

Los proyectos se describen como casos anonimizados de experiencia profesional. No incluir código, datos, diagramas internos, nombres de clientes ni métricas no autorizadas.
