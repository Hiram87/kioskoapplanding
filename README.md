# KioskoApp — Landing

Página de marketing de `kioskoapp.com` / `www.kioskoapp.com` (distinta de la app de pedidos real,
que vive en el repo `dev1402kitchen` y sirve desde hosts propios como `app.kioskoapp.com`).

Sitio estático, sin build (`index.html` autocontenido) — deploy directo en Vercel sin configuración.

## Ramas

- `main` — producción (`kioskoapp.com`, `www.kioskoapp.com`)
- `staging` — mismo contenido que `main`, para revisar cambios antes de promoverlos (mismo patrón
  que el repo principal `dev1402kitchen`)

## Diseño

Dirección "Papel Picado" — paleta `#FFF9EE`/`#D6006E`/`#00A9BE`/`#FFCB3D`/`#2B1B3D`, tipografías
Bungee (display) + Mulish (texto). Logo y wordmark reales del producto (mismo `favicon.svg` que
`dev1402kitchen`).

Los CTA de la página enlazan a los hosts reales de producción: `registro.kioskoapp.com` (alta de
negocio) y `portal.kioskoapp.com` (inicio de sesión de dueños de negocio).
