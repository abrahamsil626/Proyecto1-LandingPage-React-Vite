# Rapid Galaxy

Landing page de demostración para una plataforma SaaS, desarrollada en **React 19 + Vite**, con una estética limpia y moderna: fondo claro, acentos en azul, tarjetas redondeadas, animaciones suaves y diseño totalmente responsive.

> **Prueba el proyecto en vivo:** [reactlandingdemo.netlify.app](https://reactlandingdemo.netlify.app)

## Funcionalidad

- Interfaz íntegramente **en español**.
- **Navbar** fija que cambia a fondo translúcido con desenfoque al hacer scroll, con menú hamburguesa en móvil.
- **Hero** con titular, llamadas a la acción e imagen destacada.
- **Características principales** en tarjetas con iconos y efecto hover.
- **Carrusel de proyectos** con navegación por flechas e indicadores, y transiciones de opacidad y escala.
- **Testimonios** sobre fondo oscuro, con valoración en estrellas y avatar.
- **Formulario de contacto** con validación en cliente (nombre, email con formato válido y mensaje obligatorios) y confirmación visual de envío.
- **Footer** con redes sociales y enlaces de compañía, soporte y legal.

> El envío del formulario es **simulado** en el cliente (solo se registra en consola); no hay backend.

## Stack

React 19 · Vite · Tailwind CSS v4 · Lucide React.

## Empezar

```bash
git clone https://github.com/abrahamsil626/Proyecto1-LandingPage-React-Vite.git
cd Proyecto1-LandingPage-React-Vite
npm install
npm run dev        # http://localhost:5173
```

| Script | Qué hace |
|---|---|
| `npm run dev` | Servidor de desarrollo |
| `npm run build` | Build de producción en `dist/` |
| `npm run preview` | Sirve localmente el build de producción |

## Despliegue

El contenido de `dist/` (generado con `npm run build`) se puede subir a Vercel, Netlify, GitHub Pages o similar. La versión en vivo está publicada en Netlify.

## Estructura

```
public/       Recursos estáticos
src/
  App.jsx     Componentes de la landing (Navbar, Hero, Features,
              Carousel, Testimonials, ContactForm, Footer)
  main.jsx    Punto de entrada de React
  index.css   Estilos globales y Tailwind
index.html    Documento base
vite.config.js
```

## Sistema de diseño

- **Color:** azul (`blue-600`) como acento sobre fondos blancos y `slate`; sección de testimonios en `slate-900`.
- **Forma:** esquinas muy redondeadas (`rounded-xl` a `rounded-[3rem]`) y botones en píldora.
- **Profundidad:** sombras suaves tintadas de azul y transiciones en hover/activo.
- **Iconografía:** Lucide React, con trazo uniforme.
