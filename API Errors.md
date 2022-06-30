# Errors

As mentioned in [[API Docs]], every JSON endpoint must have a `success` key in it and return status code `200`. If there is no error, it will have a value of `true` and the rest will be the normal API response.
On the other hand, if the request fails, `success` will have a value of `false`. Then, the response will look like this:
```json
{
	"success": "false",
	"error": {
		"code": "unknown_error",  // the error code
		"data": {}                // error-specific data
	}
}
```
Some errors will also have a `details` key.