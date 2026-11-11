# Economía Yan Poll

App de finanzas personales para celular que funciona **sin internet**: cuentas, movimientos, presupuestos, préstamos por cobrar, metas y alertas automáticas.

Este repositorio solo contiene el código de la app. **No incluye datos personales**: los datos se guardan únicamente en el celular donde instales la app y se cargan con un archivo de respaldo (`.json`).

## Publicarla (una sola vez)

1. **Settings → General → Danger Zone → Change visibility → Public.** GitHub Pages es gratis solo en repositorios públicos.
2. **Settings → Pages →** en *Build and deployment* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y pulsa **Save**.
3. En 1–2 minutos la app queda en `https://feryp0503.github.io/economia-yanpoll/`.

## Instalarla en el celular

- **Android (Chrome):** abre la dirección → menú ⋮ → **Instalar app** (o *Agregar a pantalla principal*).
- **iPhone (Safari):** abre la dirección → botón Compartir → **Agregar a inicio**.

Ábrela desde el ícono, toca **Importar mis datos** y elige tu archivo `mis-datos-yanpoll.json`. Desde ese momento funciona sin internet.

## Respaldo

Los datos viven solo en el celular. Haz un respaldo cada semana en **Más → Descargar respaldo** y guárdalo en Drive o WhatsApp. Si cambias de celular o borras los datos del navegador, restáuralo con **Importar respaldo**.

## Actualizar la app

Al subir una nueva versión, cambia el número de `CACHE` en `sw.js` (por ejemplo `eyp-v2`). El celular descarga la nueva versión la próxima vez que abras la app con internet; tus datos no se borran.
