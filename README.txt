Tydra Sanitation — v4.5 (Apps Script + spam guard + toast + UTMs)
Posts to your Apps Script Web App:
https://script.google.com/macros/s/AKfycbwIxBmvil2UIJ-PSWfdZj7zPn7eSClDaesjnk7qMTKHqwkaUaHKCtj-2KfiHLX5j1Lk/exec

### What changed
- Keeps Google Sheets logging (Apps Script).
- Honeypot + 3s guard + double-submit lock.
- Small 'Sent' toast, then redirect to /thank-you.html.
- Captures UTMs and includes them in the payload; CTAs append UTMs where possible.

### Test after deploy
1) Open https://script.google.com/macros/s/AKfycbwIxBmvil2UIJ-PSWfdZj7zPn7eSClDaesjnk7qMTKHqwkaUaHKCtj-2KfiHLX5j1Lk/exec in a tab — should show OK.
2) Submit the form → you should land on /thank-you.html.
3) Check your 'Leads' tab in the Google Sheet for the new row.
