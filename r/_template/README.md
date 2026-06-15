# Tailored resume version — template

Copy this `_template` folder to create a new tailored version. Each version is
a folder whose `index.html` **is** the resume — the recipient's link opens it
directly (no video landing page).

## Make a new version

1. **Copy the folder** and rename it to a role-type slug (no company names):
   - `r/_template`  →  `r/sales`, `r/engineering`, `r/product`, `r/data`, etc.
2. **Replace `index.html`** in the new folder with your tailored resume export.
3. **Commit & push.** The link to send is:
   `https://ryanrinkel.github.io/hire-me-video/r/<role>/`

## Notes

- The `_template` folder starts with `_`, so GitHub Pages (Jekyll) does **not**
  publish it. Real versions must use names without a leading underscore.
- Slugs are readable, so they are guessable. Don't put anything in a version
  you wouldn't want another recipient to stumble onto.
- The site's main page (`/index.html`) still shows the AI video + general
  resume. Tailored links bypass it and go straight to the resume.
