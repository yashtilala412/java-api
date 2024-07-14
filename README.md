# Login Data Management API

This project provides a RESTful API for managing login data using Spring Boot and MongoDB.

## Project Structure

- `LoginDataController`: Handles HTTP requests and routes them to the service layer.
- `LoginDataDocument`: Represents the login data model.
- `LoginDataRepository`: Interface for MongoDB operations.
- `LoginDataService`: Service layer for business logic and interaction with the repository.

## Endpoints

### Create Login Data

**Endpoint:** `POST /api/login`

**Description:** Creates a new login data entry. If an email already exists, it returns a message indicating so.
