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

| Archivo / Carpeta | Descripción |
|---|---|
| `src/` | Contiene el código fuente del proyecto. |
| `src/assets/` | Almacena los recursos visuales, como imágenes, fuentes e iconos. |
| `src/styles/` | Contiene los archivos CSS/Sass que definen la apariencia de la página. |
| `src/scripts/` | Contiene los archivos JavaScript que controlan el comportamiento y la funcionalidad de la página. |
| `src/main.js` | Punto de entrada de JavaScript. Conecta los estilos y los scripts del proyecto. |
| `public/` | Almacena archivos estáticos que Vite publica directamente, sin procesarlos. |
| `public/favicon.svg` | Icono que aparece en la pestaña del navegador. |
| `index.html` | Contiene la estructura HTML principal que verá el navegador. |
| `package.json` | Archivo de configuración que contiene información del proyecto, dependencias y scripts de npm. |
| `package-lock.json` | Este archivo registra las versiones exactas de los paquetes instalados, incluyendo sus dependencias internas. |
| `README.md` | Contiene la documentación del proyecto. |

## Estructura inicial de la landing page
01. Header
Logotipo · Navegación · Menú

02. Hero
Presentación principal de la biblioteca

03. Libros destacados
Selección visual de libros

04. Sobre la biblioteca
Concepto y propósito del proyecto

05. Footer
Información adicional y enlaces

## Instalación
npm install

## Ejecución
npm run dev
