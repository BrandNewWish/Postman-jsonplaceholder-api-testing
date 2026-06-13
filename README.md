# JSONPlaceholder API Testing Project

## Project Overview

This project demonstrates manual API testing using Postman against the JSONPlaceholder REST API.

The goal was to practice testing REST API endpoints by executing CRUD operations, validating HTTP responses, and verifying API behavior through automated Postman test scripts.

The project includes testing of Users and Posts endpoints, covering positive and negative scenarios, status code verification, response structure validation, data integrity checks, and response time validation.

---

## Tested Operations

### Create

`POST /users`

Verified:
- Successful creation of a new resource
- Correct response status codes (201 Created)
- Response body structure validation

---

### Read

`GET /users`  
`GET /users/{id}`

Verified:
- Retrieval of existing records
- Handling of non-existing records
- Response data correctness

---

### Update

`PUT /users/{id}`

Verified:
- Successful update of existing resource
- Response payload validation
- Status code verification

---

#### Partial Update

`PATCH /users/{id}`

Verified:
- Successful partial update of a resource
- Modification of selected fields only
- Response payload validation
- Status code verification

---

### Delete

`DELETE /users/{id}`

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
- JSONPplaceholder REST API
- REST API concepts (HTTP methods, JSON responses)

## Key Learning Outcomes

- Understanding REST API structure and HTTP methods
- Validating API responses using Postman
- Designing basic CRUD test scenarios
- Differentiating positive and negative test cases
