## Tailwind Css
https://tailwindcss.com/docs/installation

install
npm i -D tailwindcss postcss autoprefixer

npx tailwindcss init - p

Agregar luego en el archivo .css principal lo siguiente
@tailwind base;
@tailwind components;
@tailwind utilities;

luego en tailwind.config.cjs en el content agregamos lo siguiente 
	content: ["./index.html", "./src/**/*.jsx"],

el .html es para indicar que es el archivo principal que va contener toda la vista de nuestro proyecto

y la segunda posicion del array es para indicar que busque dentro de la carpeta src y dentro de todas las carpetas
todos los archivos .jsx