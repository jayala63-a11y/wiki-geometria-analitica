# Wiki de geometría analítica

Sitio estático de una sola página para estudiar las secciones cónicas. La página principal es `index.html`; no requiere instalación, compilación ni dependencias externas.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub. Si usas GitHub Free, hazlo público para que GitHub Pages pueda publicarlo.
2. Sube al repositorio estos archivos y carpetas:
   - `index.html`
   - `.nojekyll`
   - `README.md`
   - `.github/workflows/pages.yml`
3. En GitHub, abre **Settings → Pages** y selecciona **GitHub Actions** como fuente de publicación.
4. Abre la pestaña **Actions** y espera a que termine el flujo **Deploy static wiki to GitHub Pages**.
5. La URL pública aparecerá en **Settings → Pages** y en los detalles del flujo de publicación.

Cada cambio que subas a la rama `main` volverá a publicar la página automáticamente.

## Publicación desde Windows

Puedes subir esos archivos desde la página del repositorio con **Add file → Upload files**, o usar GitHub Desktop para crear/seleccionar el repositorio local, hacer un commit y subirlo.

El flujo de publicación copia únicamente `index.html` al sitio público. Los demás archivos locales de la carpeta no se publican.
