## Cómo publicar tu primer paquete npm en el registry de GitHub

En este repositorio encontrarás el código de ejemplo del artículo de mi blog "Cómo publicar tu primer paquete npm en el registry de GitHub".

Espero que te sea útil, si te sirvió, no olvides agradecerme en twitter, me encuentras como @diana_nerd. Muchas gracias. :3

#### Para ejecutar el código de ejemplo

Para ejecutar el código de ejemplo solo necesitas usar el comando:
```sh
node example
```

#### Para instalar este paquete vía npm

Para instalar este paquete vía npm, debes agregar un archivo .npmrc en la misma ubicación que tu package.json, con el registry apuntando a:
```txt
registry=https://npm.pkg.github.com/nerddiana
```

Después puedes instalar el paquete normalmente:
```sh
npm i @nerddiana/tutorial-mi-primer-package --save
```

Puedes ejecutar el código de ejemplo con el comando:
```sh
node node_modules/@nerddiana/tutorial-mi-primer-package/example
```

O puedes importarlo y usar sus funciones en JavaScript:
```js
// index.js
const math = require('@nerddiana/tutorial-mi-primer-package');

console.log('Suma 2 + 2 = ', math.add(2, 2));
console.log('Multiplicación 2 * 4 = ', math.mult(2, 4));
```
Para cualquier duda o comentario, puedes encontrarme en twitter como @diana_nerd,
también puedes mandarme un correo.
