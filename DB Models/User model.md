# User

## Columns
- UUID - The user's UUID (v4)
- Username - The user's username (maximum length: 16; minimum length: 3; usable characters: `a`-`z`, `A`-`Z`, `0`-`9`, `_`, `-`)
- Created - The timestamp of when the user was created
- PasswordHash - The hash digest (HMAC SHA512) of the user's password
- PasswordSalt - The salt of the user's password
- Email - The user's email
- UploadKeys - A relation to the user's upload keys ([[UploadKey model]])
- Images - A relation to the user's images ([[Image model]])
- JWTs - A relation to the user's auth tokens ([[AuthJWT model]])