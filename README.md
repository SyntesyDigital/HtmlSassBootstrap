# Bootstrap + Sass + Webpack
🚀 Plantilla para iniciar proyectos basados en estas herramientas | Bootstrap + Sass + Webpack (SPA, MPA)

## NUEVA versión

Puedes ver esta versión 'live' en **Vercel** aquí:
[bootstrap-sass-webpack.vercel.app](https://bootstrap-sass-webpack.vercel.app/)

- Múltiples 'entry points' para crear 'MPA' (Aplicaciones Multipáginas)
- Al compilar limpia el css de estilos no usados.
- Disponibles los iconos de **FontAwesome**.
- Fuente cargada de **Google Fonts**


## Instalación

1. `npm install`

## Una vez instalado

Se pueden ejecutar tres comandos:

- `npm start` Arranca un servidor y abre una pestaña en el navegador.
- `npm run dev` Se generan los ficheros en la carpeta `./dist` sin minificar.
- `npm run build` Se generan los ficheros en la carpeta `./dist` minificados y listos para subir a producción.

## Dependencias

```
"dependencies": {
  "@fortawesome/fontawesome-free": "^5.14.0",
  "bootstrap": "^4.5.0",
  "jquery": "^3.5.1",
  "popper.js": "^1.16.1"
},
"devDependencies": {
  "@babel/core": "^7.10.5",
  "@babel/preset-env": "^7.10.4",
  "@fullhuman/postcss-purgecss": "^2.3.0",
  "autoprefixer": "^9.8.5",
  "babel-loader": "^8.1.0",
  "clean-webpack-plugin": "^3.0.0",
  "css-loader": "^3.6.0",
  "file-loader": "^6.0.0",
  "html-webpack-plugin": "^4.3.0",
  "mini-css-extract-plugin": "^0.9.0",
  "node-sass": "^4.14.1",
  "optimize-css-assets-webpack-plugin": "^5.0.3",
  "postcss-loader": "^3.0.0",
  "sass-loader": "^8.0.2",
  "terser-webpack-plugin": "^3.0.8",
  "webpack": "^4.41.6",
  "webpack-cli": "^3.3.11",
  "webpack-dev-server": "^3.10.3"
}
```

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
