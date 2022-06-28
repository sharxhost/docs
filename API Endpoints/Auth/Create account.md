# `POST /api/v1/auth/create`

Creates a new user account

## URL parameters
None

## Request body (JSON)
- `username` - a string; maximum length: 16; usable characters: `a`-`z`, `A`-`Z`, `0`-`9`, `_`, `-`
- `password` - the cleartext password (will be encrypted on the server)
- `email` - the user's email

## Returns (JSON)
```json
{
	"success": true,
	"uuid": "aaaa...",  // the created user's uuid
	"token": "aaaa..."  // the auth token (JWT)
}
```
