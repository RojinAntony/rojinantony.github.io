# Rojin Antony — Portfolio Website

A responsive, light-themed portfolio website for a Linux/server infrastructure engineer moving toward cloud and DevOps roles. Built with plain HTML, CSS, and JavaScript; no build tools or paid hosting are required.

## Files

- `index.html` — page content and metadata
- `styles.css` — responsive styling and visual design
- `script.js` — mobile navigation and current footer year

## Before publishing

1. Open `index.html`.
2. Replace `YOUR_EMAIL@example.com` with your professional email address.
3. Add your LinkedIn URL if you want one (there is currently no LinkedIn link).
4. Review the project and experience descriptions. Keep only statements you can comfortably discuss in an interview.
5. Add links to real public repositories, diagrams, or sanitized case studies as you publish them.

## Publish with GitHub Pages

### Option A: Upload using the GitHub website

1. Sign in to GitHub as `rojinantony`.
2. Open <https://github.com/new>.
3. Create a **public** repository named exactly `rojinantony.github.io`.
4. Keep it simple: you can skip adding a README, `.gitignore`, or license because this package already contains a README.
5. Open the new repository and choose **Add file → Upload files**.
6. Upload `index.html`, `styles.css`, `script.js`, and `README.md` from this folder. Upload the files themselves, not the parent folder.
7. Commit the files to the `main` branch.
8. Open **Settings → Pages**.
9. Under **Build and deployment**, select **Deploy from a branch**.
10. Select branch **main** and folder **/(root)**, then click **Save**.
11. Wait a few minutes, then open <https://rojinantony.github.io>.

### Option B: Upload with Git

From a terminal in this folder, run:

```bash
git init
git add index.html styles.css script.js README.md
git commit -m "Create portfolio website"
git branch -M main
git remote add origin https://github.com/rojinantony/rojinantony.github.io.git
git push -u origin main
```

If Git asks you to authenticate, use GitHub's browser authentication or a supported personal access token; your normal account password is not accepted for Git HTTPS pushes. If the repository already exists or already has content, inspect it before running these commands and do not overwrite work you need.

Then enable GitHub Pages at **Settings → Pages** as described above.

## Updating the site later

Edit the files locally or choose a file in GitHub and click the pencil icon. Commit the change to `main`; GitHub Pages will publish the update automatically.

## Important notes

- GitHub Pages gives this project a free `github.io` address; you do not need to purchase a domain.
- This is a static website. It does not include a server-side contact form or store messages. The email link opens the visitor's email app.
- Keep secrets, customer information, private IP addresses, server hostnames, credentials, and confidential infrastructure diagrams out of public repositories.
