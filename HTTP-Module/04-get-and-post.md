GET METHOD

Used to retrieve data.
Data is sent in URL.
No request body.

Example:
curl http://example.com/search.php?q=test

POST METHOD

Used to send data.
Data is sent in request body.
Not visible in URL.

Used for:
- Login
- Forms
- Creating records

Example:
curl -X POST http://example.com/login -d "user=admin&pass=admin"
