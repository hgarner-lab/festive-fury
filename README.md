# Festive Fury

A standalone HTML5 pixel-art Christmas game. No npm dependencies or build step are needed.

## Deploy on Vercel

- Connect this GitHub repository to a Vercel project.
- Use the **Other** framework preset. The root directory is `.` and the output directory is `.`, as specified in `vercel.json`.
- Vercel serves `index.html` at `/`. The original `Festive_Fury_Final.html` is preserved.
- Push or merge to the production branch to redeploy.

## Microsoft Teams link previews

The homepage includes title and description metadata, Open Graph and Twitter Card tags, and schema.org JSON-LD. The file `festive-fury-preview.png` is a static 1200 × 630 social thumbnail.

After deploying, verify that `https://festive-fury.vercel.app/` and `https://festive-fury.vercel.app/festive-fury-preview.png` are publicly accessible without sign-in. Paste the homepage URL into a fresh Teams chat to preview it. Teams can cache earlier link previews, and an organisation's Teams policies may affect whether previews are displayed.

The site is a single HTML file; all game CSS and JavaScript live inside `index.html`.
