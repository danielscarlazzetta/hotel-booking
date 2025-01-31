npm run dev


Paso 1 para el desarrollo de HOTEL-BOOKING

1 instalacion de TailwindCSS
npm install tailwindcss postcss autoprefixer

2- inicializar Tailwind
npx tailwindcss init -p


3- Instalacion de prisma
npm install prisma --save-dev


4- Configuracion basica de tailwind.config.js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
    "./app/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};

5- Agregar Tailwind a los estilos globales styles/globals.css
@tailwind base;
@tailwind components;
@tailwind utilities;

PAso 2 para el desarrollo de HOTEL-BOOKING

1 instalacion de prisma
npm install prisma --save-dev

1.1 inicio de prisma
npx prisma init