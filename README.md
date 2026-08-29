# Transición TI Hematoncólogos × BLT — Tablero

Página única (`index.html`) con dos pestañas: **Checklist** (87 puntos con responsables) y
**Presentación** (14 diapositivas: fases, tiempos, entregables, gates).

Las observaciones se registran en la hoja de Google compartida enlazada dentro del tablero.

## Publicar en Netlify (opción A — Drop, sin cuenta técnica)

1. Abre https://app.netlify.com/drop
2. Arrastra **esta carpeta** (`transicion-ti-dashboard`) a la página.
3. Netlify da una URL al instante. En *Site settings → Change site name* ponla como
   `transicion-ti-hematoncologos`.

## Publicar en Netlify (opción B — CLI, deploy repetible)

```bash
cd "transicion-ti-dashboard"
npx netlify-cli deploy --prod --dir .
```
La primera vez pedirá iniciar sesión y crear/enlazar el sitio.

## Publicar en GitHub Pages

1. Crea un repo (p. ej. `transicion-ti-dashboard`) y sube esta carpeta.
2. Settings → Pages → Source: rama `main`, carpeta `/root`.
3. Queda en `https://<usuario>.github.io/transicion-ti-dashboard/`.
