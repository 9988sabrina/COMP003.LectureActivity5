# COMP003.LectureActivity5 – ASP.NET Core Web API

This project was created for **COMP003B Module 5 Lecture Activity** at [Your College Name].

## 📚 Overview

This is a simple ASP.NET Core Web API project using .NET 8.0. The API allows for full CRUD operations on an in-memory list of products. It is documented and tested using Swagger UI.

## 🏗️ Technologies

- ASP.NET Core 8.0
- Swagger / Swashbuckle
- Visual Studio 2022+
- C#
- In-memory Data Store

## 📦 Features

- `GET /api/products` – List all products
- `GET /api/products/{id}` – Get a specific product by ID
- `POST /api/products` – Add a new product
- `PUT /api/products/{id}` – Update an existing product
- `DELETE /api/products/{id}` – Delete a product
- `GET /api/products/filter?price=50` – Filter products by price
- `GET /api/products/names` – Return only product names

## 🚀 Getting Started

1. Clone the repository
2. Open in Visual Studio 2022+
3. Build the project
4. Press `Ctrl + F5` to launch Swagger

## 🧪 Swagger Testing

All endpoints were tested using Swagger. Screenshots are included in the `Screenshots` folder.

---

## 📸 Screenshots

| Test | Screenshot |
|------|------------|
| `GET /api/products` | `get-api-products.png` |
| `GET /api/products/1` | `get-api-products-id.png` |
| `GET /api/products/1234` (invalid) | `get-api-products-id-invalid.png` |
| `POST /api/products` | `post-api-products.png` |
| `PUT /api/products/1` | `put-api-products-id.png` |
| `DELETE /api/products/4` | `delete-api-products-id.png` |
| `GET /api/products/filter?price=50` | `get-api-products-filter.png` |
| `GET /api/products/names` | `get-api-products-names.png` |

---

## 🙋 Author

Sumei Zhang  
COMP003B Student  
Spring 2025
