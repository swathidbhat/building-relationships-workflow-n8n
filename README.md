Meet someone in real life, take a screenshot of their LinkedIn preview, share screenshot and personal notes via Google Form. For convenience, add the specific Google Form link as a shortcut on phone's home page. Get app-like access without having to build an app.  

This automation takes care of the rest. Precisely:
Process a Drive image, extract profile fields with OpenAI Vision, normalize them, append to Google Sheets, and draft a LinkedIn follow-up grounded in your notes and their LinkedIn.

Flow

Form/Sheet row ingested (includes Drive link + NOTES).

Drive Download (binary data).

OpenAI · Analyze image (vision).

Code · Structure info (normalize fields).

OpenAI · Chat (LinkedIn follow-up using NOTES + fields).

Google Sheets · Append.
