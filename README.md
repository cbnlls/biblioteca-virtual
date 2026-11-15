# Biblioteca Virtual
Biblioteca virtual que busca ofrecer un espacio digital para descubrir, explorar y disfrutar de libros mediante una experiencia de navegación intuitiva, atractiva y accesible.
## Tecnologías
- HTML
- Sass
- JavaScript
- Vite
- GSAP (más adelante)


## Estructura del proyecto

```text
biblioteca-virtual/
│
├── public/
│   └── favicon.svg
│
├── src/
│   ├── assets/
│   ├── styles/
│   ├── scripts/
│   └── main.js
│
├── index.html
├── package.json
└── README.md
```

## Explicación de estructura del proyecto

### Carpetas:
*Carpeta raiz/*: Configuración y archivos principales

*src/*: Código fuente (apariencia de la página)
*src/assets/*: Recursos visuales
*src/styles/*: Apariencia de la página
*src/scripts/:* Comportamiento de la página (funcionalidad)

*main.js*: Punto de entrada de los estilos (styles). Conecta los recursos y comportamientos de la página.

*public/*: Archivos estáticos que es necesario publicar directamente, sin que Vite tenga que procesarlos.
*public/favicon.svg*: Icono pequeño que aparece en la pestaña del navegador.

*index.html*: Contiene la estructura HTML que verá el navegador.
*package.json*: La configuración del proyecto (Node.js y npm) para conocer información y dependencias del proyecto.
*README.md*: COntiene la documentación del proyecto.

## Instalación
npm install

## Ejecución
npm run dev
