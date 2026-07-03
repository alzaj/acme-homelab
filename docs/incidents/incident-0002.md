2026-07-03

Symptom:
403 Forbidden

Cause:
Apache denied access because the new DocumentRoot had no matching <Directory> rule.

Detection:
- Browser
- Apache error.log

Fix:
Added a matching <Directory> section with appropriate access control.

Lesson learned:
Changing DocumentRoot alone is not sufficient. Apache access control is configured separately.