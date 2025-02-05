### Retrieve Marketing Agents' Accounts

**Endpoint**: `{{baseURL}}/marketing/agents-accounts`

**Description**: This endpoint makes an HTTP GET request to retrieve the marketing agents' accounts.

#### Request

- **Method**: `GET`
- **Request Body**: This endpoint does not require a request body.

#### Response

The response of this request is documented as a JSON schema:

```json
{
  "type": "object",
  "properties": {
    "agents": {
      "type": "array",
      "items": {
        "type": "object",
        "properties": {
          "[agentId](https://x.com/i/grok?text=agentId)": {
            "type": "string",
            "description": "The unique identifier for the agent."
          },
          "[name](https://x.com/i/grok?text=name)": {
            "type": "string",
            "description": "The name of the agent."
          },
          "[surname](https://x.com/i/grok?text=surname)": {
            "type": "string",
            "description": "The surname of the agent."
          },
          "[phoneNumber](https://x.com/i/grok?text=phoneNumber)": {
            "type": "string",
            "description": "The phone number of the agent."
          },
          "[district](https://x.com/i/grok?text=district)": {
            "type": "string",
            "description": "The district where the agent operates."
          },
          "[status](https://x.com/i/grok?text=status)": {
            "type": "string",
            "description": "The status of the agent (e.g., 'active', 'not active')."
          },
          "[lastActiveDate](https://x.com/i/grok?text=lastActiveDate)": {
            "type": "string",
            "format": "date-time",
            "description": "The last date when the agent was active."
          }
        },
        "required": ["agentId", "name", "surname", "phoneNumber", "district", "status", "lastActiveDate"]
      }
    }
  }
}
