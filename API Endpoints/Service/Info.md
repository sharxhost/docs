# `GET /service/info`

Returns the system and backend info

## Returns (JSON)
```json
{
	"success": true,
	"git": {                 // backend git info
		"commit": "aaaaa...",
		"tag": "v1.0.0",
		"branch": "master",
		"semver": [1, 0, 0]
	},
	"name": "SharX"          // custom service name
}
```
