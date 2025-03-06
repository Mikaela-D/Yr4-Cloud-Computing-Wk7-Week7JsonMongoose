# Week7JsonMongoose

This project demonstrates the use of Express.js with Mongoose for handling JSON data in a MongoDB database.

## Routes

- `GET /addProduct`: Adds a new product to the database.
- `GET /`: Retrieves all products from the database.
- `POST /`: Retrieves all products from the database and returns them in JSON format.
- `GET /getSpecificProduct`: Retrieves a specific product based on the `ourId` query parameter.
- `POST /getSpecificProduct`: Retrieves a specific product based on the `ourId` in the request body.
- `GET /updateSpecificProduct`: Updates the price of a specific product with `ourId` of '1'.
- `GET /deleteSpecificProduct`: Deletes a specific product with `ourId` of '0'.

## Setup

1. Install dependencies:
    ```bash
    npm install
    ```

2. Start the server:
    ```bash
    npm start
    ```

## Dependencies

- Express
- Mongoose
