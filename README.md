# MERN Ecommerce

<p align="center">
  <img width="200" src="https://github.com/CloudySkyDeveloper/Ecommerce/releases" alt="Ecommerce Logo">
</p>

## Overview

Welcome to the **MERN Ecommerce** repository! This project aims to deliver a seamless shopping experience with robust features for both customers and administrators. The platform includes product management, user authentication, shopping cart functionality, wishlists, and order management—all wrapped in a responsive Material UI interface.

## Features

Here are some key features of the **MERN Ecommerce** project:

- **Product Management**: Administrators can easily add, edit, and delete products from the inventory.
- **User Authentication**: Secure user authentication is implemented using JWT tokens for enhanced security.
- **Shopping Cart Functionality**: Customers can add products to their cart for easy checkout.
- **Wishlists**: Users can create wishlists to save products for future purchase.
- **Order Management**: Administrators can manage orders from customers efficiently.

## Repository Topics

- ecommerce
- ecommerce-website
- express
- framer-motion
- jwt-authentication
- material-ui
- mern-ecommerce
- mern-stack
- mongodb
- nodejs
- react
- redux-toolkit

## Project Structure

This project uses **npm workspaces** to manage the monorepo structure:

```
Ecommerce/
├── backend/       # Express.js API server
├── frontend/      # React application
└── package.json   # Root workspace configuration
```

## Installation

To get started with the **MERN Ecommerce** project, please follow these steps:

1. **Clone the repository** to your local machine:

```bash
git clone <repository-url>
cd Ecommerce
```

2. **Install all dependencies** (both backend and frontend) using npm workspaces:

```bash
npm install --legacy-peer-deps
```

> Note: `--legacy-peer-deps` is required due to React version compatibility with some dependencies.

3. **Set up your MongoDB database**:

   - Create a `.env` file in the `backend` directory
   - Add your MongoDB connection string and other environment variables

4. **Start the development servers**:

   **Option 1: Run backend and frontend separately (recommended for development)**

   ```bash
   # Terminal 1 - Start backend
   npm run dev:backend

   # Terminal 2 - Start frontend
   npm run start:frontend
   ```

   **Option 2: Run backend only**

   ```bash
   npm start
   ```

## Available Scripts

### Root Level (Workspace Commands)

- `npm install` - Install all dependencies for both workspaces
- `npm start` - Start the backend server
- `npm run start:frontend` - Start the React frontend development server
- `npm run start:backend` - Start the backend server
- `npm run dev:backend` - Start the backend with nodemon (auto-reload)
- `npm run build:frontend` - Build the frontend for production
- `npm run seed` - Seed the database with initial data
- `npm run clean` - Remove all node_modules and package-lock files

### Workspace-Specific Commands

You can run commands in specific workspaces using:

```bash
npm run <script> --workspace=<workspace-name>
```

Examples:

```bash
# Backend commands
npm run dev --workspace=backend
npm run seed --workspace=backend

# Frontend commands
npm run build --workspace=frontend
npm run test --workspace=frontend
```

## Learn More

For more details on how to use and customize the **MERN Ecommerce** platform, please refer to the documentation included in the repository.

[![Download App](https://github.com/CloudySkyDeveloper/Ecommerce/releases)](https://github.com/CloudySkyDeveloper/Ecommerce/releases)

If the link ends with a file name, make sure to unzip and launch the application.

## Get Involved

We welcome contributions from the community to enhance the **MERN Ecommerce** project. Feel free to submit pull requests, report issues, or suggest new features!

## Stay Connected

For the latest updates and announcements, follow us on [Twitter](https://github.com/CloudySkyDeveloper/Ecommerce/releases) and [LinkedIn](https://github.com/CloudySkyDeveloper/Ecommerce/releases).

---

Thank you for checking out the **MERN Ecommerce** repository. We hope this project helps you build amazing e-commerce applications with ease! 🌟🚀

![Ecommerce Screenshot](https://github.com/CloudySkyDeveloper/Ecommerce/releases)
