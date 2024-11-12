# Product Cluster Test Project

This project demonstrates a simple Product Cluster using MongoDB for database management, with REST API routes for adding and retrieving products by exact price. The project is developed using either .NET Core or Node.js (Express) for backend services and a minimal frontend using either HTML or React.

## Prerequisites

- MongoDB (with a product cluster created)
- URL connection string to the MongoDB Database
- Either .NET Core SDK or Node.js installed

## Project Setup

1. **Create a MongoDB Product Cluster**: 
   - Set up a MongoDB cluster and obtain the connection URL.

2. **Connect to Database**:
   - Use the MongoDB connection URL string in your project to link the database.

3. **Product Structure**:
   - Each product document in MongoDB will have the following fields:
     - `name`: `String`
     - `price`: `Number`
     - `added_at`: `Date`

4. **API Routes**:
   - **GET /product/:price**: Retrieve all products with an exact price.
   - **POST /product**: Add a new product to the cluster.

5. **Frontend**:
   - A simple form to add new products with fields:
     - **Product Name**
     - **Product Price**
   - A **Submit** button to add the product.
   - A table view displaying:
     - **Product Name**
     - **Product Price**
     - **Product Created Date**
   - A search input field above the table to filter products by exact price.

## Instructions

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>
