# Rutina

Planes de entrenamiento (perfiles Alejo, Pau y Alejo · Split), sitio estático de una sola página (`index.html`), pensado para consultarse desde el celular en el gimnasio.

- HTML + CSS + JS vanilla, sin dependencias ni build. Funciona abriendo `index.html` con doble clic, incluso sin conexión.
- Los datos del plan están embebidos en el archivo, no hace falta `fetch`.
- El registro de pesos y las sesiones completadas se guardan en `localStorage`, en el navegador del celular.

## Publicar en Vercel

1. Entrá a [vercel.com/new](https://vercel.com/new) e importá este repositorio.
2. No hace falta configurar nada: no hay framework ni build command, Vercel sirve `index.html` como sitio estático apenas termina el deploy.
3. Una vez desplegado, abrí la URL desde el celular y agregala a la pantalla de inicio para acceso rápido tipo app.

## Uso local

Abrí `index.html` directamente en el navegador (doble clic), o serví la carpeta con cualquier servidor estático si preferís probarlo así.
