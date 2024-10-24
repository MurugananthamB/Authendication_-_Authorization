# User Authentication and Authorization with Bearer Token

This project implements a basic user authentication and authorization system using **Node.js**, **Express.js**, **Mongoose (MongoDB)**, and **JWT (JSON Web Tokens)**. The application follows the MVC pattern and includes API documentation for ease of use.

## Features

- User Registration
- User Login with JWT generation
- Middleware for JWT verification
- Protected route to get user information
- Clean and readable code following the MVC structure
- Comprehensive error handling and validation
- Postman API documentation with sample requests and responses

## Tech Stack

- **Node.js**
- **Express.js**
- **Mongoose** (MongoDB)
- **JWT** (JSON Web Token)
- **Postman** (for API testing and documentation)

## API Endpoints

### 1. User Registration
- **Endpoint:** `POST /register`
- **Description:** Registers a new user with hashed password.

### 2. User Login
- **Endpoint:** `POST /login`
- **Description:** Authenticates user and returns a JWT token.

### 3. Get User Info (Protected)
- **Endpoint:** `GET /user`
- **Description:** Returns user information if a valid JWT is provided.

## Deployment

The application can be deployed using [Render](https://render.com/). Make sure to push your code to GitHub and deploy it by following the platform's guidelines.

## Documentation

Detailed API documentation is available via Postman:
- [Postman API Documentation](https://www.postman.com/)
- [JWT Documentation](https://jwt.io/)

## License

This project is licensed under the MIT License.
