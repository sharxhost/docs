# `GET /user/uploadKey`

Gets the user's upload keys

## Headers
- `Authorization: Bearer aaaa...` - the user's jwt token

## Returns (JSON)
```json
{
	"success": true,
	"keys": {
		"aaaa...",
		"aaaa..."
	}
}
```
