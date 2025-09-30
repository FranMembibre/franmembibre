# API Reference Documentation

This section provides detailed information about the available APIs, including their endpoints, request parameters, and response formats.

## API Endpoints

### Endpoint 1: `GET /api/v1/resource`
- **Description**: Retrieves a list of resources.
- **Parameters**: 
  - `limit` (optional): The number of resources to return.
  - `offset` (optional): The starting point for the returned resources.
- **Response**:
  - **200 OK**: Returns a JSON array of resources.
  
### Endpoint 2: `POST /api/v1/resource`
- **Description**: Creates a new resource.
- **Request Body**: 
  - `name`: The name of the resource.
  - `description`: A brief description of the resource.
- **Response**:
  - **201 Created**: Returns the created resource object.
  - **400 Bad Request**: If the request body is invalid.

### Endpoint 3: `GET /api/v1/resource/{id}`
- **Description**: Retrieves a specific resource by ID.
- **Parameters**: 
  - `id`: The unique identifier of the resource.
- **Response**:
  - **200 OK**: Returns the resource object.
  - **404 Not Found**: If the resource does not exist.

## Usage Examples

### Example 1: Retrieve Resources
```bash
curl -X GET "http://example.com/api/v1/resource?limit=10&offset=0"
```

### Example 2: Create a Resource
```bash
curl -X POST "http://example.com/api/v1/resource" -H "Content-Type: application/json" -d '{"name": "New Resource", "description": "This is a new resource."}'
```

### Example 3: Retrieve a Specific Resource
```bash
curl -X GET "http://example.com/api/v1/resource/1"
```