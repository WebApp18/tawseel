# Tawseel / Brand Fashion Preview

Static website preview built from the uploaded Figma/image reference.

## Files

- `index.html` — main page
- `styles.css` — all styling and responsive layout
- `assets/` — local images exported from the Figma file
- `.nojekyll` — keeps GitHub Pages from changing asset handling

## How to preview locally

Open `index.html` in a browser.

Or run a tiny local server:

```bash
python -m http.server 8000
```

Then open:

```txt
http://localhost:8000
```

## How to publish on GitHub Pages

1. Create a GitHub repository.
2. Upload all files from this folder to the root of the repo.
3. Make sure `index.html` is in the root of the repo.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select `main` branch and `/root` folder.
7. Save.

Your preview should become available as:

```txt
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

If the repo is named `YOUR_USERNAME.github.io`, then it becomes:

```txt
https://YOUR_USERNAME.github.io/
```
