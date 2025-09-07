# Read Aloud — Bookmarklet

Lightweight bookmarklet that uses your browser's text-to-speech to read selected text or the whole page.

Why use this
- No install required — just a bookmark.
- Works offline in modern browsers that support speechSynthesis.
- Quick accessibility helper for reading articles, docs, and emails.

Quick install
1. Show your browser's bookmarks bar.
2. Create a new bookmark.
3. For the bookmark's URL, paste the bookmarklet code from the repo (the file ending in .js or the provided `javascript:(...)` string).
4. Name it "Read Aloud" and save.

How to use
- Select some text and click the "Read Aloud" bookmark to read only the selection.
- If nothing is selected, clicking the bookmark reads the main page text.
- Click the bookmark again to pause/resume. Use your browser's media controls to stop.

Notes
- Requires a browser that supports window.speechSynthesis (Chrome, Edge, recent Firefox, Safari).
- If no voice is heard, check browser TTS settings and available voices.
- Some pages block scripts; try a different page if it doesn't run.

License
MIT — see LICENSE file.

Made by @FlameShip
