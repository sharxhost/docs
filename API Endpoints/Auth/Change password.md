# `POST /auth/changePassword`

Changes the current user's password

## Request body (JSON)
- `password` - the new password (will be encrypted on the server)
- `oldPassword` - the old password

## Headers
- `Content-Type: application/json`
- `Authorization: Bearer aaaa...` - the user's jwt token

## Returns (JSON)
```json
{
	"success": true,
}
```
