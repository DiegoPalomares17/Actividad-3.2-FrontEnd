Aromas del Alma - Proyecto Web con Webpack
Requisitos previos
Tener instalado Node.js (versión recomendada 16 o superior)

Tener instalado npm (viene con Node.js)

Instalación
1- Clona o descarga este repositorio en tu equipo.
2- Abre una terminal y navega a la carpeta raíz del proyecto.
3- Ejecuta el siguiente comando para instalar las dependencias necesarias: 
- npm install
4- Ejecuta el siguiente comando para minificar y configurar los archivos:
- npm run build

Scripts disponibles
El proyecto incluye dos scripts principales para ejecutar tareas comunes:
- npm start — Inicia un servidor de desarrollo local con hot reload.
- npm run build — Compila y minifica el proyecto para producción en la carpeta dist.

Ejecución paso a paso
1. Ejecutar el servidor de desarrollo
Para trabajar en modo desarrollo y ver los cambios en tiempo real:
- npm start
Esto iniciará un servidor local en http://localhost:8080.
El navegador se abrirá automáticamente mostrando la página.
Cada vez que modifiques los archivos en src/, el navegador se actualizará automáticamente (hot reload).

2. Crear una versión lista para producción
Cuando quieras generar los archivos optimizados y minificados para subir a producción:
npm run build
Esto creará una carpeta dist/ con los archivos compilados:

bundle.[contenthash].js (JavaScript minificado)
styles.[contenthash].css (CSS extraído y minificado)
El archivo HTML minificado listo para usarse.

Estos archivos están optimizados para un mejor rendimiento en producción.

Estructura básica de archivos
/src
  ├── index.js         # Punto de entrada JS
  ├── index.html       # Archivo HTML base
  └── style.css        # Estilos CSS
/dist                   # Carpeta generada tras build (no en repositorio)