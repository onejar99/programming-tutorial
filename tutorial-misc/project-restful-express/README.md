# RESTful API with Express

## Requriments

Implement following endpoints by Express framework.

### GET /products
Request example:
```
GET /products
```
Response example:
(http code: 200)
```json
[
    {
        "id": 1,
        "name": "MacBook Pro",
        "description": "Apple laptops",
        "price": 1299,
        "isSoldOut": false
    },
    {
        "id": 2,
        "name": "iPhone 12",
        "description": "Apple phones",
        "price": 799,
        "isSoldOut": true
    },
]
```

### GET /products/{id}
Request example:
```
GET /products/1
```
Response example:
(http code: 200)
```json
{
    "id": 1,
    "name": "MacBook Pro",
    "description": "Apple laptops",
    "price": 1299,
    "isSoldOut": false
}
```

### POST /products
Request example:
```json
POST /products

payload:
{
    "name": "iPad 128G",
    "description": "Apple pad",
    "price": 429,
    "isSoldOut": false
}
```
Response example:
(http code: 201)
```json
{
    "id": 3,
    "name": "iPad 128G",
    "description": "Apple pad",
    "price": 429,
    "isSoldOut": false
}
```

### PATCH /products/{id}
Request example:
```json
PUT /products/3

payload:
{
    "isSoldOut": true
}
```
Response example:
(http code: 200)
```json
{
    "id": 3,
    "name": "iPad 128G",
    "description": "Apple pad",
    "price": 429,
    "isSoldOut": true
}
```

### PATCH /products/{id}
Request example:
```json
PUT /products/3

payload:
{
    "isSoldOut": true
}
```
Response example:
(http code: 204)
(no content)
