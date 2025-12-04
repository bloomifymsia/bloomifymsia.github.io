# Bloomify - Static Mockup

This is a small static e-commerce mockup for demonstration and testing. It contains multiple HTML files and assets.

How to run locally:

- Option 1: VS Code Live Server extension — open `index.html` and click "Open with Live Server".
- Option 2: Python HTTP server:

```powershell
cd 'C:\Users\user\Desktop\my website'
python -m http.server 8000
# then open http://localhost:8000
```

Deploy to GitHub Pages:

1. Create a repository on GitHub.
2. Add the repo as a remote and push:

```powershell
cd 'C:\Users\user\Desktop\my website'
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

3. On GitHub: go to Settings → Pages → select `main` branch and `/ (root)` folder, save.

Notes:
- This is a static site using local files via `file:///` paths for images. When deploying, host image assets under the repo or update image paths to relative paths.
- If images don't load after deploy, replace `file:///` image sources with relative paths inside the repo.
