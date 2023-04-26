# Plantilla API REST
🇬🇧 [English](../README.md) | 🇪🇸 Español

Este proyecto es una plantilla que te permitirá crear rápidamente una API REST con todas las librerías y estructura de carpetas necesarias. Con él, podrás ahorrar tiempo y esfuerzo al no tener que escribir el código desde cero cada vez que necesites crear una API.

Esta API está diseñada para trabajar con una base de datos Postgresql, pero puedes añadir otro tipo de base de datos si así lo deseas, aunque deberás añadir las librerías necesarias para ello y modificar el archivo ```/src/database/database.conexion.ts```

## Requisitos previos

Antes de comenzar a utilizar este proyecto, asegúrate de tener instalado lo siguiente:

- Node.js (versión 16 o superior)

## Instalación

Para instalar y utilizar este proyecto, sigue estos sencillos pasos:

1. Clona este repositorio en tu máquina local.
2. Abre una terminal y navega hasta la carpeta raíz del proyecto.
3. Ejecuta el comando ```npm install``` para instalar todas las dependencias necesarias.
4. Crea una base de datos PostgreSQL (u otra de tu elección).
5. Renombra el archivo ```.env.example``` a ```.env``` y cambia los valores de las variables por aquellos que correspondan.
6. Renombra el archivo ``.gitignore-example`` a ```.gitignore``` y modifícalo según tus necesidades.

## Estructura de carpetas

La estructura de carpetas del proyecto es la siguiente:

    src
    |--controllers
        |--database.conexion.ts
    |--helpers
    |--interfaces
    |--models
    |--routes
        |--index.ts
    |--services
    |--app.ts
    |--index.ts

## ***Datos del autor*** 👨‍💻
#### 🙋‍♂️ Nombre: Juan Hidalgo Yañez
#### 🐙 GitHub: https://github.com/Juan-Jose-Hidalgo
#### 💼 Visita mi perfil en [LinkedIn](https://www.linkedin.com/in/juan-jos%C3%A9-hidalgo-ya%C3%B1ez-854698b4/)
#### 📨 Correo electrónico: juanhidalgoyanez@gmail.com