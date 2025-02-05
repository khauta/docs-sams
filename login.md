### Login

**Endpoint**: `{{baseURL}}/login`

**Description**: This endpoint is used to authenticate a user.

#### Request

- **Method**: `POST`
- **Request Body**:

  ```json
  {
    "email": "string (required)",
    "password": "string (required)"
  }
