REAL-WORLD VULNERABILITIES

1. Broken Access Control
APIs allow PUT or DELETE without authentication.

2. IDOR
Changing IDs in URL exposes other users' data.

3. Unprotected CRUD APIs
Anyone can create, update, or delete records.

4. Missing Authorization
Authenticated but unauthorized users can perform admin actions.

Example:
PUT /api/user/1 without permission
