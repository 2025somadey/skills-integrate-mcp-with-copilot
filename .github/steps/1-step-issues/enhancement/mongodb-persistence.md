# 💾 Add MongoDB Persistence

Currently the app stores activities in a transient in-memory dictionary that
is lost when the server restarts.  A more realistic system should use a
persistent database (MongoDB as in the exercise version).

Tasks:

- Introduce a `database.py` module to configure `pymongo` and expose
  `activities_collection` (and optionally a `teachers_collection`).
- Write initialization code that seeds sample data if the collections are empty.
- Update API routes to query/update the MongoDB collections instead of the
  in-memory dict.

This lays the groundwork for data filtering, authentication, and scaling.
