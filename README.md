# Sanika Sabale – Portfolio

A static website: plain HTML and CSS in a single `index.html`. There is no React, no build step and no dependencies to install.

## Files
- `index.html` – the whole site (HTML, CSS, and your photo embedded so it never breaks)
- `assets/photo.jpg` – the same photo as a normal file (a copy, handy for other uses)
- `vercel.json`, `package.json`, `.gitignore` – optional deployment/dev helpers

Fonts (Bricolage Grotesque, Figtree) load from Google Fonts, with system fallbacks if offline.

## Run locally
Option 1: double-click `index.html`.
Option 2 (needs Node.js): `npm start`, then open the address it prints.

## Put it on GitHub
```
git init
git add .
git commit -m "Add portfolio"
git branch -M main
git remote add origin https://github.com/heyitzsanika/<repo-name>.git
git push -u origin main
```
Create the empty repo `<repo-name>` on github.com first.

## Deploy to Vercel
1. Sign in at vercel.com with your GitHub account.
2. Click Add New > Project and import the repository.
3. Framework Preset: Other. Leave Build Command and Output Directory empty.
4. Click Deploy. Every `git push` to `main` redeploys automatically.

## Editing
Change text directly in the `<body>` of `index.html`. Colors are the variables at the top of the `<style>` block.
