# TWC Test API - Developed by Shakya Rupasinghe

## Description
This API serves as the backend for the TWC Test project. It provides endpoints to manage contacts including fetching all contacts, adding a new contact, updating an existing contact, and deleting a contact.

The API is built using Node.js and Express.js for handling HTTP requests, and MongoDB Atlas for database storage.

## Running the API
1. Clone this repository to your local machine.
2. Navigate to the `API` directory in your terminal.
3. Install the dependencies by running the following command:npm install
4. Ensure you have MongoDB Atlas set up and running, and replace the connection string in `server.js` with your own MongoDB connection string.
5. Start the server by running the following command:npm start

## Testing with Postman

## MongoDB Connection
Ensure you have MongoDB Atlas set up and running. Replace the MongoDB connection string in `server.js` with your own connection string.

## Endpoints
- `GET /api/contacts`: Retrieve all contacts.
- `POST /api/contacts`: Add a new contact.
- `DELETE /api/contacts/:id`: Delete a contact by ID.
- `PUT /api/contacts/:id`: Update a contact by ID.

## Dependencies
- Express.js: Web framework for Node.js.
- Mongoose: MongoDB object modeling tool.
- CORS: Middleware for enabling Cross-Origin Resource Sharing.

## Environment Variables
- PORT: Port number for the server. Default is 5000.




