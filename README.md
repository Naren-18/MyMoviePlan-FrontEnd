# 💊 MEDICARE

MEDICARE is a full-stack web application built with React.js and Spring Boot. It is designed to facilitate online medicine search and ordering, providing a comprehensive healthcare platform for users and administrators.

## 🚀 Features

- 🔍 **Medicine Search** - Users can search for medicines by name, category, or medical condition
- 🛒 **Order Management** - Place orders and track medicine deliveries in real time  
- 👤 **User Authentication** - Secure login and registration with JWT token-based authentication
- 👨‍💼 **Admin Dashboard** - Manage medicine inventory, user accounts, and order status
- 📦 **Inventory Management** - Real-time stock updates and low-stock alerts
- 💳 **Secure Checkout** - Integrated payment processing with order confirmation

## 🗂️ Project Structure
```bash
medicare/
├── medicare-backend/ # Spring Boot backend (APIs, authentication, inventory, orders)
│ ├── src/ # Java source code
│ ├── pom.xml # Maven dependencies
│ └── ...
│
├── medicare-frontend/ # React.js frontend (UI, components, routing)
│ ├── public/ # Static files
│ ├── src/ # React components, pages, services
│ ├── package.json # Frontend dependencies
│ └── ...
│
├── README.md # Project documentation
└── .gitignore # Git ignore rules
