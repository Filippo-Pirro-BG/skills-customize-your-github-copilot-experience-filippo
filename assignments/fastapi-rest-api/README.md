# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build and test RESTful APIs using the FastAPI framework in Python. By the end of this assignment, you will have created a simple API with endpoints for basic CRUD operations.

## 📝 Tasks

### 🛠️	Set Up FastAPI Project

#### Description
Initialize a new FastAPI project and set up the required environment.

#### Requirements
Completed setup should:

- Install FastAPI and Uvicorn
- Create a main application file (e.g., `main.py`)
- Run the server locally and access the default docs at `/docs`

### 🛠️	Create a Simple Item API

#### Description
Build an API to manage a collection of items (e.g., books, products, or tasks).

#### Requirements
Completed API should:

- Define an `Item` model with at least `id`, `name`, and `description` fields
- Implement endpoints to:
  - List all items (`GET /items`)
  - Retrieve a single item by ID (`GET /items/{id}`)
  - Add a new item (`POST /items`)
  - Update an item (`PUT /items/{id}`)
  - Delete an item (`DELETE /items/{id}`)
- Return appropriate status codes and error messages

### 🛠️	Test Your API

#### Description
Test your API using the interactive docs or a tool like Postman/curl.

#### Requirements
Completed testing should:

- Demonstrate successful requests for each endpoint
- Show error handling for invalid requests (e.g., item not found)
- (Optional) Add example requests/responses in your README
