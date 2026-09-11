# Yunhan Zhao — Personal Website

A responsive, static academic homepage built for GitHub Pages. No build step or dependencies are required.

## Publish at `vinsonzyh.github.io`

1. Sign in to GitHub and create a **public** repository named exactly `Vinsonzyh.github.io`.
2. Do not add a README, `.gitignore`, or license on GitHub because this folder already contains the site files.
3. Open Terminal in this folder and run:

```bash
git init
git add .
git commit -m "Create personal academic homepage"
git branch -M main
git remote add origin https://github.com/Vinsonzyh/Vinsonzyh.github.io.git
git push -u origin main
```

4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`. Save.
6. The site will appear at `https://vinsonzyh.github.io` after GitHub finishes deployment.

## Update the site later

Edit `index.html` or `styles.css`, then run:

```bash
git add .
git commit -m "Update homepage"
git push
```

## Files

- `index.html` — page content and links
- `styles.css` — visual design and responsive layout
- `CV_onepage.pdf` — downloadable CV
- `favicon.svg` — browser tab icon
