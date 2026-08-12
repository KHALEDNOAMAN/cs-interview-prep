# API Design Best Practices

## REST Principles
- Use nouns, not verbs: GET /users not GET /getUsers
- HTTP status codes: 200, 201, 400, 401, 404, 500
- Pagination: ?page=1&limit=20
- Versioning: /api/v1/

## Rate Limiting
- Token bucket algorithm
- Sliding window counter
- Headers: X-RateLimit-Remaining