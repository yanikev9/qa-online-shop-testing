# API Testing

API testing was performed using Postman.

## Tested Endpoint

POST /register

## Test Cases

### 1. Successful registration
Request:
POST /register

Body:
{
"email": "test@test.com",
"password": "Test12345"
}

Expected result:
Status code 201  
User successfully created

---

### 2. Registration with existing email

Body:
{
"email": "existing@test.com",
"password": "Test12345"
}

Expected result:
Status code 400  
Error message: "User already exists"

---

### 3. Registration with empty fields

Body:
{
"email": "",
"password": ""
}

Expected result:
Status code 400  
Validation error
