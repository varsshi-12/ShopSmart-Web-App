# 🛒 ShopSmart: Your Digital Grocery Store Experience

## 📂 Category
**Full Stack Development**

## 🛠️ Skills Required
- Web Application Development  
- HTML  
- CSS  
- JavaScript  
- Bootstrap  
- Node.js  
- MongoDB  
- Database Design  
- React  

## 🌐 Project Overview
**ShopSmart** is a modern, responsive digital grocery store web application that offers users a seamless shopping experience from browsing to checkout. Designed with a user-friendly interface and robust backend integration, ShopSmart brings grocery shopping into the digital age.

## 🚀 Features
- Intuitive and responsive UI using **Bootstrap** and **React**
- Dynamic product listing with real-time filtering
- Secure user authentication and session management
- Cart management and order tracking
- RESTful APIs using **Node.js**
- Data persistence with **MongoDB**
- Admin dashboard for product & inventory management

## 🎯 Objectives
- Deliver a smooth and fast online grocery shopping experience
- Enable users to browse, search, and purchase products with ease
- Provide administrators with tools to manage product data effectively

## 🧩 Tech Stack
**Frontend:** HTML, CSS, JavaScript, Bootstrap, React  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  

## 🧱 Technical Architecture

Below is the high-level technical architecture of the **ShopSmart** web application, showcasing the interaction between the frontend, backend, and database layers.

![Technical Architecture](![image](https://github.com/user-attachments/assets/f0cb2edd-a3ea-4ed7-92d4-6ac2a14c6308)
The technical architecture illustrates the interaction between the frontend (React), backend (Node.js/Express), and the MongoDB database using RESTful APIs. It ensures smooth data flow and system scalability across the application layers.

## 🗂️ ER Diagram (Entity-Relationship Diagram)

The ER Diagram represents the database schema used in **ShopSmart**, including entities like Users, Products, Orders, and Cart with their relationships.

![ER Diagram](![image](https://github.com/user-attachments/assets/9b6c4f47-946e-47f0-987e-f7a9933cb6a3)
The ER diagram outlines the structure of the database, depicting entities such as Users, Products, Orders, and their relationships. It helps visualize how data is organized and connected within ShopSmart.

## 👑 Admin Role

### 🧾 Description:
The **Admin** role has full control and administrative privileges across the entire ShopSmart system.

### 🔐 Permissions & Responsibilities:

- **🛠️ Manage Shop & Products**  
  Admins can add, edit, and delete shop information and product listings.

- **📦 Manage Product Bookings**  
  Admins can view, modify, or cancel all product bookings made by users and agents.

- **👥 Manage Users**  
  Admins can create, update, and delete user accounts, and assign or modify user roles and permissions.

- **📊 Generate Reports**  
  Admins have access to analytics and reports, including booking details, booking counts, and sales performance.

## 🙋‍♂️ User Role

### 🧾 Description:
**Users** are the customers of the ShopSmart platform who can browse, book, and manage grocery products through the online shopping interface.

### 🔐 Permissions & Responsibilities:

- **🔍 View Products**  
  Users can search and browse grocery items based on their preferences and categories.

- **🛒 Product Bookings**  
  Users can select available products and complete the order/booking process.

- **📦 Manage Product Bookings**  
  Users can view, modify, track, or cancel their own product bookings through their account dashboard.

- **🧺 Manage Cart**  
  Users can add items to their cart, review cart contents, and update or remove items as needed.

## 🗃️ Project Structure

The ShopSmart project follows a modular structure for better scalability and maintainability:

ShopSmart ├── Backend/ │ ├── db/ │ │ ├── connect.js │ │ ├── products.js │ │ └── schema.js │ ├── index.js │ ├── package.json │ └── package-lock.json │ ├── Frontend/ │ ├── public/ │ ├── src/ │ │ ├── admin_components/ │ │ ├── components/ │ │ ├── context/ │ │ ├── App.js │ │ └── ... │ ├── package.json │ └── package-lock.json

## ✨ Features

- 🛍️ **Browse Grocery Items**  
  Users can explore a wide range of grocery products with detailed descriptions and prices.

- 🧑‍💼 **Admin Panel for Product Management**  
  Admins can add, update, and delete products through a secure dashboard.

- 🔎 **Search and Filter Functionality**  
  Quickly find products using real-time search and category-based filters.

- ⚡ **Responsive UI**  
  Seamless experience across desktops, tablets, and mobile devices using Bootstrap and React.

- 💾 **MongoDB Database Integration**  
  Robust data storage and retrieval using MongoDB with Mongoose for schema modeling.

## 📦 Installation

Follow the steps below to set up and run the **ShopSmart** application locally.

### 🔧 Backend Setup

```bash
cd Backend
npm install
node index.js
### 💻 Frontend Setup

```bash
cd Frontend
npm install
npm start

## 📌 Conclusion
ShopSmart demonstrates a complete full-stack application workflow—from designing the frontend to connecting and managing a backend with database support. It exemplifies best practices in responsive design, API integration, and scalable web development.

---

⭐ If you found this project useful, feel free to star the repository.
