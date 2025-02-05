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
  {
      "districts": [
          {
              "districtId": "123",
              "districtName": "District A",
              "region": "Region 1"
          },
          {
              "districtId": "456",
              "districtName": "District B",
              "region": "Region 2"
          }
      ]
  }
