# Abhay Singh — DevOps / SRE Portfolio

A single-page portfolio site styled as an infrastructure status dashboard — built for a Site Reliability / DevOps Engineer.

## Deploy to GitHub Pages (5 minutes)

1. Create a new GitHub repo, e.g. `abhaysingh.github.io` (for a root URL) or any name like `portfolio`.
2. Upload these files to the repo (keep them in the root):
   - `index.html`
   - `AbhaySingh_Resume.pdf`
   - `README.md`
3. In the repo: **Settings → Pages → Source → Deploy from a branch → `main` / `(root)` → Save.**
4. Your site goes live at:
   - `https://<your-username>.github.io/` (if repo is named `<username>.github.io`)
   - or `https://<your-username>.github.io/<repo-name>/` (any other repo name)

## Before you publish — update these placeholders

In `index.html`, search and replace:
- `github.com/abhaysingh` → your real GitHub URL
- `linkedin.com/in/abhaysingh` → your real LinkedIn URL

## Local preview

Just open `index.html` in a browser, or run:
```
python3 -m http.server 8000
```
and visit `http://localhost:8000`.

## Structure

```
.
├── index.html              # entire site (HTML + CSS + JS, no build step needed)
├── AbhaySingh_Resume.pdf   # linked from the "Download Resume" button
└── README.md
```
