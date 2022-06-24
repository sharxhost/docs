# `GET /service/info`

Returns the system and backend info

## URL parameters
None

## Returns (JSON)
```json
{
	"success": true,
	"git": {                 // backend git info
		"commit": "aaaaa...",
		"tag": "vxx",
		"branch": "master"
	},
	"name": "SharX"          // custom service name
}
```
