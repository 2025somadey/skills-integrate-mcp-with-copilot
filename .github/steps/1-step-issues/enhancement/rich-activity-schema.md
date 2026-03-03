# 🗂️ Expand Activity Schema & Sample Data

Current activities only have a description, schedule and participant list.
To support filtering and richer UI, we should:

- Add `schedule_details` with explicit `days`, `start_time`, and `end_time`.
- Populate more realistic sample activities (weekend workshops, tournaments,
  etc.) during initialization.
- Ensure the frontend displays the new information correctly.

This gives students more context and enables server-side queries.
