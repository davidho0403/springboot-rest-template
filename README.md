# Spring Boot Rest API Template
Rest API template for Spring Boot

## API Document

### `GET` Get all users
```
api/users/
```

### `GET` Get user info by user ID
```
api/users/{userID}
```

### `POST` Add user
```
api/users/
```
- Request Headers
```
Content-Type application/json
```
- Request Body
```json
{
  "name": "User",
  "email": "user@mail.com"
}
```

### `DELETE` Delete user by user ID
```
api/users/{userID}
```