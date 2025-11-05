# Client Intake Form

A modern, multi-step client intake form powered by Tailwind CSS. Includes progress bar, validation, autosave (localStorage), and Formspree integration.

## Live site (GitHub Pages)
After enabling GitHub Pages, your site will be available at:

- https://alphatronomegaroo.github.io/Client_Intake_Form/
- Direct file link: https://alphatronomegaroo.github.io/Client_Intake_Form/Client_Intake_Form.html

## Configure Formspree
1. Create a form at https://formspree.io/ (copy your endpoint like `https://formspree.io/f/xxxxx`).
2. Open `Client_Intake_Form.html` and replace the `action` URL:
   ```html
   <form action="https://formspree.io/f/YOUR_UNIQUE_ID" method="POST">
   ```
3. Optional: keep the `_redirect` hidden input set to your GitHub Pages URL so users see a friendly success state.

## Local preview
- Double-click `Client_Intake_Form.html` to open in your browser.
- Fill the form to test validation and autosave.

## Deploy to GitHub Pages
1. Push to GitHub (already done).
2. On GitHub repo: Settings → Pages → Source: Deploy from a branch → Branch: `main` → Folder: `/root`.
3. Wait ~1–2 minutes for the site to build.

## Notes
- Honeypot `bot_field` is included for lightweight spam protection.
- Line ending warnings (LF/CRLF) on Windows are harmless.
- No build step required; this is a static site.
