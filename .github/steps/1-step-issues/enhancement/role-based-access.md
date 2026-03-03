# 🔒 Implement Role-Based Access Controls

The OoS backend uses ASP.NET authorization attributes and distinguishes teachers,
providers, parents, and admins. Our simple app has no authentication at all.

Possible improvements:

- Add user accounts with roles (teacher, admin, maybe parent).
- Protect sensitive endpoints (`/activities/signup`, `/unregister`) with role
  checks rather than accepting any email.
- Allow admins to manage users and activities separately.

This will make the system more secure and suitable for a multi-user context.
