# 📎 Add Export/Conversion to PDF

After building a `.docx` or other document, automatically convert it to a portable format and clean up intermediate files.

Specifically:

- Use a library (e.g. `python-docx`) to generate a Word document.
- Invoke `abiword` or similar to convert to PDF.
- Delete the `.docx` once conversion succeeds.

This ensures students and staff have a ready‑to‑send file and avoids cluttering the repo with temporary documents.

----- COMMENTS -----
A simple script could live alongside the FastAPI server or as a separate `make` target.