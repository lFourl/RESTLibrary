# RESTLibrary

This repository is a Dockerized RESTful API application in Go for a simple book library.

## Includes

- The idiomatic structure based on the resource-oriented design.
- The usage of Docker, Docker compose, Alpine images, and linters on development.
- Healthcheck and CRUD API implementations with OpenAPI specifications.
- The usage of Goose for the database migrations and GORM as the database ORM.
- The usage of Validator.v10 as the form validator.

## Endpoints

| Name        | HTTP Method | Route          |
|-------------|-------------|----------------|
| Health      | GET         | /livez         |
|             |             |                |
| List Books  | GET         | /v1/books      |
| Create Book | POST        | /v1/books      |
| Read Book   | GET         | /v1/books/{id} |
| Update Book | PUT         | /v1/books/{id} |
| Delete Book | DELETE      | /v1/books/{id} |