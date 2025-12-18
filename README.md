# 📦The General Goods Depot (E-Commerce API - Capstone Project)
A full-stack e-commerce application built with Java Spring Boot and MySQL. This API handles the complete online shopping experience, from browsing products and categories to managing user carts and processing secure checkouts.
# 📁 Project Structure
<img width="348" height="1072" alt="image" src="https://github.com/user-attachments/assets/1a851de6-88f3-47c4-a2b1-58aac5366d72" />


# 🚀 Features
## ✅ Core Features
* User Authentication (JWT-based)
* Product Management (CRUD operations)
* Category Management
* Shopping Cart with persistence
* Checkout & Order Processing
* User Profiles

# 🐛 Bugs Fixed
* Product Search Bug: Fixed incorrect price filtering logic
* Product Update Bug: Fixed issue where updates created duplicate products instead of updating existing ones

# 🛠️ New Features Implemented
* Complete CategoriesController with admin-only CRUD operations
* Shopping cart with add, update, and clear functionality
* User profile management
* Order processing and checkout system

# 🏗️ Architecture
## Tech Stack
* Java 17
* Spring Boot (Web, Security)
* MySQL (Database)
* JDBC (Data Access)
* Spring Security & JWT (Authentication & Authorization)
* Maven (Dependency Management)
* Insomnia (API Testing)

# 📚 API Documentation
## Authentication Endpoints
<img width="618" height="847" alt="image" src="https://github.com/user-attachments/assets/729d353a-0633-4b93-bb1b-094de8fc2640" />
<img width="605" height="539" alt="image" src="https://github.com/user-attachments/assets/8419ef01-24d1-42fb-af8a-837900376291" />


# 🐛 Bug Fixes Highlight
Bug 1: Product Search
Problem: Search was ignoring max price and had incorrect comparison logic.
Solution: Fixed SQL query to properly handle both min and max price ranges.

<img width="715" height="135" alt="image" src="https://github.com/user-attachments/assets/f2435c0d-1326-46f1-beda-520521e99614" />

Bug 2: Product Updates
Problem: PUT request to update products was calling create() instead of update().
Solution: Fixed controller to call correct DAO method.
<img width="1141" height="195" alt="image" src="https://github.com/user-attachments/assets/7238e8da-1c8c-4335-913f-9613d853861c" />



