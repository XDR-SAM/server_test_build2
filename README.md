# Simple CRUD Server

This is a simple CRUD (Create, Read, Update, Delete) server built with Express.js and MongoDB. It provides basic API endpoints for managing a collection of users.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Make sure you have MongoDB installed and running. Update the MongoDB connection URI in `index.js`:
   ```javascript
   const uri = 'mongodb://localhost:27017';
   ```

## Usage

Start the server:

```bash
npm start
```

The server will start on port 3000.

## API Endpoints

*   `GET /users`: Get all users.
*   `GET /users/:id`: Get a single user by ID.
*   `POST /users`: Create a new user.
*   `PATCH /users/:id`: Update a user's information.
*   `DELETE /users/:id`: Delete a user.
