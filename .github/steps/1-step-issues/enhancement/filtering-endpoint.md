# 🔎 Support Filtering on `/activities`

Enhance the activities API to allow clients to filter results by schedule.

- Accept query parameters such as `day`, `start_time`, and `end_time`.
- Build the appropriate database query (or in-memory filter while persisting
  info) to return only matching activities.
- Add a new endpoint like `/activities/days` that returns all days with
  scheduled activities.

This makes the UI more useful when students search by day/time.
