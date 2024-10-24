# User Authentication and Authorization with JWT
This is a Node.js application that implements user authentication and authorization using Bearer tokens (JWT). 
It follows the MVC pattern and uses Express.js, Mongoose (MongoDB), and JWT for secure token-based authentication.

The application will run on `http://localhost:3000`

## Features
- User Registration
- User Login
- Password Hashing using Node.js crypto module
- JWT-based Authentication (Bearer Tokens)
- Protected routes for authenticated users
- MongoDB database with Mongoose
- Detailed API documentation with sample requests and responses
- Proper error handling and input validation

## Tech Stack
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT (JSON Web Tokens) for authentication
- Postman for API testing and documentation
- dotenv for environment variable management

## API Endpoints

1. **User Registration**
   
- URL: `POST /api/users/register` <br>
- Description: Register a new user.

### Request

```json
{
  "username": "azhagukarthikeyan",
  "email": "karthiazhagu0@gmail.com",
  "password": "password@1234"
}
```

### Response

```json
{
  "message": "User registered successfully"
}
```

2. **User Login**
   
- URL: `POST /api/users/login`
- Description: Authenticate user and return JWT.

### Request 

```json
{
  "email": "john@example.com",
  "password": "password123"
}
```

### Response

```json
{
  "token": "your_jwt_token"
}
```


## Postman Documentation
The API endpoints can be tested using Postman. Sample requests and responses are included for each endpoint. Import the Postman collection or manually set up the requests.

## License
This project is licensed under the MIT License.
