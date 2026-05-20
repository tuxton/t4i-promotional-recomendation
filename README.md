# Tech4Impact — Recomendador de Charlas

Motor de recomendación de charlas para el evento Tech4Impact by NaranjaX (27 de mayo).

## Uso

Abrí `index.html` directamente en el browser — no necesita servidor ni dependencias.

## Para deployar en el sitio del evento

1. Copiá `index.html` a tu servidor o CDN
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
