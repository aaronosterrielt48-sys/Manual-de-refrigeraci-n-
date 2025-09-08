# Manual de Refrigeración – Deploy en Vercel (PWA)

Este paquete es una **Web App Progresiva (PWA)** lista para desplegar en **Vercel**.

## Archivos principales
- `index.html`, `styles.css`, `app.js`
- `manifest.webmanifest` (define nombre, tema e íconos del manifold)
- `service-worker.js` (cachea recursos para **modo offline**)
- `icon-48.png`, `icon-96.png`, `icon-192.png`, `icon-512.png`

## Deploy paso a paso en Vercel (sin Git)
1. Entrá a https://vercel.com/ e iniciá sesión.
2. Click en **New Project** → **Deploy Project**.
3. **Arrastrá y soltá** *esta carpeta* (todos los archivos, no el .zip).
4. Vercel detecta un proyecto **estático** → click **Deploy**.
5. Cuando termine, te dará una URL pública (ej: `https://manual-frio.vercel.app`).

## Instalar como app en el celular
- **Android (Chrome)**: abrí la URL → menú ⋮ → **Añadir a pantalla de inicio**.
- **iOS (Safari)**: botón **Compartir** → **Añadir a pantalla de inicio**.

> El `service-worker.js` se registra automáticamente y habilita el uso **offline**.

## Actualizaciones
- Volvé a subir los archivos a Vercel (nuevo Deploy) o usá un repo Git.
- Para ver cambios en el celu, cerrá y abrí la app con conexión a internet.
