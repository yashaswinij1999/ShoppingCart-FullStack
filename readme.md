# ShoppingCart-FullStack

This is a full-stack shopping cart application that allows users to browse products, add them to their cart, and manage their cart. The frontend is built with React, and the backend is powered by Express.js.

## Table of Contents

- [ShoppingCart-FullStack](#shoppingcart-fullstack)
  - [Table of Contents](#table-of-contents)
  - [Prerequisites](#prerequisites)
  - [Project Structure](#project-structure)
  - [Installation](#installation)
    - [Frontend Setup](#frontend-setup)
    - [Backend Setup](#backend-setup)
    - [Running the Application](#running-the-application)
  - [Features](#features)
  - [Concepts Used](#concepts-used)
    - [Frontend](#frontend)
    - [Backend](#backend)
  - [Frontend](#frontend-1)
    - [Components and Hooks](#components-and-hooks)
  - [Backend](#backend-1)
    - [API Endpoints](#api-endpoints)
  - [Middleware and Controllers](#middleware-and-controllers)

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en)

## Project Structure

The project is organized into two main directories:

- **backend** - Contains the Node.js backend.
- **frontend** - Contains the React frontend.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yashaswinij1999/shopping-cart-fullstack.git

   ```

2. Navigate to the project directory:

   ```
   cd shopping-cart-fullstack

   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```
   cd frontend
   ```
2. Install dependencies:

   ```
   npm install

   ```

3. Start the frontend development server:

   ```
   npm run dev

   ```

   The frontend development server will run on http://localhost:5173.

### Backend Setup

1. Navigate to the backend directory:

   ```
   cd backend

   ```

2. Install dependencies:

   ```
   npm install

   ```

3. Start the backend server:
   ```
   node index.js
   ```

The backend server will run on http://localhost:3000.

### Running the Application

- Ensure the backend server is running (see Backend Setup).
- Ensure the frontend development server is running (see Frontend Setup).
- Open your browser and navigate to http://localhost:5173 to see the Todo application.

## Features

- Browse and view products.
- Add products to the cart.
- increment product quantities in the cart.
- decrement the product quanties in the cart.
- remove products from the cart.

## Concepts Used

### Frontend

- **React:** A JavaScript library for building user interfaces.
- **React Router:** For routing within the application.
- **useContext:** For state management.
- **useReducer:** For complex state logic.
- **useEffect:** For fetching the products data.
- **useState:** For managing local component state

### Backend

- **Express:** A web application framework for Node.js
- **CORS:** Middleware for enabling Cross-Origin Resource Sharing.
- **Router:** For defining API routes.
- **Controller:** For handling business logic.
- **REST API:** For interacting with the frontend.

## Frontend

### Components and Hooks

- **React Router:** Used for routing between different pages in the application.
- **useContext:** Used to create a context for managing global state.
- **useReducer:** Used to handle state changes in a predictable manner.
- **useEffect:** Used to fetch data from the backend API and perform other side effects.
- **useState:** Used to manage component-specific state.

## Backend

### API Endpoints

- **GET /shoppingcart/products/:** Fetch the data of the shopping cart.
- **POST /shoppingcart/cart/addToCart:** Add a new product to the cart.
- **GET/shoppingcart/cart/getCart:** Fetch the data of products added to the cart.
- **PATCH /shoppingcart/cart/update/:id:** Update the quantity of a product in the cart.
- **PATCH /shoppingcart/cart/decrement/:id:** Decrease the quantity of a product in the cart.

## Middleware and Controllers

- **Express Router:** Used to define and manage routes.
- **CORS:** Used to allow cross-origin requests.
- **Controllers:** Handle the business logic for each route.
