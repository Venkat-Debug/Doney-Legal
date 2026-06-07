# Doney Legal Pages

Public privacy policy and terms of service for the Doney mobile app.

**This repo contains only legal HTML pages — no app source code.**

## Live URLs (after GitHub Pages is enabled)

- Privacy: https://venkat-debug.github.io/Doney-Legal/privacy.html
- Terms: https://venkat-debug.github.io/Doney-Legal/terms.html

## One-time setup

1. Create a new **public** repo on GitHub named `Doney-Legal`
2. Push this folder:

   ```bash
   cd /Users/venkatpasala/Doney-legal
   git init
   git add .
   git commit -m "Add privacy policy and terms of service"
   git branch -M main
   git remote add origin https://github.com/Venkat-Debug/Doney-Legal.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages**
   - Source: Deploy from branch
   - Branch: `main`
   - Folder: `/ (root)`
   - Save

4. Wait 1–2 minutes, then open the privacy URL above.
