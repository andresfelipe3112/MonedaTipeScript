

Basicamente para integrar webpack necesitamos los siguientes paquetes adicionales:

* ts-loader
* typescript
* webpack
* webpack-cli
* webpack-dev-server

## ¿Cómo levanto el proyecto?
1. Clonar el repositorio
2. Posicionarse desde la consola en la carpeta del proyecto e instalar los paquetes a través del comando `npm install`.
3. Elegir el modo a trabajar si será desarrollo o producción que se explicará a continuación.

## Modo desarrollo
Posicionarse desde la consola en la ruta del proyecto y ejecutar el comando `npm run dev`.

Dentro del proyecto tenemos un archivo principal que es donde se visualizará los cambios del proyecto. Este se encuentra en **dist/index.html**.

*La ventaja de usar el servidor local de webpack es que permite refrescar los cambios que hagamos automáticamente en un servidor local evitando de esta manera tener que hacer build ante cada cambio.*

## Modo producción
Cuando estemos listo para generar todo nuestro proyecto basta con ejecutar `npm run build` y se generar un compilado en un solo archivo en la siguiente ruta **build/bundle.js**.

KODOTI - ¡Aprende más, haciendo pequeños proyectos!


