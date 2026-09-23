# My Learning Notes

## Day 1
- Learned about frontend, backend, and servers.
- Created my GitHub, LinkedIn, and Twitter accounts.
- Made my first repository and first commit.

## Day 2 — HTTP Requests, Status Codes & Idempotency

### HTTP Requests (Methods)

| Method | Purpose | Changes server? |
|---|---|---|
| GET | Read data | No |
| POST | Create new data | Yes |
| PUT | Replace entire thing | Yes |
| PATCH | Update part of thing | Yes |
| DELETE | Remove thing | Yes |

CRUD → HTTP:
- Create = POST
- Read = GET
- Update = PUT / PATCH
- Delete = DELETE

PUT vs PATCH:
- PUT = send the whole thing, old version fully replaced
- PATCH = send only what changed, rest stays

### HTTP Status Codes

Categories:
- 1xx = Information
- 2xx = OK / Success
- 3xx = Redirect
- 4xx = User (client) error
- 5xx = Server error

Codes covered in class:
- 200 = OK
- 201 = Created
- 204 = No Content
- 301 = Moved Permanently
- 302 = Temporary Redirect
- 400 = Bad Request
- 401 = Unauthorized
- 403 = Forbidden
- 404 = Not Found
- 409 = Conflict
- 500 = Internal Server Error


### Idempotency

Idempotent = doing the same request multiple times gives the same result as doing it once.

- Idempotent: GET, PUT, DELETE
- Not idempotent: POST
- Sometimes: PATCH

Why it matters: networks retry requests. Idempotent requests are safe to retry. Non-idempotent (POST) can cause duplicates.

### Tools Set Up Today

- Installed VS Code (code editor)
- Created file: victdev.js
- Did not sign in to GitHub in VS Code (optional)
