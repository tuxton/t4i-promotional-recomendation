# Tech4Impact — Recomendador de Charlas

App web estática que recomienda charlas del evento **Tech4Impact by NaranjaX** (27 de mayo de 2026) según el perfil del asistente: rol, seniority y skills.

🔗 **Demo en vivo:** https://t4i-promotional-recomendation.vercel.app

---

## Estructura del proyecto

```
index.html      → App principal (React 18 UMD, sin build)
talks.md        → Lista de charlas disponibles
skills.md       → Lista de skills seleccionables en el formulario
vercel.json     → Configuración de Vercel (headers, rewrite)
```

---

## Cómo correrlo localmente

Abrí `index.html` directamente en el browser — no necesita servidor, build ni dependencias.

> Si los archivos `talks.md` / `skills.md` no cargan (CORS en file://), la app usa los datos embebidos como fallback.

---

## Cómo agregar o editar charlas

Editá `talks.md` — una charla por línea con el formato:

```
## id | Título de la charla
```

El ID se usa internamente para el motor de recomendación. El título es lo que ve el usuario.

## Cómo agregar o editar skills

Editá `skills.md` — una skill por línea con guión al inicio:

```
- Nombre de la skill
```

---

## Deploy

El proyecto está conectado a **Vercel** vía este repositorio de GitHub. Cualquier push a `main` dispara un redeploy automático.

Para hacer un deploy manual desde cero:

1. Clonar el repo
2. Conectar en [vercel.com/new](https://vercel.com/new) → Framework preset: **Other**
3. Confirmar deploy (no hay build step)

---

## Stack

- **React 18** vía CDN (UMD) — sin JSX, sin bundler
- **CSS vanilla** — todo en un `<style>` inline
- **Scoring client-side** — no hay API ni backend, funciona offline
