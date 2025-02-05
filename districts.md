### Retrieve Marketing Districts

**Description**: This endpoint allows you to retrieve a list of marketing districts.

**Endpoint**: `GET /marketing/get-districts`

**Authentication**: This route is accessed with a token.

#### Request

- **Request Body**: This endpoint does not require a request body.

#### Response

- **200 OK**: A successful response will include a list of marketing districts, each containing the following information:

  - **districtId**: The unique identifier for the district.
  - **districtName**: The name of the district.
  - **region**: The region to which the district belongs.

  **Example Response**:

  ```json
  [
    {
        "id": 1,
        "region": null,
        "name": "Berea",
        "date": "2020-07-03 00:00:00",
        "pub": 1,
        "del": 1,
        "agent_count": 97,
        "personal_user_count": 50
    },
    {
        "id": 10,
        "region": null,
        "name": "Thaba Tseka",
        "date": null,
        "pub": 1,
        "del": 1,
        "agent_count": 0,
        "personal_user_count": 0
    }
  ]
