# Javier Piratova — Professional Portfolio

Portafolio profesional estático en HTML5, CSS3 y JavaScript vanilla. No requiere Node.js, framework, backend ni dependencias de runtime.

## Desarrollo local

Abre `index.html` en el navegador o ejecuta:

```bash
python -m http.server 8080
```

Luego visita http://localhost:8080.

## Publicación: GitHub Pages

Este repositorio está preparado para desplegarse con GitHub Actions.

1. En GitHub abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **GitHub Actions** como Source.
3. Fusiona los cambios de `feature/portfolio-v2` en `main`.
4. El workflow `.github/workflows/pages.yml` validará los archivos y publicará el sitio.
5. Consulta **Actions** para verificar el resultado del despliegue.

URL esperada del proyecto: https://xavier8502.github.io/Portafolio/

## Estructura

- `index.html`: contenido, metadatos SEO y datos estructurados.
- `styles.css`: diseño responsive, accesibilidad y estilos.
- `script.js`: interacciones pequeñas sin dependencias.
- `assets/`: fotografía, favicon e imagen Open Graph.
- `sitemap.xml` y `robots.txt`: descubrimiento por buscadores.
- `.github/workflows/pages.yml`: CI/CD de GitHub Pages.

## Fotografía profesional

El archivo actual `assets/profile-placeholder.svg` es un placeholder de marca JP. Reemplázalo por la fotografía profesional autorizada y actualiza la referencia en `index.html` a `assets/javier-piratova.webp`. No se debe usar una fotografía generada que altere la identidad del titular.

## Contenido y privacidad

Los proyectos se describen como casos anonimizados de experiencia profesional. No incluir código, datos, diagramas internos, nombres de clientes ni métricas no autorizadas.
