FlashThink

FlashThink es una aplicación móvil creada con Vite, JavaScript Vanilla y Capacitor, diseñada para ofrecer una experiencia rápida, ligera y compatible con Android.
El objetivo de la app es presentar contenidos de forma simple y dinámica, permitiendo al usuario interactuar fácilmente con la información.

- Tecnologías utilizadas

Vite – Para crear y compilar el proyecto web.

JavaScript Vanilla – Lógica de la aplicación sin frameworks.

HTML + CSS – Interfaz y estilos.

Capacitor – Permite convertir el proyecto web en una app Android.

Android Studio – Generación del APK final.

- Estructura del proyecto
FlashThink/
│── android/            # Proyecto Android generado por Capacitor
│── public/             # Recursos públicos (iconos, imágenes, etc.)
│── src/                # Código principal de la aplicación
│── dist/               # Build generado por Vite
│── index.html          # Estructura base de la app
│── capacitor.config.json
│── package.json
│── vite.config.js

- Comandos principales
Instalar dependencias
npm install

Ejecutar en modo desarrollo
npm run dev

Generar la versión final (carpeta dist/)
npm run build

Sincronizar cambios con Android
npx cap sync

Abrir proyecto Android en Android Studio
npx cap open android
