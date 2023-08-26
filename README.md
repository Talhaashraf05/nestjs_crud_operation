# CRUD API with Nest.js, MySQL(ORM), and Postman

This document provides an overview of the CRUD (Create, Read, Update, Delete) API that has been developed using Nest.js, MySQL as the database, and Postman for testing HTTP requests.

## Overview

The CRUD API is built using the Nest.js framework, which is a powerful and extensible Node.js framework for building scalable and maintainable applications. The API interacts with a MySQL database using an Object-Relational Mapping (ORM) system for efficient data handling.

## Features

- **Create Operation**: The API allows you to create new records by sending a POST request. It processes the incoming data, validates it, and then stores it in the MySQL database.

- **Read Operation**: You can retrieve data from the database using GET requests. The API supports various query parameters to filter and paginate the results.

- **Update Operation**: Data can be updated using PUT or PATCH requests. The API validates the incoming data and updates the corresponding records in the database.

- **Delete Operation**: Existing records can be deleted by sending DELETE requests. The API identifies the target record and removes it from the database.

## Technologies Used

- **Nest.js**: A progressive Node.js framework for building efficient, scalable, and maintainable server-side applications.

- **MySQL**: A popular open-source relational database management system used for storing and retrieving data.

- **ORM (TypeORM)**: An Object-Relational Mapping library for TypeScript and JavaScript that simplifies database interactions by using classes and objects to represent database tables and records.

- **Postman**: A versatile tool used for testing APIs by sending HTTP requests and receiving responses. It provides a user-friendly interface for making requests and analyzing results.

## Testing with Postman

To test the CRUD API, you can use Postman, which provides a convenient way to interact with the API endpoints:

1. **Installation**: Install Postman on your machine if you haven't already.

2. **Import Collection**: Import the provided Postman collection that includes pre-configured requests for CRUD operations.

3. **Testing Endpoints**:
   - Create: Use the POST request in the collection to add new records.
   - Read: Utilize the GET request to retrieve data from the API.
   - Update: Use PUT or PATCH requests to modify existing records.
   - Delete: Send DELETE requests to remove records.

4. **Inspect Responses**: Postman will display the responses from the API. You can analyze the status codes and data returned to verify the operations.

## How to make it work:
   - Update .env file with your mysql server info such as username,password,database
   - and open terminal in the directory and write npm install 

## Conclusion

In conclusion, the CRUD API developed using Nest.js and MySQL with ORM provides a robust and efficient way to perform CRUD operations on data. Postman simplifies the testing process by allowing easy interaction with the API endpoints.
