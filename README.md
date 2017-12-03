----
THIS README IS UNDER CONSTRUCTION, please, be patient.

------
# Basic and empty Node.js & Express.js server  with auth ready for start to code


Here you have a basic config for a server with [Node.js](https://nodejs.org/es/) and [Express](https://www.npmjs.com/package/express) and authentication with [Passport](https://www.npmjs.com/package/passport).

Project created by [Juan Macías](http://github.com/soyjuanmacias) with original idea by [Xenock](http://github.com/xenock).
Link to the [original repository](https://github.com/soyjuanmacias/server-basic-express-juan)

This repository contains a server with the necessary packages to start any project in Node.js

Everything is installed, you only have to run:
```javascript
npm install --save
```
And you will install all packages with this command.

## Features:
- App.js only 10 lines:

![App.js](https://image.prntscr.com/image/zTr0WUcZSYSAz20MbxeQrw.png)
- Design with MVC pattern (Model, View, Controller)
- Work with controllers folder where we take on all our project action. Cleaner and tidier code.
- Middleware for save user data and send it in all requests (res.locals.user)

# Pre-installed packages (By alphabetical order)

## [Bcrypt](https://www.npmjs.com/package/bcrypt)

- Lib to help you hash passwords.
  -  We use it with [passport.](#passport)

## [Body parser](https://www.npmjs.com/package/body-parser)
- Parse incoming request bodies in a middleware before your handlers, available under the req.body property.
  - So, without body parser you can't do req.body.foo

## [Connect ensure login](https://www.npmjs.com/package/connect-ensure-login)
- This middleware ensures that a user is logged in.
  - If a request is received that is unauthenticated, the request will be redirected to a login page.
  - The URL will be saved in the session, so the user can be conveniently returned to the page that was originally requested.

## [Cookie-parser](https://www.npmjs.com/package/cookie-parser)
- Parse Cookie header and populate req.cookies with an object keyed by the cookie names. Optionally you may enable signed cookie support by passing a secret string, which assigns req.secret so it may be used by other middleware.

## [Mongoose](https://www.npmjs.com/package/mongoose)
- Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.
We use this for create schema models for MongoDB and make sure that the data we save in Mongo is correct.

## [Debug](https://www.npmjs.com/package/debug)
- A tiny JavaScript debugging utility modelled after Node.js core's debugging technique. Works in Node.js and web browsers.
![Debug](https://user-images.githubusercontent.com/71256/29091486-fa38524c-7c37-11e7-895f-e7ec8e1039b6.png

## [Dotenv](https://www.npmjs.com/package/dotenv)
- Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. Storing configuration in the environment separate from code is based on The Twelve-Factor App methodology.

## [EJS](https://www.npmjs.com/package/ejs)
- EJS is an embedded Javascript templating library for render and show the view in our server.

## [Express](https://www.npmjs.com/package/express)
- The crown jewel for Node.js. Fast and minimalist web framework with routing, and others great features. It will allow us to create the model view controller easily and simply. Simplifying everything to create our backend easily.

## [Express EJS Layouts](https://www.npmjs.com/package/express-ejs-layouts)
- Layout support for ejs in express.

## [Express-session](https://www.npmjs.com/package/express-session)
- This is a Node.js module available through the npm registry. Installation is done using the npm install command
```javascript
$ npm install express-session
```

## [Mongoose](https://www.npmjs.com/package/mongoose)
- Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.

## [Morgan](https://www.npmjs.com/package/morgan)
- HTTP request logger middleware for node.js

## [Passport](https://www.npmjs.com/package/passport)
- Passport's sole purpose is to authenticate requests, which it does through an extensible set of plugins known as strategies. Passport does not mount routes or assume any particular database schema, which maximizes flexibility and allows application-level decisions to be made by the developer. The API is simple: you provide Passport a request to authenticate, and Passport provides hooks for controlling what occurs when authentication succeeds or fails.


## [Passport-local](https://www.npmjs.com/package/passport-local)
- Passport strategy for authenticating with a username and password.

- This module lets you authenticate using a username and password in your Node.js applications. By plugging into Passport, local authentication can be easily and unobtrusively integrated into any application or framework that supports Connect-style middleware, including Express.



# Español
# Basic and empty Node.js & Express.js server  with auth ready for start to code

Aquí tienes la configuración básica para un servidor montado con [Node.js](https://nodejs.org/es/) y [Express](https://www.npmjs.com/package/express) con autentificación con [Passport](https://www.npmjs.com/package/passport).

Proyecto creado por [Juan Macías](http://github.com/soyjuanmacias) con idea original de [Xenock](http://github.com/xenock).
Enlace al [repositorio original](https://github.com/soyjuanmacias/server-basic-express-juan)

Este repositorio contiene un servidor con los paquetes necesarios para iniciar cualquier proyecto en Node.js

Todo está requerido en el archivo package.json, solo tienes que descargar este repositorio y ejecutar:
```javascript
npm install --save
```
Y tendrás instalados todos los paquetes con ese comando.

## Características:
- App.js solo 10 líneas:

![App.js](https://image.prntscr.com/image/zTr0WUcZSYSAz20MbxeQrw.png)
- Diseño siguiendo el patrón MVC (Modelo, Vista, Controlador)
- En lugar de llevar a cabo la acción del controlador en las rutas, pasamos a ejecutar las acciones al controlador. Código mas limpio y ordenado.
- Middeware para guardar los datos del usuario y enviarlo a cualquier petición. (res.locals.user)

Idea original: [Xenock](https://github.com/xenock)
