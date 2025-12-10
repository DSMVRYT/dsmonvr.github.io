DSMONVR website
=================

This repository contains a simple, responsive personal site for a content creator (videos, livestreams, social links). It's ready to publish using GitHub Pages.

Quick publish (recommended: user site)

- If you want your site to be available at `https://USERNAME.github.io`, create a repository named `USERNAME.github.io` (replace `USERNAME` with your GitHub username) and push the contents of this folder to the `main` branch.

Example commands (replace `USERNAME` and optionally the remote URL):

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin git@github.com:USERNAME/USERNAME.github.io.git
git push -u origin main
```

If you prefer HTTPS remote use:

```bash
git remote add origin https://github.com/USERNAME/USERNAME.github.io.git
git push -u origin main
```

You can also create the repo and push in one command with the GitHub CLI:

```bash
gh repo create USERNAME/USERNAME.github.io --public --source=. --remote=origin --push
```

Notes
- For a `USERNAME.github.io` repository, GitHub Pages serves the site automatically from the `main` branch.
- For a project site (other repo name), enable Pages in the repository settings and choose the branch/folder (e.g., `main` or `/docs`).

Optional: custom domain

- To use a custom domain, add a file named `CNAME` at the repo root containing your domain (e.g., `example.com`).
- Configure your DNS provider to point the domain to GitHub Pages. For an apex domain, add A records to GitHub Pages IPs; for subdomains, add a CNAME to `USERNAME.github.io`.

Support
- If you'd like, I can:
  - customize the `index.html` content (add your social links and embedded latest video),
  - create a `CNAME` file for a custom domain,
  - generate additional pages (blog, schedule), or
  - add a deploy GitHub Action to automate releases.

Happy to continue — tell me what you'd like to edit next.
