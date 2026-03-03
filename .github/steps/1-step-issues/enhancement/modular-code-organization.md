# 📂 Refactor into Routers & Database Module

Split the monolithic `app.py` into multiple modules for clarity and
maintainability.

- Extract database configuration (Mongo client, collections, init) into
  `backend/database.py`.
- Move activities-related endpoints into `backend/routers/activities.py`.
- Optionally add an authentication router (`backend/routers/auth.py`).
- Keep the top-level `app.py` minimal, importing and including routers.

Cleaner structure eases future growth and mirrors the exercise repo layout.
