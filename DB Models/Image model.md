# Image
Stores an uploaded image's metadata

## Columns
- ShortID - Short image ID (8 characters)
- UUID - The image UUID (v4)
- Name - The image's filename
- Uploaded - The timestamp of when the image was uploaded
- Size - The image's size in B (bytes)
- Hash - An [image-hash](https://github.com/danm/image-hash) hash (16-bit, precise) of the image
- User - A relation to the owner ([[User model]])
- UserID - The owner's UUID