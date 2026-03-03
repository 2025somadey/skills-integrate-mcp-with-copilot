# 📄 Support JSON‑Driven Templates

Right now activities are hard‑coded in `app.py`. We could extract text fragments (open paragraph variants, coop descriptions, extracurricular activity blurb, etc.) into a JSON file and load them at runtime.

Benefits:

- Non‑developers can update or add new paragraphs/activity descriptions without touching Python code.
- Placeholder substitution (`{company_name}`, `{position}`, etc.) could be performed automatically.
- The same file could track personal/contact information and be written back with user updates.

----- COMMENTS -----
This approach mirrors authoring workflows for the eventual cover‑letter generator and would make the app more flexible.
