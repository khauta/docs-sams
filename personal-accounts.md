### Retrieve Personal Accounts Related to Marketing

**Endpoint**: `{{baseURL}}/marketing/personal-accounts`

**Description**: This endpoint makes an HTTP GET request to retrieve personal accounts related to marketing from the server.

#### Request

- **Method**: `GET`
- **Request Body**: This endpoint does not require a request body.

#### Response

The response of this request can be documented as a JSON schema to provide a structured description of the data format:

```json
{
  "type": "object",
  "properties": {
    "personalAccounts": {
      "type": "array",
      "items": {
        "type": "object",
        "properties": {
          "[accountId](https://x.com/i/grok?text=accountId)": {
            "type": "string",
            "description": "The unique identifier for the personal account."
          },
          "[name](https://x.com/i/grok?text=name)": {
            "type": "string",
            "description": "The name of the account holder."
          },
          "[surname](https://x.com/i/grok?text=surname)": {
            "type": "string",
            "description": "The surname of the account holder."
          },
          "[phoneNumber](https://x.com/i/grok?text=phoneNumber)": {
            "type": "string",
            "description": "The phone number of the account holder."
          },
          "[district](https://x.com/i/grok?text=district)": {
            "type": "string",
            "description": "The district associated with the account."
          },
          "[status](https://x.com/i/grok?text=status)": {
            "type": "string",
            "description": "The current status of the account (e.g., 'Active', 'Blocked')."
          },
          "[registrationDate](https://x.com/i/grok?text=registrationDate)": {
            "type": "string",
            "format": "date-time",
            "description": "The date when the account was registered."
          }
        },
        "required": ["accountId", "name", "surname", "phoneNumber", "district", "status", "registrationDate"]
      }
    }
  }
}
