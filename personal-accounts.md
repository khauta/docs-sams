### Retrieve Personal Accounts Related to Marketing

**Endpoint**: `{{baseURL}}/marketing/personal-accounts`

**Description**: This endpoint makes an HTTP GET request to retrieve personal accounts related to marketing from the server.

#### Request

- **Method**: `GET`
- **Request Body**: This endpoint does not require a request body.

#### Response

The response of this request can be documented as a JSON schema to provide a structured description of the data format:

```json
[
    {
        "name": "Seth",
        "surname": "Matete",
        "id_number": "071255556665",
        "gender": "Male",
        "cell": "58445333",
        "district": "N\/A",
        "physical_address": "Ha foso",
        "date": "2023-07-22 20:55:37",
        "limit": "1500"
    },
    {
        "name": "Seth",
        "surname": "Matete",
        "id_number": "041255556665",
        "gender": "Male",
        "cell": "58454578",
        "district": "N\/A",
        "physical_address": "Ha foso",
        "date": "2023-07-24 12:12:37",
        "limit": "100"
    }
]
