# Prokart: Full-Stack E-Commerce Application

A robust, full-stack e-commerce platform designed to handle online shopping workflows with secure, role-based access. Built with a component-driven Angular frontend and a RESTful Spring Boot backend, this application manages products, user orders, and customer reviews through a normalized MySQL database.

## 🚀 Tech Stack

**Frontend:** Angular, TypeScript, HTML/CSS
**Backend:** Java, Spring Boot, Spring Security
**Database:** MySQL
**Authentication:** JSON Web Tokens (JWT)

## ✨ Key Features

### Security & Architecture
* **Role-Based Access Control (RBAC):** Secured via Spring Security and JWT, strictly separating privileges between standard users and administrators.
* **Service-Driven Frontend:** Built with a component-based Angular architecture, utilizing client-side routing across 10+ dynamic pages for a seamless Single Page Application (SPA) experience.
* **RESTful Backend:** Powered by 15+ REST APIs built with Spring Boot, handling all business logic, data persistence, and secure client-server communication.

### 🛍️ User Panel
* **Product Browsing:** View, search, and filter through the product catalog (e.g., browsing for items like "The Coffee Club" t-shirts or "Delicioso Brown" Nobero cargo pants).
* **Shopping Cart & Checkout:** Securely add items to the cart and process orders.
* **Review System:** Leave ratings and feedback on purchased products.
* **Account Management:** Secure login, registration, and order history tracking.

### ⚙️ Admin Panel
* **Inventory Management:** Full CRUD (Create, Read, Update, Delete) operations for the product catalog.
* **Order Tracking:** Monitor platform-wide order statuses and fulfillment.
* **User Management:** Oversee registered accounts and platform activity.

## 🗄️ Database Schema

The application relies on a highly normalized MySQL schema designed for data integrity and performance, featuring key relations including:
* **Users:** Managing credentials, roles (Admin/User), and profile data.
* **Products:** Storing item details, pricing, stock levels, and categories.
* **Orders:** Tracking user purchases, timestamps, and payment statuses.
* **Reviews:** Linking user feedback directly to specific products.

## 🛠️ Getting Started

### Prerequisites
* Java Development Kit (JDK) 17+
* Node.js and npm
* Angular CLI
* MySQL Server

### Backend Setup (Spring Boot)
1. Navigate to the backend directory.
2. Update the `application.properties` file with your MySQL database credentials:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/prokart_db
   spring.datasource.username=root
   spring.datasource.password=your_password
