# Image
Stores an uploaded image's metadata

## Columns
- ID - Unique image ID (8 characters)
- Name - The image's filename
- Upload time - The timestamp of when the image was uploaded
- Size - The image's size in B (bytes)
- Hash - An [image-hash](https://github.com/danm/image-hash) hash (16-bit, precise) of the image