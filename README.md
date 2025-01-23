# TODO App

A simple TODO App just made a bit "FullStack". 🔨

https://github.com/its-id/TODO-MERN-APP/assets/60315832/7fa469e5-07cc-4401-a936-fe12aeab7b49

## Basic Features

- User can login and signup to save his/her todos.
- User can create a Todo.
- User can see their Todos
- User can mark the Todo as done.

## Add-On Work

- Email verification w/o OTP, JWT Authentication & Route Protection.
- Coded entirely in TS (FE & BE, including TYPE validation).
- Complete CRUD operations and DB storage.
- State Management using Context.
- Adheres industry standard coding practices.

## Future Works

- Giving User Todos based on selected date.
- Implementing OTP verification, Google and other third party auth.
- Maybe some UI revamps.

> **Tech Stack Used:** React, Node, Express, MongoDB, TS. <br/> > **Additional Libraries:** Tailwind, deep-email-validator, jsonwebtoken, zod, react-router-dom, axios.

## Instructions to Run Locally

### First, run the Backend

1.  `cd backend`
2.  `npm i`
3.  Create the .env file containing the following data: Your MongodDB conection URL, Your JWT secret and Frontend URL. (check .env.example for the format)
4.  `npm run dev`

### Frontend

1. `cd frontend`
2. `npm i`
3. Create the .env file containing the following data: URL backend. (check .env.example for the format)
4. `npm run dev`

## Some Issues you can encounter

If get the **`punnycode`** error when running the backend. Simply:

1. Go to `node_modules` of backend.
2. Look for the folder **tr46**.
3. Go to index.js and
   ```
   // Replace this:
   const punycode = require('punycode');
   // With this:
   const punycode = require('punycode/');
   ```

Always open to any issues or collaborations. Let's go 🚀

## Original author of initial code: https://github.com/its-id/TODO-MERN-APP
