# Blank Template Tailwind

Plantilla básica para arrancar con la librería Tailwind CSS

- Mínimas dependencias
- Ideal para maquetar de forma libre
- Úsalo con tu `live-server` favorito


## Instalación

1. Descarga el repositorio
2. Ejecuta `npm install` 

A partir de ahí tienes dos opciones para generar el CSS si haces cambios en la configuración de tailwind:

- Ejecuta `npm run build` si quieres regenerar `public/css/styles.css` manualmente.
- Ejecuta `npm run watch` si quieres que se actualice con cada cambio.

## Recomendaciones

### Live Server

Utilizar un servidor local que permita la recarga automática en cada cambio de los ficheros.

Uso [live-server](https://www.npmjs.com/package/live-server).

Con el comando: `live-server public --watch`

### PurgeCSS

La plantilla está preconfigurada para trabajar con PurgeCSS.

La configuración puedes encontrarla en `postcss.config.js`.

Para ejecutarlo: `NODE_ENV=production npm run build`

Si cambiar el nombre a la carpeta `public` debes configurarlo.

Para más información: [PurgeCSS](https://purgecss.com/configuration.html)