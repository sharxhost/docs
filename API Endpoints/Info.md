# `GET /api/v1/service/info`

Returns the system and backend info

## URL parameters
None

## Returns (JSON)
```json
{
	"success": true,
	"version": "1.0.0",   // backend version
	"gitver": "aaaaaaa",  // backend git commit hash
	"name": "SharX"       // custom service name
}
```
