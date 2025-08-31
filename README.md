# Calculadora de Servicios (Web)

Esta es la versión web de tu calculadora basada en tu Excel.

## Cómo publicarla en GitHub Pages

1. Crea un repositorio en GitHub (por ejemplo: `calculadora-servicios`).
2. Sube el archivo `index.html` (renombra `calculadora.html` a `index.html`).
3. En GitHub, ve a **Settings → Pages**.
4. En **Build and deployment**, elige:
   - **Source**: Deploy from a branch
   - **Branch**: `main` y carpeta `/root`
5. Guarda. GitHub generará una URL como: `https://tuusuario.github.io/calculadora-servicios/`

## Editar tarifas
- Fotografía/Vídeo (tabla E24–E28 en tu Excel): edita los valores en el bloque JS `precioBase`.
- Matterport (B24–B28): edita los valores en el bloque JS de `matterport`.
- Extras fijos (B10, B11): edita los valores `100` y `100` en el JS.
