# Ofir Webpage

Personal website repository for GitHub Pages.

## Project Structure

- `index.html` - main site page
- `404.html` - custom not found page
- `.nojekyll` - tells GitHub Pages to serve files directly without Jekyll processing
- `.gitignore` - local and OS files to ignore in git

## Run Locally

Open `index.html` in your browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Go to repository Settings -> Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Select branch `main` and folder `/ (root)`.
5. Save and wait for the deployment.

Your page will be available at:

`https://<your-username>.github.io/<repo-name>/`
