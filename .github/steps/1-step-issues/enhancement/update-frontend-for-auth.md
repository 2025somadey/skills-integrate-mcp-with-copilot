# 🖥️ Update Frontend for Authenticated API

The static UI currently posts directly to unprotected endpoints.

Enhancements:

- Modify `app.js` to call `/auth/login` and store the returned session in
  memory (or localStorage).
- Update signup/unregister requests to include the teacher identifier (query
  or header) obtained after login.
- Adjust UI behaviour when not authenticated (disable register buttons or
  redirect to a login form).

This ensures only logged‑in staff can modify activity rosters.
