Deploying this page

Files created/updated:
- `index.html` — copied from your `resume website.html` (ready for static hosting)

Notes:
- Your images currently reference local OneDrive paths (e.g. `C:\Users\Prasanna\OneDrive\...`). Those will not load when deployed. Upload images to the repo (place in an `images/` folder) and update the `src` attributes to relative paths.

Quick: Deploy to GitHub Pages

1. Create a new GitHub repository (or use an existing one).
2. In this folder, run:

```bash
git init
git add .
git commit -m "Deploy resume"
# create remote (replace with your repo URL):
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

3. On GitHub: open the repository > Settings > Pages (or "Pages" in left sidebar). Set Source to `main` branch and folder `/ (root)`, then Save. Your site will be served at `https://<your-username>.github.io/<repo>/`.

Alternative: Netlify (fast, no CLI)
- Go to https://app.netlify.com/drop and drag `index.html` (and any asset folders). Netlify will publish a site immediately.
- Or connect your GitHub repo in Netlify for continuous deploys.

Alternative: Vercel
- Install the Vercel CLI or connect your GitHub repo at https://vercel.com/import and deploy.

If you'd like, I can:
- push this folder to a new GitHub repo for you (you'll need to provide the repo name and allow a browser auth step), or
- set up a Netlify automatic deploy (I can prepare a ZIP or help with the drag-and-drop).

Which would you prefer? GitHub Pages or Netlify?