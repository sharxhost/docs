# `GET /user/info`

Returns info about the user

## Headers
- `Authorization: Bearer aaaa...` - the user's jwt token

## Returns (JSON)
```json
{
	"success": true,
	"uuid": "aaaa...",            // the user's uuid
	"username": "GGORG",          // the user's username
	"email": "GGORG@email.tld",   // the user's email
	"createdAt": 1656496146233    // the timestamp of user creation
}
```
