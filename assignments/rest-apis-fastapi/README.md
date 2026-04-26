# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn to build REST APIs using the FastAPI framework in Python. This assignment covers creating endpoints, handling HTTP requests and responses, and basic API structure.

## 📝 Tasks

### 🛠️ Set Up FastAPI and Basic Endpoint

#### Description
Install FastAPI and create a basic API with a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a FastAPI app instance
- Define a GET endpoint at "/" that returns a JSON response with a welcome message
- Run the server and verify the endpoint works

### 🛠️ Create CRUD Endpoints

#### Description
Expand the API to include endpoints for creating, reading, updating, and deleting items in a simple in-memory list.

#### Requirements
Completed program should:

- Define a data model for items (e.g., using Pydantic)
- Create POST endpoint to add new items
- Create GET endpoint to retrieve all items or a specific item by ID
- Create PUT endpoint to update an item by ID
- Create DELETE endpoint to remove an item by ID
- Handle cases where items don't exist