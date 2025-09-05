# API Contract for Contract Review System

## Base URL
`/api/v1`

## Endpoints

### Contracts

#### GET /contracts
Retrieve all contracts

**Response:**
```json
{
  "success": true,
  "data": [
    {
      "id": "string",
      "title": "string",
      "content": "string",
      "contractType": "string",
      "status": "string",
      "riskLevel": "string",
      "complianceScore": "number",
      "createdAt": "string",
      "updatedAt": "string"
    }
  ]
}
