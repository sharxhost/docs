# `POST /image/upload`

Upload a new image to the service

## URL parameters
None

## Request body
The raw image data

## Returns (JSON)
```json
{
	"success": true,
	"id": "aaaaaaaa"  // the 8-character image id
}
```

## Note
The image must be smaller than 5 MB
