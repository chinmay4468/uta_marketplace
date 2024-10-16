# Student Marketplace

A web-based platform designed to connect students within a specific educational institution or across multiple institutions, enabling them to buy and sell goods in a safe, secure, and convenient manner. This marketplace fosters community and supports a circular economy by simplifying the process of listing and purchasing student-related items.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Authentication**: Secure registration and login for student accounts.
- **Product Listings**: Students can list items for sale with details like images, descriptions, and pricing.
- **Wishlist**: Users can save items for future reference.
- **Messaging System**: Chat feature for direct communication between buyers and sellers.
- **Admin Panel**: Tools for administrators to manage listings and monitor platform activity.
- **Responsive Design**: Frontend optimized for desktop and mobile devices.

## Tech Stack
### Frontend
- **React** with **Vite**: Provides fast build tooling and responsive UI.
- **Tailwind CSS**: Used for styling and creating a responsive layout.
- **JavaScript (ES6)**: Scripting for frontend interactivity.

### Backend
- **PHP**: Manages backend logic for handling requests, sessions, and database operations.
- **MySQL**: Stores user data, listings, and messages in a relational database.

## Installation
### Prerequisites
- [Node.js and npm](https://nodejs.org/) (for frontend setup)
- [PHP and MySQL](https://www.apachefriends.org/index.html) (for backend setup)

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend

   npm install

   npm run dev
cd student-marketplace-backend


Usage
Access the frontend at http://localhost:3000.
Access the backend at http://localhost:8000.
Register a new account, create listings, add items to your wishlist, and use the chat feature to communicate with other users.

STUDENT_MARKETPLACE/
├── frontend/                # Frontend application (React, Tailwind CSS)
│   ├── src/
│   ├── public/
│   └── vite.config.js       # Vite configuration
└── student-marketplace-backend/
    ├── DatabaseConnection.php
    ├── login.php            # User login
    ├── register.php
    ├── listings/            # Handles listings
    ├── wishlist/            # Manages user wishlists
    └── chat/                # Chat feature for user interaction
Contributing
Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request.

