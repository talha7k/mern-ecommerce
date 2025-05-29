# MERN E-Commerce Website

Welcome to the MERN E-Commerce Website! This project is a feature-rich e-commerce application built using the powerful MERN stack, featuring an intuitive user-facing store and a comprehensive admin dashboard.

## ✨ Features

### 🌟 User Frontend
- **🔒 Secure Authentication**: Register, log in, and manage user profiles effortlessly.
- **🛍️ Product Exploration**: Browse and search an extensive product catalog with advanced filtering options.
- **🛒 Shopping Cart**: Add products, modify quantities, and enjoy a hassle-free checkout process.
- **💳 Seamless Payments**: Secure payment processing via Stripe integration.
- **📦 Order Management**: View order history, track deliveries, and manage returns with ease.

### ⚙️ Admin Dashboard
- **🛠️ Product Management**: Add, update, or delete products using a user-friendly interface.
- **📂 Category Management**: Organize products into categories for improved navigation.
- **📑 Order Management**: Efficiently view, process, and update orders.
- **👥 User Management**: Manage user roles and access levels.

## 🛠️ Tech Stack
- **MongoDB**: Robust NoSQL database for storing all application data.
- **Express.js**: Fast and minimalistic backend framework.
- **React.js**: Modern frontend library for dynamic user interfaces.
- **Node.js**: JavaScript runtime environment for the backend.
- **Stripe**: Integrated payment gateway for secure transactions.
- **JWT**: JSON Web Tokens for secure user sessions.

## 🗂️ Folder Structure
```
/ 
├── admin/            # React.js admin frontend code
├── backend/          # Node.js backend code (Express.js)
├── frontend/         # React.js frontend code
├── .gitignore        # Files and folders to be ignored by Git
├── README.md         # Project documentation
```

## 🤸 Quick Start
Follow these steps to set up the project locally on your machine.

### Prerequisites
Ensure you have the following installed:
- Git
- Node.js
- NPM (Node Package Manager)

### Cloning the Repository
```bash
git clone https://github.com/talha7k/mern-ecommerce.git
```

### Installation
Install the project dependencies using npm:
```bash
npm install
```

### Set Up Environment Variables
Create `.env` files in the following directories and configure them with your credentials:
- `/admin/.env`
- `/backend/.env`
- `/frontend/.env`

Replace placeholder values with your actual Appwrite and Stripe credentials.

### Running the Project
1. **Admin Dashboard**:
   ```bash
   cd admin
   npm run dev
   ```
   Open `http://localhost:5174` in your browser to view the admin dashboard.

2. **Backend**:
   ```bash
   cd backend
   npm run server
   ```
   The backend runs on `http://localhost:4000`.

3. **Frontend**:
   ```bash
   cd frontend
   npm run dev
   ```
   Open `http://localhost:5173` in your browser to view the frontend.

## 📬 Contact
For questions or feedback, reach out to:
- **Name**: Talha Khan
- **Email**: talha7k@gmail.com

## 📄 License
This project is licensed under the MIT License.
