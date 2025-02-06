# Bits de Educación
Este proyecto nace de la necesidad de tener una comunidad de docente de educación básica regular,
donde podamos apoyarnos en cuanto al uso de la tecnología, viendo mucho esta necesidad en su mayoría.


## Sobre este proyecto
Tenemos un proyecto desarrollado en react, usando vite como manejador de paquetes y CSS puro para los estilos.

Tenemos la siguiente estructura de nuestra carpetas.

```csharp
mi-proyecto/
│── public/               # Archivos estáticos (favicon, imágenes globales, etc.)
│── src/
│   ├── assets/           # Recursos estáticos (imágenes, fuentes, etc.)
│   │   ├── images/
│   │   ├── fonts/
│   │   ├── styles/       # Estilos globales
│   │   │   ├── reset.css # Reseteo de estilos
│   │   │   ├── global.css # Estilos generales
│   │   │   ├── variables.css # Variables CSS si las usas
│   │   │   ├── themes/   # Temas opcionales si aplicas dark/light mode
│   ├── components/       # Componentes reutilizables
│   │   ├── Button/
│   │   │   ├── Button.jsx
│   │   │   ├── Button.css
│   │   ├── Card/
│   │   │   ├── Card.jsx
│   │   │   ├── Card.css
│   ├── pages/            # Páginas principales
│   │   ├── Home/
│   │   │   ├── Home.jsx
│   │   │   ├── Home.css
│   │   ├── About/
│   │   │   ├── About.jsx
│   │   │   ├── About.css
│   ├── hooks/            # Custom Hooks (si los usas)
│   ├── context/          # Context API (si lo usas)
│   ├── services/         # Llamadas a APIs u otras funciones auxiliares
│   ├── utils/            # Funciones de utilidad
│   ├── App.jsx           # Componente principal
│   ├── index.js          # Punto de entrada
│── package.json
│── .gitignore
│── README.md
```
