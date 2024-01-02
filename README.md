# Fullstack Blog Application 


This full-stack blog application is built using the MERN stack (MongoDB, Express, React, Node.js). The state management is handled using Zustand instead of Redux. Users can enjoy features like post categorization, pagination, commenting, and a dual Dark & Light theme UI. Admins have access to additional functionalities in the Admin Dashboard, including analytics on post content and views.

&nbsp;

## Technologies Used:

1. ReactJs
2. NodeJs (Node version 18 or above)
3. ExpressJs
4. MongoDB (Database)
5. Tailwind CSS (for Styling)
6. Zustand (for State Management)

&nbsp;



## Environment variables
First, create the environment variables file `.env` in the server folder. The `.env` file contains the following environment variables:

- MONGODB_URL = `your MongoDB URL`
- JWT_SECRET_KEY = `any secret key - must be secured`
- PORT = `8800` or any port number
- AUTH_EMAIL = `your email address to send the OTP`
- AUTH_PASSWORD = `password to your email account` (used Hotmail for email verification)

&nbsp;


## Steps to run server

1. Open the project in any editor of choice.
2. Navigate into the server directory `cd server`.
3. Run `npm i` to install the packages.
4. Run `npm start` to start the server.

If configured correctly, you should see a message indicating that the server is running successfully and `Database Connected`.

&nbsp;

# Client Side Setup

## Environment variables
First, create the environment variables file `.env` in the client folder. The `.env` file contains the following environment variables:

- REACT_APP_GOOGLE_CLIENT_ID = `Google client ID for Google Sign In`
- REACT_APP_FIREBASE_API_KEY = `Firebase key`

## Steps to run client

1. Navigate into the client directory `cd client`.
2. Run `npm i` to install the packages.
3. Run `npm start` to run the app on `http://localhost:3000`.
4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

&nbsp;
