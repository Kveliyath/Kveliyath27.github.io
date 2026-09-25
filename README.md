# Kartik Veliyath — Mechanical Engineering Portfolio

A single self-contained `index.html` file — no build step, no dependencies to install.
All images, the demo video, and the CDR slide deck are embedded directly in the page
as base64 data, so this one file is the entire site.

## Host it for free with GitHub Pages

1. Create a new GitHub repository (public).
2. Upload `index.html` to the root of the repo (keep the filename as `index.html`).
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Pick the `main` branch and `/ (root)` folder, then **Save**.
6. GitHub gives you a live URL after a minute or two, usually:
   `https://<your-username>.github.io/<repo-name>/`

That's it — no other configuration needed.

## Editing

Everything (HTML, CSS, and JavaScript) lives in the one `index.html` file. Open it in
any text editor. Search for `:root {` near the top to find the color variables if you
want to tweak the theme.

## File size

This file is ~14 MB because the photos, video, and slide deck are embedded inline
rather than linked externally. GitHub's per-file limit is 100 MB, so this is well
within range — but note that regular `git clone`/`pull` will download the full file
each time since it's a single binary-ish blob to Git (not much to diff).
