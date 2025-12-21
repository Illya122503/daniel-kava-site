Daniel Kava - Static site

This repo contains a static website for Daniel Kava (HTML, CSS, images).

How to publish to GitHub Pages (web upload):

1. Create a new repository on GitHub.
2. In the repository page, click "Add file" → "Upload files" and drag the
   contents of this project (not the parent folder) — `index.html`, `scc/`,
   `images/`, `README.md`, `.nojekyll`.
3. Commit the changes.
4. Go to Settings → Pages → Source: choose "Deploy from a branch" and set the
   branch to `main` (or default) and folder to `/ (root)`.
5. Wait a minute and open `https://<your-username>.github.io/<repo-name>/`.

If CSS is not loading:

- Open Developer Tools (F12) → Network → reload page and look for
  `scc/style.css` or other 404 errors.
- Ensure files have been uploaded and paths are correct (case-sensitive on
  GitHub).
- If filenames had spaces or special characters, they might not be referenced
  correctly; I renamed images to safe filenames (lowercase, hyphens).
