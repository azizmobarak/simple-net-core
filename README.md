# Product Cluster Test Project

This project demonstrates a simple product management system using MongoDB for database storage and REST API routes to add and retrieve products by exact price. The backend is built with either .NET Core or Node.js (Express), while the frontend can be a basic HTML template or a React app.

## Prerequisites

- MongoDB with a created cluster for products
- Database connection URL string for MongoDB
- Either .NET Core SDK or Node.js installed

## Project Setup

### Step 1: MongoDB Product Cluster
- Set up a MongoDB cluster and obtain the connection URL.

### Step 2: Connect to the Database
- Use the MongoDB connection URL string in the project's configuration file to link the database.

### Step 3: Product Structure
Each product document in MongoDB should include:
  - `name`: `String`
  - `price`: `Number`
  - `added_at`: `Date`

### Step 4: API Routes
- **GET /product/:price**: Retrieve all products with an exact price.
- **POST /product**: Add a new product to the cluster.

### Step 5: Frontend UI
Create a form and a table display for products:
- Form with:
  - **Product Name** input
  - **Product Price** input
  - **Submit** button
- Table display with:
  - **Product Name**
  - **Product Price**
  - **Created Date**
- Include a search field above the table to filter products by exact price.

---

## Instructions

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>
