# 🔐 Add Teacher Authentication

Protect signup/unregister operations by requiring teacher credentials.

- Create `/auth/login` and `/auth/check-session` endpoints.
- Store teacher accounts in the database with hashed passwords.
- Require a `teacher_username` (and later token) when posting to
  `/activities/{name}/signup` and `/unregister`.

This prevents unauthorized modifications and lets us support roles such as
`teacher` vs `admin`.
