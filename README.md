# Web Application Project

## Overview
This project is a web application that consists of a frontend built with React and a backend built with Node.js and Express. The application allows users to interact with products, manage their accounts, and place orders.

## Project Structure
The project is organized into two main directories: `frontend` and `backend`.

### Frontend
- **src/components**: Contains reusable React components used throughout the application.
- **src/pages**: Contains different pages of the application, each representing a unique view.
- **src/App.tsx**: The main component of the React application that sets up routing and renders the main layout.
- **src/index.tsx**: The entry point of the React application that renders the App component into the DOM.
- **package.json**: Configuration file for npm in the frontend, listing dependencies and scripts.
- **tsconfig.json**: TypeScript configuration file specifying compiler options and files to include.

### Backend
- **src/controllers**: Contains controllers for handling requests related to products, users, and orders.
  - **productsController.ts**: Handles product-related requests.
  - **usersController.ts**: Handles user-related requests.
  - **ordersController.ts**: Handles order-related requests.
- **src/models**: Contains models defining the structure of product, user, and order objects.
  - **product.ts**: Defines the Product model.
  - **user.ts**: Defines the User model.
  - **order.ts**: Defines the Order model.
- **src/routes**: Contains route definitions for products, users, and orders.
  - **products.ts**: Sets up routes for product-related requests.
  - **users.ts**: Sets up routes for user-related requests.
  - **orders.ts**: Sets up routes for order-related requests.
- **src/app.ts**: Entry point of the backend application that creates an Express app, sets up middleware, and initializes routes.
- **src/types**: Contains TypeScript interfaces defining types used in the backend.
  - **index.ts**: Exports interfaces for Product, User, and Order.
- **package.json**: Configuration file for npm in the backend, listing dependencies and scripts.
- **tsconfig.json**: TypeScript configuration file specifying compiler options and files to include.

## Setup Instructions

### Frontend
1. Navigate to the `frontend` directory.
2. Install dependencies using:
   ```
   npm install
   ```
3. Start the development server using:
   ```
   npm start
   ```

### Backend
1. Navigate to the `backend` directory.
2. Install dependencies using:
   ```
   npm install
   ```
3. Start the backend server using:
   ```
   npm start
   ```

## Features
- User authentication and management
- Product listing and management
- Order placement and tracking

## Technologies Used
- Frontend: React, TypeScript
- Backend: Node.js, Express, TypeScript

## License
This project is licensed under the MIT License.