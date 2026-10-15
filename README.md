<p align="center">
  <a href="https://github.com/Brajesh31/food-ordering">
    <img src="https://raw.githubusercontent.com/Brajesh31/asset/main/food-ordering-banner.png" alt="Food Ordering Platform Banner">
  </a>
</p>

<div align="center">

# 🍕 Food Ordering & Delivery Platform 🛵

**A complete, real-time food ordering and delivery platform connecting customers, restaurants, and delivery agents in a seamless ecosystem.**

</div>

<p align="center">
  <a href="[LINK_TO_YOUR_LIVE_DEMO]">
    <img src="https://img.shields.io/badge/Live-View_Demo-brightgreen?style=for-the-badge&logo=vercel" alt="Live Demo">
  </a>
  &nbsp;
  <img src="https://img.shields.io/github/stars/Brajesh31/food-ordering?style=for-the-badge&color=gold" alt="Stars">
  &nbsp;
  <img src="https://img.shields.io/github/license/Brajesh31/food-ordering?style=for-the-badge&color=blue" alt="License">
</p>

---

## ## ✨ Project Overview

This project is a full-cycle food delivery application inspired by platforms like Swiggy, Zomato, and Uber Eats. It features distinct interfaces and functionalities for three key user roles: customers, restaurant managers, and delivery agents.

The platform is built on the MERN stack and leverages **Socket.IO** for real-time communication, ensuring that order statuses, notifications, and location tracking are updated instantly across all clients. From browsing menus and placing orders to real-time delivery tracking on a map, this application provides a comprehensive and modern food ordering experience.

[Image collage of the food ordering app]

---
## ## ⭐ Core Features

### For Customers 🍕
* **User Authentication**: Secure sign-up and login.
* **Restaurant Discovery**: Search and filter nearby restaurants.
* **Menu Browsing**: View detailed restaurant menus with pricing.
* **Shopping Cart**: Easily add and manage items before checkout.
* **Secure Payments**: Integrated with **Stripe** for safe and easy payments.
* **Real-time Order Tracking**: Track the order status (Placed, Preparing, Out for Delivery) and see the delivery agent's location on a live map.
* **Order History**: View a history of all past orders.

### For Restaurants 🏪
* **Restaurant Dashboard**: A dedicated panel to manage the restaurant's profile and menu.
* **Menu Management**: Full CRUD (Create, Read, Update, Delete) functionality for menu items and categories.
* **Order Management**: Receive new orders in real-time, with options to accept or reject them.
* **Live Status Updates**: Update the order status, which instantly notifies the customer.

### For Delivery Agents 🛵
* **Delivery Dashboard**: View a list of available orders for pickup.
* **Order Acceptance**: Accept delivery tasks.
* **Live Location Sharing**: Share location in real-time with the customer once a delivery is started.
* **Status Updates**: Update delivery status (e.g., "Picked Up," "Delivered").

---
## ## 🛠️ Technology Stack

| Category | Technology |
| :--- | :--- |
| **Frontend** | [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/) |
| **Backend** | [![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/) |
| **Database** | [![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/) |
| **Real-time Engine** | [![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)](https://socket.io/) |
| **Payments** | [![Stripe](https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=stripe&logoColor=white)](https://stripe.com/) |
| **Mapping** | **Leaflet.js** with **OpenStreetMap** or **Google Maps API** |

---
## ## 🚀 Getting Started

To get a local copy up and running, follow these detailed steps.

### ### ✅ Prerequisites

* **Node.js** (v18.x or later)
* **npm** & **Git**
* **MongoDB**: A running instance of MongoDB, either locally or a connection string from MongoDB Atlas.

### ### ⚙️ Installation & Setup

1.  **Clone the repository**:
    ```sh
    git clone [https://github.com/Brajesh31/food-ordering.git](https://github.com/Brajesh31/food-ordering.git)
    ```
2.  **Navigate to the project directory**:
    ```sh
    cd food-ordering
    ```
3.  **Backend Setup**:
    * Navigate to the backend directory: `cd server`
    * Install backend dependencies: `npm install`
    * Create a `.env` file in the `server` directory and add the environment variables listed below.
    * Start the backend server: `npm start`

4.  **Frontend Setup**:
    * Navigate to the frontend directory from the root folder: `cd client`
    * Install frontend dependencies: `npm install`
    * Start the frontend development server: `npm start`

### ### 🔑 Environment Variables

You need to create a `.env` file in the `server` directory and add the following variables:

Last updated: 2026-10-15 23:30 UTC
