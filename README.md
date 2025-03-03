# 🚀 API Documentation

## 📌 Overview
This repository contains two Postman collections for working with mock APIs:

1. **Jsonplaceholder API** - A fake online REST API for testing and prototyping.
2. **DummyJson API** - A dummy API with various endpoints for testing JSON-based interactions.

## 🛠 Installation
To use these collections, import them into Postman:

1. Open Postman.
2. Go to **File** > **Import**.
3. Select and upload the `.postman_collection.json` files from this repository.

## 📡 API Endpoints

### 🌐 Jsonplaceholder API
A collection of RESTful API endpoints that allow users to interact with mock data.

#### 📌 Endpoints:
- `GET /posts` - Retrieve all posts 📰
- `GET /posts/{id}` - Retrieve a specific post 🔍
- `POST /posts` - Create a new post ✍️
- `PUT /posts/{id}` - Update a post 🛠
- `PATCH /posts/{id}` - Partially update a post 🩹
- `DELETE /posts/{id}` - Delete a post ❌
- Similar endpoints exist for comments, albums, photos, and users.

### 🏗 DummyJson API
A fake API providing dynamic data for testing and prototyping applications.

#### 📌 Endpoints:
- **🖼 Dynamic Images**:
  - `GET /image/{size}` - Generates an image with a specified size 📏
  - `GET /image/{width}x{height}` - Generates a custom-sized image 🎨
  - `GET /image/{width}x{height}/{bgColor}/{textColor}?text=Hello` - Custom images with text 🖋
- **🔐 Authentication**:
  - `POST /auth/login` - User login and token retrieval 🔑
  - `GET /auth/me` - Get current authenticated user 🧑‍💻
  - `POST /auth/refresh` - Refresh authentication token 🔄
- **🛒 Products**:
  - `GET /products` - Get all products 🛍
  - `GET /products/{id}` - Retrieve a single product 📦
  - `POST /products/add` - Add a new product ➕
  - `PUT /products/{id}` - Update a product 🔄
  - `DELETE /products/{id}` - Delete a product 🗑
- **👥 Users**:
  - `GET /users` - Retrieve all users 👨‍👩‍👧‍👦
  - `GET /users/{id}` - Get a specific user 🆔
  - `POST /users/add` - Add a new user ➕
  - `PUT /users/{id}` - Update user details ✏️
  - `DELETE /users/{id}` - Remove a user ❌

## 🧪 Tests Performed
The following tests were executed in Postman to ensure API reliability:

✅ **Response Time Tests** - Verified that responses were received within 300ms.
✅ **Status Code Validation** - Ensured responses return correct HTTP status codes (200, 201, 400, etc.).
✅ **Content-Type Checks** - Confirmed that JSON responses had the correct `Content-Type` headers.
✅ **Authentication Tests** - Tested login, token retrieval, and authentication-protected endpoints.
✅ **CRUD Operations** - Verified create, read, update, and delete functionality for various endpoints.
✅ **Data Consistency Tests** - Ensured data integrity across endpoints and user actions.

## 📌 Usage
These APIs can be tested using Postman or any API client by sending requests to the specified endpoints. For authentication-related requests, replace placeholders with actual values before sending requests.

## 📜 License
This repository is open for testing purposes only. Use it freely for development and learning. 🚀

