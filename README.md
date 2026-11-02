# Air-Limp · web, app de clientes y panel de empresa

Versión de demostración de la nueva web y app de **Air-Limp Climatización** (Cartes, Cantabria).

| Archivo | Qué es | Quién lo usa |
|---|---|---|
| `index.html` | App de clientes: presupuestos, averías, citas, equipos, reseñas, asistente | Clientes (móvil) |
| `panel.html` | Panel de gestión: solicitudes, agenda, partes con firma, clientes, reseñas, contenido | Oficina y técnicos |
| `demo.html` | Demo de presentación con las dos vistas y el recorrido guiado | Para enseñarla |

Contraseña del panel en la demo: **1995**.

## 1. Subirlo a GitHub
1. Crea un repositorio nuevo, por ejemplo `Aplicaci-n-airlimp`.
2. Sube todo el contenido de esta carpeta (incluida la carpeta oculta `.github`).

## 2. Publicar la web gratis (GitHub Pages)
1. En el repositorio: **Settings → Pages**.
2. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y guarda.
3. En un par de minutos estará en:
   - App de clientes: `https://maykelpg.github.io/Aplicaci-n-airlimp/`
   - Panel de empresa: `https://maykelpg.github.io/Aplicaci-n-airlimp/panel.html`
   - Demo: `https://maykelpg.github.io/Aplicaci-n-airlimp/demo.html`

## 3. Instalarla en el móvil sin tiendas
Abre la dirección en el móvil y elige **Añadir a pantalla de inicio** (Chrome: menú ⋮ → *Instalar app*; iPhone: Compartir → *Añadir a pantalla de inicio*). Se abre como una app, con su icono y a pantalla completa. Igual con el panel.

## 4. APK para Android
Cada vez que subas cambios a `main`, GitHub crea el APK solo:
1. Pestaña **Actions** → la última ejecución de *App Android (APK)*.
2. Abajo, en *Artifacts*, descarga **airlimp-apk** (es un .zip con `app-debug.apk`).
3. Pásalo al móvil e instálalo (Android pedirá permitir instalar apps de origen desconocido).

## Importante: es una demo
- Los datos se guardan solo en el dispositivo donde se usa. La app de clientes y el panel solo comparten datos si se abren en el **mismo navegador del mismo dispositivo** (útil para enseñarla).
- Para que lo que pide un cliente llegue de verdad al panel de la empresa hace falta un servidor. Opción gratuita prevista: **Supabase** (base de datos, usuarios y fotos).
- Pendiente de confirmar: horario, email, número de WhatsApp, nombres de los técnicos, precios y fotos reales de obras.

Diseño y desarrollo: Maykel Puente.
