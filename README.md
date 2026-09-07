# KNG Cargo — GitHub Pages

Esta carpeta está preparada para publicarse directamente con GitHub Pages.

## Publicación
1. Crea un repositorio nuevo en GitHub (por ejemplo `kng-cargo-web`).
2. Sube `index.html`, `.nojekyll` y la carpeta `assets`.
3. En GitHub: **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Branch: `main` y carpeta `/ (root)`. Guarda.
6. GitHub mostrará la URL pública de la web.

## Dominio propio
En **Settings → Pages → Custom domain**, escribe tu dominio cuando lo tengas. GitHub te indicará los registros DNS que debes configurar en tu proveedor de dominio. Activa **Enforce HTTPS** cuando esté disponible.

## Antes de lanzar definitivamente
- Confirmar que `+34 932 123 456` es el teléfono real.
- Confirmar que `info@kngcargo.com` es el email real.
- Crear/enlazar Política de privacidad, Aviso legal y Cookies. Esos enlaces siguen sin contenido porque faltan los datos legales de la empresa.
- Cuando conozcas el dominio definitivo, añadir `canonical` y `og:url` al `<head>`.
