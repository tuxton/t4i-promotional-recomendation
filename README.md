# Tech4Impact — Recomendador de Charlas

Motor de recomendación de charlas para el evento Tech4Impact by NaranjaX (27 de mayo).

## Uso local

Abrí `index-techtalk-pro.html` directamente en el browser — no necesita servidor ni dependencias.

## Deploy en Vercel (v0)

### Opción A — Drag & drop
1. Zipear el directorio completo
2. Ir a [vercel.com/new](https://vercel.com/new) y soltar el zip
3. Vercel detecta el sitio estático automáticamente y deploy listo

### Opción B — GitHub
1. `git init && git add . && git commit -m "init"`
2. Crear repo en GitHub y hacer push
3. Conectar el repo en [vercel.com/new](https://vercel.com/new)
4. Framework preset: **Other** (sitio estático sin build)
5. Confirmar deploy

La raíz `/` sirve `index-techtalk-pro.html` (configurado en `vercel.json`).  
Los archivos `talks.md` y `skills.md` se cargan automáticamente.  
Si el fetch falla (ej: CORS en dev local sin servidor), la app usa los datos embebidos como fallback.

## Para deployar en el sitio del evento (CDN propio)

1. Copiá todos los archivos (`index-techtalk-pro.html`, `talks.md`, `skills.md`) a tu servidor o CDN
2. La fuente `Gibson-Semibold` se carga automáticamente si está disponible en el dominio
3. El logo de Tech4Impact se carga desde `tech4impact.naranjax.com/assets/...`

## Personalización

### Agregar / cambiar charlas
Editá el array `TALKS` y el objeto `PROFILES` en el `<script>`:

```js
const TALKS = [
  { id: "mi-charla", title: "Título de la charla" },
  // ...
];
```

Y agregá el perfil de keywords correspondiente en `PROFILES`.

### Cambiar colores
Las variables clave en el CSS:
- Fondo: `#130a2a` + gradientes radiales
- Naranja: `#ff5e00`
- Purple: `#7321a6`
- Botón glow: `box-shadow: 0 0 25px #ff5e0080, ...`

## Stack

- React 18 (UMD, sin build)
- CSS vanilla
- Scoring 100% client-side (no API, funciona offline)
