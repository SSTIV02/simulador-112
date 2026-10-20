# Instalar el Simulador en el iPhone (GitHub Pages, gratis)

Por qué el .html no abre en iPhone: iOS no ejecuta archivos HTML locales desde Archivos o Mensajes. Necesita una dirección https. GitHub Pages la da gratis.

## Paso a paso (unos 5 minutos, desde el computador)
1. Entra a github.com con TU cuenta → botón **New** → nombre `simulador-112` → **Public** (Pages gratis exige público; ver aviso abajo) → **Create repository**.
2. En el repositorio nuevo: **uploading an existing file** → arrastra TODO el contenido de esta carpeta (index.html, manifest.webmanifest, sw.js, los 4 iconos y .nojekyll) → **Commit changes**.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. En 1-2 minutos aparece la dirección: `https://TU-USUARIO.github.io/simulador-112/`.
5. En el iPhone abre esa dirección en **Safari** (no en Chrome) → botón Compartir → **Añadir a pantalla de inicio**. Queda como app, a pantalla completa y con uso sin conexión después de la primera carga.

## Avisos importantes
- Repositorio público = cualquiera con el enlace puede ver el contenido (preguntas y explicaciones). Si te incomoda, usa un nombre poco evidente o pide una opción privada (GitHub Pro o Cloudflare Pages con acceso restringido).
- El progreso guardado en el navegador NO se comparte entre Safari, la app instalada y el computador. Usa el botón **Guardar** de la app para exportar y respaldar.
- Para actualizar: sube el nuevo index.html y cambia `VERSION` en sw.js (por ejemplo `sim112-v11-2`), si no, el iPhone seguirá mostrando la versión guardada.
- No pude probar en un iPhone real ni en WebKit (mi entorno solo tiene Chromium). Si algo falla en Safari, envíame captura y el texto del error.
