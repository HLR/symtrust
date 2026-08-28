# SymTrust workshop website

Static website for **SymTrust: Symbolic Methods for Trustworthy and Verifiable Reasoning**, an ACL workshop.

## Preview locally

Open `index.html` in a browser. No build tools or dependencies are required.

## Publish with GitHub Pages

1. Create a new GitHub repository and push this folder to its `main` branch.
2. On GitHub, open **Settings → Pages** and set **Source** to **GitHub Actions**.
3. Pushes to `main` automatically deploy the website through the workflow in `.github/workflows/deploy-pages.yml`.
4. The Pages URL appears in the deployment workflow summary. For a repository named `symtrust`, it is usually `https://<your-github-username>.github.io/symtrust/`.

Before publishing, replace the provisional ACL year, dates, location, submission link, and speaker status as they become available.
