# `POST /api/v1/auth/login`

Logs in with the provided credentials

## URL parameters
None

## Request body (JSON)
- `email` - the user's email
- `password` - the cleartext password (will be encrypted on the server)

## Headers
- `Content-Type: application/json`

## Returns (JSON)
```json
{
	"success": true,
	"uuid": "aaaa...",  // the created user's uuid
	"token": "aaaa..."  // the auth token (JWT)
}
```
