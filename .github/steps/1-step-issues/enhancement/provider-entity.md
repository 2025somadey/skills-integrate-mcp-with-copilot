# 🏫 Add Provider and Parent/Child Entities

The OoS platform distinguishes between organizations that offer activities
("providers") and the parents and children who sign up for them. Our minimal
model only tracks activities and participant emails.

Proposed enhancements:

- Introduce `Provider` objects that own workshops/activities.
- Create `Parent` and `Child` models so signups are tied to a family rather
  than a bare email address.
- Update APIs and frontend to manage providers and parent/child profiles.

This lays the foundation for more realistic workflows and multi-tenant use.
