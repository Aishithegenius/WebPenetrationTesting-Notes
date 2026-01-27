HTTP REQUESTS

Sent from client to server.

Contains:
- Method
- URL
- Headers
- Optional body

Example:
GET /index.php HTTP/1.1
Host: example.com

HTTP RESPONSES

Sent from server to client.

Contains:
- Status code
- Headers
- Response body

Example:
HTTP/1.1 200 OK
Content-Type: application/json

HTTP HEADERS

Headers provide extra information.

Common request headers:
- Host
- User-Agent
- Cookie
- Authorization
- Content-Type

Common response headers:
- Set-Cookie
- Content-Type
- Server
- Cache-Control
