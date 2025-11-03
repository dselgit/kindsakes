# Kindsakes – Static Demo (No Backend)
This is a **single-file** demo you can deploy anywhere (Vercel, Netlify, GitHub Pages). It simulates sending keepsakes, viewing a private inbox, login, FAQ editing, and an admin copy editor — all using `localStorage` so you can test the UX without servers or email.

## Files
- `index.html` – everything lives here (HTML/CSS/JS).

## Run locally
Open `index.html` in a browser.

## Deploy (Vercel - easiest)
1. Go to **vercel.com**, create a New Project → Deploy from a directory.
2. Drag & drop this folder. Vercel will host it as a static site.
3. You’ll get a URL like `https://kindsakes-demo.vercel.app`.

## After testing
- Replace placeholders (domain/email) when you're ready for the real build.
- For real emailing & accounts, we’ll swap the localStorage parts with a tiny backend.
