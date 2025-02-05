### Retrieve Marketing Agents' Accounts

**Endpoint**: `{{baseURL}}/marketing/agents-accounts`

**Description**: This endpoint makes an HTTP GET request to retrieve the marketing agents' accounts.

#### Request

- **Method**: `GET`
- **Request Body**: This endpoint does not require a request body.

#### Response

The response of this request is documented as a JSON schema:

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
  },
  {
      "name": "larry",
      "surname": "simetsi",
      "id_number": "654852144545",
      "gender": "Male",
      "cell": "45452147",
      "district": "N\/A",
      "physical_address": "kk",
      "date": "2023-07-28 08:50:54",
      "limit": "1500"
  }
]
