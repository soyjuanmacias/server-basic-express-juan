----
THIS README IS UNDER CONSTRUCTION, please, be patient.

------
# Server basic express config


Here you have a basic config for a server with [Node.js](https://nodejs.org/es/) and [Express](https://www.npmjs.com/package/express).

# Pre-installed packages (Alphabetical order)
## [bcrypt](https://www.npmjs.com/package/bcrypt)
- Lib to help you hash passwords.
  -  We use it with [passport.](#passport)

## [Connect ensure login](https://www.npmjs.com/package/connect-ensure-login)
- This middleware ensures that a user is logged in.
  - If a request is received that is unauthenticated, the request will be redirected to a login page.
  - The URL will be saved in the session, so the user can be conveniently returned to the page that was originally requested.

## [Mongoose](https://www.npmjs.com/package/mongoose)
- Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.

## [Passport](https://www.npmjs.com/package/passport)





Original credits: [Xenock](https://github.com/xenock)
