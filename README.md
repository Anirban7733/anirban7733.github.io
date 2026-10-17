# Personal website

Plain HTML/CSS site served by GitHub Pages. No build step.

## Files
- `index.html` — all content. Search for `EDIT` and `[` to find placeholders.
- `style.css` — styling (colors at the top; dark mode follows the system setting).
- `images/profile.jpg` — your photo (add it, then swap the placeholder div in `index.html`).
- `files/cv.pdf` — your CV.
- `.nojekyll` — tells GitHub Pages to serve files as-is.

## Deploy (first time)
1. On github.com, create a **public** repo named exactly `<username>.github.io` (no README).
2. In this folder:
   ```
   git init -b main
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/<username>/<username>.github.io.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
4. The site appears at `https://<username>.github.io` after a minute or two.

## Update
Edit files, then `git add . && git commit -m "Update" && git push`.
