# FreeCodeCamp API: File Metadata Microservice
## User stories:
- I can submit a FormData object that includes a file upload.
- When I submit something, I will receive the file size in bytes within the JSON response

Hint: You may want to use this package: https://www.npmjs.com/package/multer

### Example query usage:
Upload file from the UI at the root.

`https://effy-file-metadata-microservice.glitch.me`

### Example query output:
`https://effy-file-metadata-microservice.glitch.me/upload`

```
{
"name": "2016-01-26.png",
"size": 258957,
} 
```

