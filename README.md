# JSONPlaceholder API Testing Project

## Project Overview

This project demonstrates manual API testing using Postman against the JSONPlaceholder REST API.

The goal was to practice testing CRUD operations, HTTP methods, response validation, and API behavior.

---

## Tested Operations

### Create

`POST /posts`

Verified:
- Successful creation of a new resource
- Correct response status codes (201 Created)
- Response body structure validation

---

### Read

`GET /posts`  
`GET /posts/{id}`

Verified:
- Retrieval of existing records
- Handling of non-existing records
- Response data correctness

---

### Update

`PUT /posts/{id}`

Verified:
- Successful update of existing resource
- Response payload validation
- Status code verification

---

### Delete

`DELETE /posts/{id}`

Verified:
- Successful deletion of resource
- Correct status code responses

---

## Test Types Performed

- Positive testing
- Negative testing
- CRUD operations validation
- HTTP status code verification
- Response body validation

---

## Tools Used

- Postman
- JSONPlaceholder REST API
- REST API concepts (HTTP methods, JSON responses)
