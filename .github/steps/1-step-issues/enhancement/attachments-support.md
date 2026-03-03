# 📎 Add Support for Attachments

The advanced backend allows workshops/activities to have attachments (images,
documents) and tracks their status. Our simple system stores only text fields.

Enhancements:

- Define an `Attachment` model linked to activities.
- Allow users to upload files via the API and serve them from the static folder.
- Track attachment metadata (filename, type, upload date) and expose it in
  activity responses.

This would enable richer activity descriptions (flyers, forms, etc.).
