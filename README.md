# Relojj

Reloj minimalista a pantalla completa, distribuido como una Progressive Web App (PWA).

## URL de GitHub Pages

https://furry5633-collab.github.io/Relojj/

Para activar la publicación, selecciona **GitHub Actions** en **Settings → Pages → Build and deployment → Source**. Una vez habilitado, el workflow publica automáticamente los cambios de `reloj-pwa/` en esa URL al actualizar `main` o la rama de trabajo de Arena.

## Archivos

La aplicación está en [`reloj-pwa/`](reloj-pwa/). Se extrajo desde `reloj-pwa.zip` y conserva el reloj, sus recursos de instalación y el service worker para uso sin conexión.

## Publicación

El workflow [Deploy reloj-pwa to GitHub Pages](.github/workflows/pages.yml) publica el contenido de `reloj-pwa/` en GitHub Pages al actualizar `main` o la rama de trabajo de Arena. También puede ejecutarse manualmente desde la pestaña **Actions**.
