# NeoSystem v1.3 — Installable PWA

Esta versión añade: manifest, icono, instalación desde Chrome Android, modo standalone y caché offline básica.

## Publicar
1. Descomprime.
2. Sube los cuatro archivos a la raíz de tu repo GitHub Pages: `index.html`, `manifest.webmanifest`, `service-worker.js`, `icon.svg`.
3. Espera el deploy. Abre la página en Chrome Android.
4. Usa el botón Instalar si aparece; si no, menú ⋮ → Instalar aplicación / Añadir a pantalla principal.

**Limitación:** es una PWA que funciona como app independiente y personaliza su propia interfaz. No modifica ajustes, barra de estado, pantalla de bloqueo ni temas nativos de HyperOS. Para eso necesitamos una app Android nativa y estudiar permisos/APIs compatibles.
