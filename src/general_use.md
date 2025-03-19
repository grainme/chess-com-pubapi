# General Use and Features

## How to Use the API
1. **Construct the URL**: Use the endpoint patterns provided in the documentation.
2. **Make the Request**: Use a browser, `cURL`, Postman, or any HTTP client.
3. **Parse the Response**: Responses are in JSON format.

---

## Rate Limiting
- Avoid making parallel requests to prevent being blocked.
- If you receive a `429 Too Many Requests` response, slow down your requests.

---

## Caching
- Data is cached and refreshed every 12-24 hours.
- Use `ETag` and `Last-Modified` headers to check for updates.

---

## JSON-LD
The API uses JSON-LD (JSON for Linked Data) to provide context for the data. Each response includes a `Link` header pointing to the JSON-LD context.

---

## JSONP
You can use JSONP by adding a `callback` parameter to the URL. For example:
```bash
https://api.chess.com/pub/player/erik?callback=myFunction
```

---

## HTTP Compression
Responses are gzip-compressed if the `Accept-Encoding: gzip` header is included in the request.

---

## HTTP/2 Support
The API supports HTTP/2 for faster and more efficient communication.
