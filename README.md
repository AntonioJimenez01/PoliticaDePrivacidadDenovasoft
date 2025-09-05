# Política de Privacidad — Deploy en Netlify

Sitio estático en español, listo para que **Netlify** lo reconozca desde tu repositorio de GitHub.

## Cómo usar

1. **Edita** `index.html` y reemplaza:
   - `[NOMBRE DE LA APP]`
   - `[EMAIL DE SOPORTE]`
2. **Sube** este proyecto a un repo en GitHub (p. ej., `privacy-policy`).

## Deploy en Netlify (app.netlify.com)

1. Entra a **Netlify** → **Add new site** → **Import an existing project**.
2. Conecta tu cuenta de **GitHub**.
3. Elige el repo que contiene este proyecto.
4. Configuración de deploy:
   - **Build command**: _vacío_ (no hay build, es estático)
   - **Publish directory**: `.` (raíz)
5. Click **Deploy site**. Netlify te dará una URL tipo `https://xxxxxx.netlify.app`.
6. (Opcional) **Custom domain**: en **Domain settings**, agrega `privacidad.tudominio.com` y crea un CNAME hacia el subdominio de Netlify.

Usa esa URL en **Google Play Console → Política de privacidad**.
