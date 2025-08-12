# Tydra Sanitation — v4.3.2
**Change:** Form now posts with `Content-Type: text/plain` to avoid browser CORS preflight with Apps Script.

## Where your leads go
Sheet: https://docs.google.com/spreadsheets/d/1A-EswuPUIkB30izlWxMny-dLEhZG_uvQayZ0c0C5aRA/edit
Tab: `Leads` (created automatically).

## Apps Script snippet (already shared earlier)
Make sure your script uses your sheet ID and is deployed as a Web App (Execute as **Me**, Who has access **Anyone**).

## Plausible events
- `lead_submitted` on submit
- `lead_thankyou` on thank-you page

