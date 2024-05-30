# Vidly NodeJs Project

## Overview
Vidly is a simple movie rental application built with Node.js, Express, and MongoDB. This project demonstrates fundamental concepts of building RESTful APIs with Node.js.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- Joi (for validation)
- Winston (for logging)
- bcrypt (for password hashing)
- jsonwebtoken (for authentication)

## Features
- User authentication and authorization
- CRUD operations for movies, customers, and rentals
- Input validation
- Error handling
- Logging

## API Endpoints

### Movies

- **GET /api/movies**: Get all movies
- **GET /api/movies/:id**: Get a movie by ID
- **POST /api/movies**: Create a new movie
- **PUT /api/movies/:id**: Update a movie
- **DELETE /api/movies/:id**: Delete a movie

### Customers

- **GET /api/customers**: Get all customers
- **GET /api/customers/:id**: Get a customer by ID
- **POST /api/customers**: Create a new customer
- **PUT /api/customers/:id**: Update a customer
- **DELETE /api/customers/:id**: Delete a customer

### Rentals

- **GET /api/rentals**: Get all rentals
- **GET /api/rentals/:id**: Get a rental by ID
- **POST /api/rentals**: Create a new rental

### Users

- **POST /api/users**: Register a new user
- **GET /api/users/me**: Get current user (requires authentication)

### Auth

- **POST /api/auth**: Authenticate user and get a token

## Testing
- **Unit Tests:** Using Jest and Supertest for testing individual units of the application in isolation.
- **Integration Tests:** Testing the interaction between different layers.
