# Spring-boot-3-customer-api

# Spring-boot-3-customer-api

## Overview
This repository contains a Spring Boot API for managing customer information. The API offers endpoints for adding, deleting, retrieving, and updating customer details.

## 1- Add Customer
**Method:** `POST`  
**Endpoint:** `http://localhost:8080/api/v1/customers/`  
**Request Body (JSON):**
```json
{
  "name": "John",
  "email": "john@gmail.com",
  "age": 32
}
```

## 2- Delete Customer
**Method:** `DELETE`
**Endpoint:** `http://localhost:8080/api/v1/customers/{customerid}`


## 3- Get Customers
**Method:** `GET`
**Endpoint:** `http://localhost:8080/api/v1/customers/`

### Output
```json
[
  {
    "id": 1,
    "name": "Gurkan Yakar",
    "email": "data.yakar@gmail.com",
    "age": 25
  },
  {
    "id": 3,
    "name": "John",
    "email": "john@gmail.com",
    "age": 32
  }
]
```



## 4- Update Customer
**Method:** `PUT`  
http://localhost:8080/api/v1/customers/{customerid}

```json
{
"name": "Gurkan Yakar",
"email": "data.yakar@gmail.com",
"age": 25
}
```