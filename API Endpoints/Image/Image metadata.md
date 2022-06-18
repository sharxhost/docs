# `GET /image/:id/metadata`

Returns all the metadata of the image

## URL parameters
- id - The 8-character ID of the image

## Returns (JSON)
```json
{
	"success": true,
	"longid": "aaaaaaaa",      // the image's 8-char short id
	"uuid": "aaaaaaaa",        // the image's uuid
	"name": "image.png",       // the image's filename
	"uploaded": 1655323171,    // the image's upload timestamp
	"size": 1048576,           // the image's file size in bytes
	"hash": "077306..."        // a 64-character hash of the image (more info in the image db model)
}
```
