# User Management Application

This is a user management application that allows users to register, log in, view their profile, and update their profile information. It is built using **React**, **Redux**, **Node.js**, and **Express.js**. The backend is connected to a **MongoDB** database and uses **JWT authentication** for user sessions.

## Features

- **User Registration**: New users can register by providing their email and password.
- **User Login**: Existing users can log in with their credentials.
- **View Profile**: Authenticated users can view their profile information.
- **Update Profile**: Users can update their profile information (e.g., name, email).
- **Authentication**: JWT tokens are used for secure authentication.

## Tech Stack

- **Frontend**: React, Redux (with Thunk middleware), Zod validation
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

<h1>Please make Changes on core policisy while using it</h1>
const coreOptions = {
  origin: "http://localhost:5173",  // Add the URL from which the frontend will be making requests to the backend.
  methods: "GET, POST, PUT, DELETE, PATCH, HEAD",
  credentials: true, // Allow credentials (cookies, HTTP authentication) to be sent with requests.
};


during cloning it please re install some dev dependencies
