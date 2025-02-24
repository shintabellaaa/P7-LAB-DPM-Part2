# App Backend

A Node.js/Express backend server providing authentication APIs for the RN App.

## Features

- User authentication (login/register)
- JWT token-based authentication
- MongoDB database integration
- Input validation
- Password hashing with bcrypt

## Prerequisites

- Node.js
- MongoDB
- npm

## Installation

1. Clone the repository
2. Install dependencies:
```sh
npm install express
npm install nodemon
npm install mongoose
npm install cors
npm install bcrypt
npm install jsonwebtoken
```
3. Create a `.env` file in the root directory and add the following environment variables:
```sh
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=3000
HOST=your_host_ip
```

## Usage
- Start the server:
```sh
npm start
```
- The server will run on `http://localhost:3000`

## API Endpoints

### Auth Routes

- POST `/api/auth/register`
- POST `/api/auth/login`

#   P 7 - L A B - D P M - B A C K E N D  
 #   P 7 - F R O N T E N D - L A B - D P M  
 #   P 7 - L A B - D P M - P a r t 2  
 