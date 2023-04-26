# REST API template
🇬🇧 English | 🇪🇸 [Español](./docs/LEEME.md)

This project is a template that will allow you to quickly create a REST API with all the necessary libraries and folder structure. With it, you can save time and effort by not having to write the code from scratch every time you need to create an API.

This API is designed to work with a Postgresql database, but you can add another type of database if you wish. However, you will need to add the necessary libraries for it and modify the `/src/database/database.conexion.ts` file.

## Prerequisites

Before you can use this REST API template, you will need to have the following installed on your machine:

- Node.js (versión 16 or higher)

## Instalation

To install and use this project, follow these simple steps

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the root folder of the project.
3. Run the command `npm install` to install all the necessary dependencies.
4. Create a PostgreSQL database (or another of your choice).
5. Rename the file `.env.example` to `.env` and change the values of the variables to those that correspond.
6. Rename the file `.gitignore-example` to `.gitignore` and modify it according to your needs

## Folder Structure

The folder structure of this REST API template is as follows:

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

## ***Author's information*** 👨‍💻
#### 🙋‍♂️ Name: Juan Hidalgo Yañez
#### 🐙 GitHub: https://github.com/Juan-Jose-Hidalgo
#### 💼 Visit my profile in [LinkedIn](https://www.linkedin.com/in/juan-jos%C3%A9-hidalgo-ya%C3%B1ez-854698b4/)
#### 📨 Email: juanhidalgoyanez@gmail.com
