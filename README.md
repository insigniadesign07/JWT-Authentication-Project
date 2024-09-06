## JWT Authentication Project

### Setup Instructions

1. Clone the repository
2. Run `npm install` to install dependencies
3. Create a `.env` file and add your `JWT_SECRET` and `MONGO_URI`
4. Start the server with `node server.js`
5. Use Postman to test the API

### API Endpoints

- **POST /api/auth/register:** Register a new user
- **POST /api/auth/login:** Login a user and receive a JWT
- **GET /api/users:** Access protected route (requires JWT)
